# 3.3.8 Accessible Authentication (Minimum) - AAArdvark

[Understandable](https://aaardvarkaccessibility.com/wcag-principle/understandable/)

[Input Assistance](https://aaardvarkaccessibility.com/wcag-guideline/input-assistance/)

WCAG 2.2
Level AA

[View official documentation for WCAG 3.3.8](https://www.w3.org/WAI/WCAG22/Understanding/accessible-authentication-minimum.html)

# 3.3.8 Accessible Authentication (Minimum)

Authentication must be possible without cognitive challenges like memorization or solving puzzles, unless an alternative exists.

[Forms](https://aaardvarkaccessibility.com/wcag-theme/forms/) 

 

[Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Physical/Motor](https://aaardvarkaccessibility.com/wcag-disability/physical-motor/) 

 

[Code](https://aaardvarkaccessibility.com/wcag-responsibility/code/) 

## What is it?

Authentication, or the ability to log into a website, should not feel like a memory test. Having to remember passwords, transcribe codes, or solve puzzles can make logging in unnecessarily difficult. Instead, websites should offer simpler authentication options that reduce cognitive load.
Imagine trying to log into your bank account but struggling to recall the password you set months ago. You reset it, only to forget it again later. Sound familiar? This guideline ensures logging in doesn’t become a frustrating memory challenge.
The goal is to make authentication simple for everyone, especially those who have difficulty with memory or complex tasks.

## Why does it matter?

If logging in is too complicated, people may struggle to access essential services or give up altogether. Complex authentication can be a major barrier for people with cognitive disabilities, including those with reading disabilities and memory or perception limitations.
Issues that can happen during inaccessible authentication setups:

People forgetting their password and struggling with password resets
Difficulty figuring out how to transcribe one-time or time-limited codes from another device
Getting stuck on CAPTCHAs that require solving puzzles, math problems, or working with blurry images

These issues cause frustration and can prevent people from accessing critical services like banking, healthcare, or work-related platforms.

## Who is affected?

People with cognitive disabilities.

People with cognitive disabilities vary widely:

Those with memory limitations may struggle with remembering their passwords or security questions they previously entered.
Those with reading disabilities, such as dyslexia or dyscalculia, might have trouble transcribing codes or completing CAPTCHAs with distorted letters and numbers.
Those with attention disorders could lose focus when switching between screens for two-factor authentication methods.
Those with mental processing difficulties can find CAPTCHAs confusing or difficult to solve.

## How to implement 3.3.8

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

### Allow Alternative Login Methods.

Websites should offer at least one alternative method of logging in that doesn’t require memory or transcription rather than solely relying on passwords.
To meet this success criterion, at least one alternative from below should be available to help users avoid memorizing passwords and manually transcribing codes.
#### Support for Password Managers

Many people use password managers to store and autofill their login details so they don’t have to remember passwords themselves. Websites should support password managers so users can automatically fill in their credentials without needing to type them manually.
If a login form follows WCAG guidelines—specifically,  1.3.5 Input Purpose and  4.1.2 Name, Role, Value  —browsers and password managers can reliably recognize the email and password fields and automatically fill them in.
Login form with automatically filled-in email and password fields from the browser's built-in password manager.
#### Third-party Logins or OAuth

Another alternative is offering third-party logins or OAuth-based systems, such as “Login with Google” or “Log in with Facebook.” These allow users to log in with credentials from another account they already have access to, avoiding the need to remember another password.
This method is especially helpful for people who use multiple websites but prefer not to manage many different passwords.
Login form with additional buttons to allow third-party login methods.
#### Biometric Authentication

Biometric authentication, such as fingerprint scanning or facial recognition, makes logging in fast and easy - just a touch or glance instead of typing. Plus, it’s secure since biometric data is unique to each person.
Instead of remembering and entering a password, users can simply access their accounts with a quick touch or glance.
Login form with a biometric face scanning feature to allow users to bypass email and password fields.
#### Email-Based Login Links

Email-based login links allow users to verify their identity simply by clicking a link sent to their inbox, removing the need for password entry altogether.
A login form gives users the option to send themselves a login link via email.
### Improve Two-Factor Authentication (2FA)

When two-factor authentication (2FA) is required, it should avoid forcing users to manually transcribe verification codes. More accessible approaches include:

Push notifications, where users simply tap a confirmation button on their phone instead of entering a code.
QR codes to allow users to scan a code rather than typing in numbers.
Hardware-based authentication, such as security keys like YubiKey, provides a physical method to confirm identity without requiring complex cognitive tasks.

### Make CAPTCHAs Accessible

Ever struggled with a CAPTCHA that asks you to identify blurry street signs or distorted letters? Many people do. If CAPTCHAs are necessary, instead of requiring users to decipher distorted text or select objects in images, websites should offer:

Simple checkbox verification, for example, “I’m not a robot.”
Audio challenges that don’t require complex transcription
Object recognition tests where they select an image they uploaded earlier

### Provide a "Show Password" Option

Passwords are often hidden as you type, which can lead to mistakes. A simple “Show Password” option helps users see what they’re typing and avoid login errors.
A password field with a show password option toggled on and off.
### Support for Copy-and-Paste Functionality

Another necessity is to allow copy-and-paste functionality so that users can securely transfer credentials if needed. Blocking this feature only makes things harder, especially for those relying on password managers or assistive tools.

## Conclusion

Logging in should be easy. By removing memory-based authentication barriers and offering alternative login methods, websites can create a more accessible experience for everyone. Small changes can make a big difference in ensuring that all users, regardless of their cognitive capacity, can access their accounts with ease.

## Related Success Criteria

