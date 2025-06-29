# Accessibility Issues - AAArdvark

Back to
				Basics				Guides

![](https://aaardvarkaccessibility.com/wp-content/uploads/2023/08/a11y-Help-Center-Icons_Setup-copy.png) 
# Accessibility Issues

 

## Introduction

AAArdvark’s issue management system is designed to make accessibility remediation simple and efficient for your team. Just run a scan to get started and uncover the issues that need attention.

You must run a scan on the site you wish to view issues for first, or this menu item will not be accessible.

## Basic Concepts

There are a few important concepts to understand before diving into the Issues tab.

### Issues

Accessibility issues on your site are mapped to specific WCAG Success Criteria, such as insufficient contrast or missing descriptive text. Think of an issue as a category of problem that may have multiple occurrences.

### Instances

An instance is a specific example of an issue on your site. For example, a missing alt text issue may have instances on several images across multiple pages.

We use advanced pattern matching in an attempt to group like issues together. This grouping enables developers to better identify the source template for grouped instances, even if they occur on multiple pages of your site.

![](https://aaardvarkaccessibility.com/wp-content/uploads/2023/05/image-38.png)Issue instances that appear on several pages.
### Issue Categories

Issues in AAArdvark are categorized into three groups to help prioritize remediation:

Tip: Start by addressing Errors, as they represent the most critical and actionable accessibility issues, then move on to Warnings and Notices as part of a comprehensive review.

## Issue Trends and Data

### Site Statistics

The Site Statistics in the dashboard provide a summary of the issues on the site. A graphic will display issues by impact, and from there, the issues can be visited.

Active Issues will be tracked as well, displaying the most common issues found on the site.

Additionally, Average Instances/Page with the most problematic pages will be presented in this view.

![](https://aaardvarkaccessibility.com/wp-content/uploads/2023/05/image-12.png)Site Statistics displays issues by impact, active issues, and average instances per page.
### Count History

The Count History section in the dashboard provides a graph view of issues and issue instances over time, based on the most recent scan.

A graph for the issues can be seen, showing issues scanned over time.

![](https://aaardvarkaccessibility.com/wp-content/uploads/2023/05/image-27.png)An issue count history showing the issues recorded over time since August 2024.
Another tab with issue instances can be viewed, showing issue instances scanned over time.

![](https://aaardvarkaccessibility.com/wp-content/uploads/2023/05/image-28.png)Issue instances count history is displayed in a graph, from August 2024 to April 2025.

## Accessibility Issues for a Site

After a site scan or manual auditing, discovered issues will be listed under the Issues tab on your Site’s Dashboard.

### Filtering Issues

Use the filters in the Issues tab to search, sort, and prioritize accessibility issues. Filters include severity, status, assignment, and more, helping you focus on what matters most.

![](https://aaardvarkaccessibility.com/wp-content/uploads/2023/05/image-24.png)Overview of filtering issues.
Search Issues

Search for issues by entering keywords, WCAG criteria, or descriptions. For example, you can search for ‘color contrast’ or a specific success criterion like ‘1.4.3.’

Sort Issues

Sort issues by priority to focus on what needs attention first. Priority is determined by:

You can also sort issues by severity or chronological order.

Severity

Issues can be filtered by Severity, all of which is determined by the impact the issue has on the site users. The choices available are:

Type

The Type dropdown can be used to filter issues depending on whether they were caught in an Automatic scan, or added as a manual issue. The choices available are:

Status

Issues can be sorted by Status, whether they are active, resolved, or not an issue. This allows users to discern what issues need resolving and are already resolved. The choices available are:

Assigned To

To find out which issues are assigned to certain assignees, the Assigned To filter will allow users to select which assignee they want to filter by. Issues that have been assigned to other Workspace users will appear under the filter. If they have not been assigned to anyone, they will remain under the Unassigned filter.

The choices available are:

Success Criteria

Issues can be sorted by WCAG Success Criteria. Depending on the Success Criteria of issues captured on the site, either through automatic or manual audits, these criteria will be listed out on the dropdown to use as filters.

![](https://aaardvarkaccessibility.com/wp-content/uploads/2023/05/image-14.png)Success Criteria dropdown depicting WCAG criteria for accessibility issues.
Pages

The Pages filter can be utilized to view the list of issues for specific pages or the overall site. You can also search pages by their slug.

This allows users to see what issues have been found on certain pages and address them individually.

![The All Pages option under the AAArdvark Accessibility Issues filter.](https://aaardvarkaccessibility.com/wp-content/uploads/2023/05/image2.png)Filter the issues by looking through pages in the dropdown.

### Viewing Issues

For each identified issue, you’ll see the following details:

![The image shows the issue list with summary details for each issue identified in the scan.](https://aaardvarkaccessibility.com/wp-content/uploads/2023/05/Issues-List.png)Issues detailing the issue number, severity level, detection status, instance, date, description, assignee, and number of comments.
### Issue Details

Click an issue in the Issues List to open the detail view. This includes:

Use the Previous Issue and Next Issue arrow buttons at the top of the page to navigate between the Issue Detail pages.

![Image displaying the issue details.](https://aaardvarkaccessibility.com/wp-content/uploads/2023/05/Issue-description.png)Details of an issue with information on what it means and how to fix it.
#### Issue Description Feedback

To leave feedback on an Issue Description, click Yes if you found it helpful, or No if you didn’t, under the “Was this helpful?” section.

If you choose No, a comment box will appear so you can share any suggestions for improvement. Our support team will receive and review your feedback.

![The image shows a comment box that opens up when you don't like the issue description.](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfW0rRS7srrz9iqSDy6HaUkRfBGBtU--25tZYa14Yu2yXhqbjyOSnY9fMCtKCJIyW15eWaF4k78iFGW7BYA72nrzBTdrJJj9bNyXa2oON97oYFJ_jsV-6-o8MpKND-DEPBU1jPbIA?key=f-jL1KzJ326BgeAuS9QnQfbM)A pop-up window accepting suggestions for improvement to submit for feedback.

### Issue Instances

Issue instances can be filtered in two ways:

![](https://aaardvarkaccessibility.com/wp-content/uploads/2023/05/image-42.png)A dropdown displaying the review status and pages where issue instances can be found and filtered by.
Filtering by Pages

Filtering Issue Instances by pages is especially useful if there are a lot of issue instances active on a site across numerous pages. One page, several pages, or all pages can be selected and displayed.

Filtering by Review Status

When you filter issues by whether they need review or not, only the relevant ones will show up, making it easier to focus on reviewing and verifying fixes.

### Assigning Issues

Assign issues to team members to streamline your workflow.

### Issue Status

The current status is visible in the top right and is one of Active, Resolved (pending scan or review), Resolved, or Not an Issue. Clicking on the issue will display a drop-down that will update the issue status.

![](https://aaardvarkaccessibility.com/wp-content/uploads/2024/08/image-3.png)Select dropdown to mark the issue as active, resolved, or not an issue.

### Resolving Issues

You can also set the status of an entire issue to fixed by choosing Resolve in the status drop-down on the top right of the issue page.

If any instances of these issues are seen in a subsequent scan, the issue will be reopened for you to take another look.

## Reviewing Issue Instances

To better scroll through the instances, you have the following options.

### Collapsible Instances

By default, all the instances are in expanded view. You can either collapse all instances together via the “Collapse All” option or use the collapse option on individual instances to collapse or expand an instance.

![](https://aaardvarkaccessibility.com/wp-content/uploads/2023/05/Collapsible-instances.png)The Collapse All button is highlighted above the Issue Instance list on the Issue Detail page within AAArdvark.

### Needs Manual Review

When the automated scanner detects issue instances that require human review (e.g., overlapping elements or ambiguous context), it flags them as Needs Manual Review.

In this case, a manual review of the Instance Details should be done to confirm whether the automated scanner’s detection is accurate.

![The screenshot shows the Needs Manual Review option for issues.](https://aaardvarkaccessibility.com/wp-content/uploads/2023/05/Needs-Manual-Review-Check.png)

### Instance URL

Click the URL under ‘Seen On’ to open the linked page in a new tab or switch to Visual Mode for issue viewing.

![An image that shows the options that get displayed when clicking the instance URL.](https://aaardvarkaccessibility.com/wp-content/uploads/2023/05/Instance-URL-options.png)

### Marking Instances as Fixed

Once you have resolved an instance, you can click the Mark as Fixed button to mark it as fixed. The fix will be confirmed during the next site scan or through manual review.

If an instance marked as fixed is seen in a subsequent scan, it will be labeled as Reopened for you to take another look. When all instances are confirmed Fixed or marked as Not an Issue, the issue will be automatically set as resolved.

![](https://aaardvarkaccessibility.com/wp-content/uploads/2023/05/image-39.png)

### Multi-Select Instances

You also have the option to multi-select instances and mark them as Fixed or Not an Issue.

![](https://aaardvarkaccessibility.com/wp-content/uploads/2023/05/image-41.png)Selecting multiple issues in an instance to mark them as fixed or not an issue.

### Viewing Instances on Pages

Instances can also be seen in a group of pages, allowing the ability to see where the issue appears with ease. Pagination is included if there are more than ten pages that the issue appears on.

![](https://aaardvarkaccessibility.com/wp-content/uploads/2023/05/image-25.png)Issue instances that appear on at least 11 pages.

## Commenting on Issues or Instances

Collaborate with your team by adding comments to issues or instances.

The team member who is tagged will receive a notification and email if it’s enabled for them.

## False Positives

Automated scans aren’t perfect and may flag ambiguous situations as issues. If you determine an issue is a false positive after manual review, mark it as Not an Issue to remove it from the active list.

## Still stuck?

File a support ticket with our five-star support team to get more help.

### File a ticket

  

## Related Guides

 

