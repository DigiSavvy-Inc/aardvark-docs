# 3.3.6 Error Prevention (All) - AAArdvark

[Understandable](https://aaardvarkaccessibility.com/wcag-principle/understandable/)

[Input Assistance](https://aaardvarkaccessibility.com/wcag-guideline/input-assistance/)

WCAG 2.0, 2.1, 2.2
Level AAA

[View official documentation for WCAG 3.3.6](https://www.w3.org/WAI/WCAG22/Understanding/error-prevention-all.html)

# 3.3.6 Error Prevention (All)

After entering any information, the user is offered the opportunity to check it before sending.

[Forms](https://aaardvarkaccessibility.com/wcag-theme/forms/), [Wording](https://aaardvarkaccessibility.com/wcag-theme/wording/) 

 

[Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Physical/Motor](https://aaardvarkaccessibility.com/wcag-disability/physical-motor/) 

 

[Code](https://aaardvarkaccessibility.com/wcag-responsibility/code/), [Design](https://aaardvarkaccessibility.com/wcag-responsibility/design/) 

## What is it?

When users submit any form—whether for signing up, buying something, or entering data—they should have a chance to confirm, correct, or undo their actions. At level AAA, all form submissions must include at least one of the following:

The submission can be reversed
The data is checked for errors, and users can correct them
Users can review and confirm the info before finalizing

This helps prevent mistakes that could be difficult—or even impossible—to fix later.

## Why does it matter?

Mistakes happen, but for people with disabilities, they’re often harder to catch and fix, especially when completing forms, entering data, or navigating websites. Without a way to review, confirm, or undo actions, users may face serious consequences they can’t easily reverse.
Picture someone with a cognitive disability trying to book a flight. They might accidentally enter their name incorrectly or miss a required step. If there's no chance to review or fix it, they may end up with the wrong ticket or not get one at all.
By giving users a second chance to review or undo actions, we help avoid errors, improve confidence, and make websites a lot more user-friendly for everyone.

## Who is affected?

People with reading disabilities. People with mobility impairments. People with cognitive disabilities.

People with reading disabilities, such as dyslexia, may struggle with typos and misreading form fields. If there’s no opportunity to review or fix errors, they could unintentionally submit inaccurate information.
People with mobility impairments, such as tremors, limited dexterity, or involuntary movements, may accidentally press the wrong keys, select incorrect options, or delete data by mistake. Providing an undo option or a confirmation step helps prevent irreversible errors.
People with cognitive disabilities, such as ADHD or memory impairments, may struggle with focus, remembering details, or following complex steps. They might click the wrong button or enter incorrect information. Error prevention mechanisms give them a chance to double-check their actions before finalizing form submissions.

## How to implement 3.3.6

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

### Error Prevention for Submissions

These techniques apply to all form submissions, including forms for:

Sign-up and Registration Forms
Login and Authentication Forms
E-commerce Forms
Subscription and Membership Forms
Contact and Inquiry Forms
Application Forms
Government or Legal Forms
Medical and Health-Related Forms
Booking and Reservation Forms

And many more! All of these forms require users to enter and submit information, which means mistakes are bound to happen. Therefore, it's important to have built-in error prevention features like review steps, confirmation prompts, or undo options.
#### Give Users Time to Fix or Cancel

One way to support reversability is to allow a brief window to edit or cancel a submission. This timeframe should be clearly communicated, and the steps to make corrections should be easy to access.
For example, after completing a purchase form, a message appears stating, "You have 10 minutes to edit or cancel your purchase." The confirmation page shows a countdown timer and edit/cancel buttons.
#### Allow Users to Review and Make Corrections

Before submission, display a review page summarizing all user inputs. Users should be able to:

Edit directly on the review page, or
Navigate back to the original form section for updates

Include “Back” or “Previous” buttons to improve navigation between steps.
#### Include a Checkbox in Addition to the Submit Button

In some cases, forms may include a required checkbox before the submit button to encourage users to review their entries more carefully. This can help prevent accidental submissions and give users a chance to pause and reflect before finalizing.
However, be mindful that this pattern can create unnecessary friction for some users, epecially those with cognitive or motor disabilities, if it becomes a barrier to submission. It should be clear, easy to use, and not the only mechanism in place for confirming form submissions.
If a user tries to submit without checking the box, a prompt can gently remind them to review their inputs. But this should be paired with other error prevention strategies, such as a review page or confirmation step, to ensure accessibility is preserved.
#### Request Confirmation Before Submission

Before finalizing, show a confirmation dialog to prevent accidental submissions. The message should clearly state that changes may not be possible after submission.
If you use a confirmation dialog, ensure that it's accessible. Focus should move to the dialog, it should be screen-reader friendly, and the method for closing the modal should be clear.
 
Illustrations of all the ways to prevent errors on form submissions.
Within the image above:

Time to Fix or Cancel: A timer is counting down, and a message says, “10 minutes to edit or cancel this submission.” Buttons to “Cancel Submission” and “Make a Fix” are shown.
Review and Revise: A summary page titled “Review Before Submission” is shown where the field has the option to edit.
Checkbox Confirm: A form where the user is shown a required checkbox labeled, “I confirm this info is correct.”
Follow-Up Confirmation: A popup is displayed to the user after selecting “Submit”, where they’re asked, “Are you sure you want to submit?” and they have two options, “No, Cancel” or “Yes, Submit”.

## Conclusion

WCAG 3.3.6 ensures that people have a chance to fix or review their submissions before it’s too late. This is especially important for people with disabilities, who may be more prone to making and missing errors. Whether it’s through confirmation steps, input validation, or simple undo buttons, giving people a safety net helps them feel confident and in control.

## Related Success Criteria

