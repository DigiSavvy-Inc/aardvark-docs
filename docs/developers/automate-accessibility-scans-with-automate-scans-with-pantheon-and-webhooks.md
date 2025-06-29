# Automate Accessibility Scans with Automate Scans with Pantheon and Webhooks

Back to
				Integrations				Guides

![](https://aaardvarkaccessibility.com/wp-content/uploads/2023/08/a11y-Help-Center-Icons_Integrations-copy.png) 
# Automate Scans with Pantheon and Webhooks

 

## Introduction

AAArdvark’s Webhooks integration allows you to automate accessibility scans, ensuring that your site remains accessible every time new code is deployed. This helps minimize the introduction of new accessibility issues during updates.

## Automate Accessibility Scans with Webhooks

Pantheon is a popular host for Drupal and WordPress projects. They provide the ability to execute commands as part of the deployment process using a system called Quicksilver.

### Step 1 – Add Site to AAArdvark

Add the site you created in Pantheon to AAArdvark. This could be your production, development, staging, or multidev environment. Anytime new code or updates are deployed to your site in Pantheon, and a site scan will be triggered in AAArdvark.

### Step 2 – Generate Webhook URL and Collect Site ID and Webhook Token

Create a generic Webhook integration to the site and copy the generated URL. We’ll extract the Site ID and Webhook Token from the URL.

The URL takes on this structure. However, we just need to take note of these two pieces in the URL:

https://webhooks.aaardvarkaccessibility.com/site/site_id_hash/scan/webhook_token

### Step 3 – Create a Secrets.json File or Add Keys to an Existing File

Add or update the secrets.json file with the content provided below. Make sure this file exists in your site’s /root/files/private/ directory; if it doesn’t exist, create the subdirectory.

Upload or update the file using SFTP with your favorite tool.

If you copy the files from one environment to another, you will need to update or remove the secrets.json file in the destination environment.

#### /root/files/private/secrets.json

Make sure to swap the aaardvark_site_id and aaardvark_webhook_token values for the Site ID and Webhook Token values you collected from the Webhook URL in Step 2.

```
{ "aaardvark_site_id": "3QdjF5", "aaardvark_webhook_token": "0c16e69038f8d46fdcfb9c832235af199ce9dad14ae625e0401c9daa13c0cef5" }
```

### Step 4 – Create the AAArdvark Script

Add the aaardvark.php file with the content provided below. Make sure this file exists in the site’s /root/code/private/scripts/ directory; if it doesn’t exist, create the subdirectory.

#### /root/code/private/scripts/aaardvark.php

This script posts a request to the AAArdvark webhook URL, initiating the scan.

```
<?php function loadSecrets() { 
$secretsFile = $_SERVER['HOME'].'/files/private/secrets.json'; 

if (!file_exists($secretsFile)) { 
throw new \Exception("Secrets file not found in the /files/private directory"); } 

$secretsContents = file_get_contents($secretsFile); 
$secrets = json_decode($secretsContents, 1); 

if ($secrets == false) { 
die('Could not parse json in secrets file.'); 
} 

$missing = array_diff(['aaardvark_site_id', 'aaardvark_webhook_token'], array_keys($secrets)); 

if (!empty($missing)) { 
throw new \Exception('Missing required keys in json secrets file: '.implode(',', $missing).'.'); 
} 

return $secrets; 
} 
try { 
$secrets = loadSecrets(); 
$url = "https://app.aaardvarkaccessibility.com/webhooks/site/{$secrets['aaardvark_site_id']}/scan/{$secrets['aaardvark_webhook_token']}"; 
$payload['source'] = 'Pantheon: ' . $_ENV['PANTHEON_ENVIRONMENT']; 
$payload = http_build_query($payload); 
$ch = curl_init(); 
curl_setopt($ch, CURLOPT_URL, $url); 
curl_setopt($ch, CURLOPT_POSTFIELDS, $payload); 
curl_setopt($ch, CURLOPT_POST, 1); 
curl_setopt($ch, CURLOPT_RETURNTRANSFER, 1); 
curl_setopt($ch, CURLOPT_TIMEOUT, 10); 
print("\n==== Posting to Webhook URL ====\n"); 
$result = curl_exec($ch); 
print("RESULT: $result"); 
print("\n===== Post Complete! =====\n"); 
curl_close($ch); } catch (\Exception $e) { 
print("\n==== Skipping: " . $e->getMessage() . " ====\n"); 
}
```

### Step 5 – Update the pantheon.yml Workflow

Add the following lines of code to your pantheon.yml file. If this file doesn’t exist, then create it at the topmost layer of your site.

Add or update the pantheon.yml file with the content provided below. Make sure this file exists in the site’s /root/code/ directory.

#### /root/code/pantheon.yml

This configuration triggers the AAArdvark scan after every code deployment.

```
api_version: 1 
workflows: 
  sync_code: 
    after: 
      - type: webphp 
      description: Scan for Accessibility Issues on Deploy 
      script: private/scripts/aaardvark.php
```

### Step 6 – Push to Your Pantheon Environment

In summary, you should now have three new files or file updates to the site that you’ll need to push to Pantheon:

![](https://aaardvarkaccessibility.com/wp-content/uploads/2023/05/Accessibility-Scan-Triggered-by-Pantheon-deployment-1024x673.png)Accessibility Scan triggered by deployment on Pantheon.
From now on, every time you push code to this environment, AAArdvark will automatically perform an accessibility scan, helping you maintain an inclusive and accessible website.

![](https://aaardvarkaccessibility.com/wp-content/uploads/2023/05/Full-Site-Scan-Triggered-by-Webhook-Pantheon-1024x277.png)Full Site Scan Triggered by Webhook/Pantheon showing in the AAArdvark Activity Log for the Site

## Still stuck?

File a support ticket with our five-star support team to get more help.

### File a ticket

  

## Related Guides

 

