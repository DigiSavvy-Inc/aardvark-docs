# 3.3.4 Error Prevention (Legal, Financial, Data) - AAArdvark

[Understandable](https://aaardvarkaccessibility.com/wcag-principle/understandable/)

[Input Assistance](https://aaardvarkaccessibility.com/wcag-guideline/input-assistance/)

WCAG 2.0, 2.1, 2.2
Level AA

[View official documentation for WCAG 3.3.4](https://www.w3.org/WAI/WCAG22/Understanding/error-prevention-legal-financial-data.html)

# 3.3.4 Error Prevention (Legal, Financial, Data)

Important forms like a legal agreement or submitting financial information offer the opportunity to check the information entered before sending.

[Forms](https://aaardvarkaccessibility.com/wcag-theme/forms/), [Wording](https://aaardvarkaccessibility.com/wcag-theme/wording/) 

 

[Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Visual](https://aaardvarkaccessibility.com/wcag-disability/visual/) 

 

[Code](https://aaardvarkaccessibility.com/wcag-responsibility/code/) 

## What is it?

Important actions like submitting legal or financial forms or deleting crucial data should either be reversible or require users to review and confirm before proceeding. This helps prevent mistakes that could be difficult—or even impossible—to fix later.
An important action is any online task that, if completed incorrectly, could have serious consequences. These include:

Signing contracts or filling out legal commitments
Submitting monetary transactions or financial documents
Deleting or modifying important data, such as user profiles, payment information, or stored records

## Why does it matter?

Mistakes happen, but for people with disabilities, they’re often harder to catch and fix, especially when completing forms, entering data, or navigating websites. Without a way to review, confirm, or undo actions, users may face serious consequences they can’t easily reverse.
Imagine a person with dyslexia filling out a mortgage application under a tight deadline. They accidentally enter their address incorrectly on multiple fields and submit the form. Later, they discover they can’t correct it because the deadline has passed—leading to a missed opportunity.
While that may seem like an extreme case, errors like this happen all the time online. For many users, missing a confirmation step or an undo option can turn a small mistake into a major problem. By giving users a chance to review and correct their inputs before submitting, websites not only improve accessibility but also create a smoother, more user-friendly experience for everyone.

## Who is affected?

People with reading disabilities. People with mobility impairments. People with cognitive disabilities.

People with reading disabilities, such as dyslexia, may struggle with typos and misreading form fields. If there’s no opportunity to review or fix errors, they could unintentionally submit inaccurate information.
People with mobility impairments, such as tremors, limited dexterity, or involuntary movements, may accidentally press the wrong keys, select incorrect options, or delete data by mistake. Providing an undo option or a confirmation step helps prevent irreversible errors.
People with cognitive disabilities, such as ADHD or memory impairments, may struggle with focus, remembering details, or following complex steps. They might click the wrong button or enter incorrect information. Error prevention mechanisms give them a chance to double-check their actions before finalizing important decisions.

## How to implement 3.3.4

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

Since this guideline applies to different situations, the best approach depends on the specific feature or function. Use the section below that best fits your use case, and implement at least one of the listed techniques.
### Transactions, Testing, or Submissions

This section applies to legal and financial transactions, tests, and form submissions, including:

Signing contracts and accepting terms and conditions
Submitting legal documents such as tax forms or court filings
Making purchases or entering payment details
Applying for jobs or government benefits
Registering for medical services
Entering personal data where errors could have legal or financial consequences

#### Give Users Time to Fix or Cancel

Allow users a set time to edit or cancel their submission after completing a form. This timeframe should be clearly communicated, and the steps to make corrections should be easy to access.
For example, after signing a contract, a message appears stating, "You have 10 minutes to edit or cancel this submission." The confirmation page shows a countdown timer and edit/cancel buttons.
#### Allow Users to Review and Make Corrections

Before submission, display a review page summarizing all user inputs. Users should be able to:

Edit directly on the review page, or
Navigate back to the original form section for updates

Include “Back” or “Previous” buttons to improve navigation between steps.
#### Include a Checkbox in Addition to Submit Button

To ensure users double-check their entries, add a required checkbox before the submit button. The label should clearly state that they are reviewing and approving their submission.
For example, if a user attempts to submit without checking the box, display a prompt reminding them to review their inputs.
#### Request Confirmation Before Submission

Before finalizing, show a confirmation popup to prevent accidental submissions. The message should clearly state that changes may not be possible after submission.
Illustrations of all the ways to prevent errors for legal and financial transactions, testing, or form submissions.
Within the image above:

 Time to Fix or Cancel: A timer is counting down, and a message says, “10 minutes to edit or cancel this submission.” Buttons to “Cancel Submission” and “Make a Fix” are shown.
 Review and Revise: A summary page titled “Review Before Submission” is shown where the field has the option to edit.
 Checkbox Confirm: A form where the user is shown a required checkbox labeled, “I confirm this info is correct.”
 Follow-Up Confirmation: A popup is displayed to the user after selecting “Submit”, where they’re asked, “Are you sure you want to submit?” and they have two options, “No, Cancel” or “Yes, Submit”.

### Deleting Information and Data

This section focuses on preventing accidental deletion of important data.
#### Allow Data Recovery

Enable users to restore deleted data through:

A temporary “Trash” folder that holds deleted items for a set time, such as 30 days
An edit history feature that allows restoring previous versions

For example, have a “deleted items” page where users can restore mistakenly deleted records.
#### Include a Checkbox for Deletion Confirmation

To prevent accidental deletions, add a required checkbox next to the delete button. The label should clearly state that this action is permanent.
If a user tries to delete without checking the box, display a warning message.
#### Request Confirmation Before Deleting

Before completing a deletion, display a confirmation popup with a clear warning that the action cannot be undone.
Illustrations of all the ways to prevent errors for deleting important data.
Within the image above:

Allow Data Recovery: A page dedicated to trashed items is shown where users can restore and recover items they deleted.
 Checkbox Confirm: After selecting the Trash button for an item in a list of files, a checkbox labeled “Confirm Delete” appears.
 Follow-Up Confirmation  : A popup is displayed to the user after selecting “Delete”, where they’re asked, “Are you sure you want to delete?” and they have two options, “No, Cancel” or “Yes, Delete”.

## Conclusion

Mistakes happen, but when they involve legal, financial, or critical data, a simple error can lead to frustration, lost opportunities, or even serious consequences. WCAG 3.3.4 ensures that users, especially those with disabilities, have the chance to review, confirm, or recover their actions before finalizing them.
By incorporating confirmation prompts, review steps, and undo options, websites don’t just improve accessibility. They create a smoother and more user-friendly experience for everyone. When people know they can safely complete important tasks without fear of making irreversible mistakes, they feel more confident and in control.

## Related Success Criteria

