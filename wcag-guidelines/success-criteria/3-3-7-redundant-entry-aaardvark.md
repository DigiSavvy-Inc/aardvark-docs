# 3.3.7 Redundant Entry - AAArdvark

[Understandable](https://aaardvarkaccessibility.com/wcag-principle/understandable/)

[Input Assistance](https://aaardvarkaccessibility.com/wcag-guideline/input-assistance/)

WCAG 2.2
Level A

[View official documentation for WCAG 3.3.7](https://www.w3.org/WAI/WCAG22/Understanding/redundant-entry.html)

# 3.3.7 Redundant Entry

Users must not be required to re-enter previously provided information unless necessary.

[Forms](https://aaardvarkaccessibility.com/wcag-theme/forms/) 

 

[Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Physical/Motor](https://aaardvarkaccessibility.com/wcag-disability/physical-motor/) 

 

[Code](https://aaardvarkaccessibility.com/wcag-responsibility/code/) 

## What is it?

A web form should not ask users to enter the same information more than once in a single session. This is especially important for multi-step forms and processes. For example, when completing a checkout form, users should not have to separately enter their billing and shipping information if they are the same.
The aim of this success criteria is to make the process easier by avoiding redundant data entry, which helps users feel less stressed and reduces the chance of mistakes.
Form where the user is asked to enter repeated information. One field says, “Enter your favorite color” and the other field says, “Enter your favorite color on Wednesdays”.

## Why does it matter?

Requiring users to remember and re-enter information can cause stress and mistakes, especially for people with cognitive disabilities. Everyone experiences mental fatigue while completing multi-step processes, and adding memory tasks makes the process even more difficult.
Nobody enjoys re-entering the same information over and over, and people with limited mobility can experience additional challenges with that task. Reducing the need for repeated entries makes the experience easier and smoother for everyone.

## Who is affected?

People with cognitive disabilities. People with limited mobility.

People with cognitive disabilities may struggle to remember information they’ve already entered, which can cause stress and mistakes.
People with limited mobility also benefit from fewer inputs, as it may be harder for them to enter information using assistive technology.

## How to implement 3.3.7

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

Most of the time, redundant inputs should be avoided, but there are some exceptions, such as:

Games where repeating inputs is part of the challenge, such as memory quizzes
Confirming passwords or email addresses for security or validation reasons
When previous entries expire and need to be updated

### Avoid Duplicate Input

The easiest way to implement 3.3.7 is to remove any fields that ask for the same information more than once. Check your form make sure every input is necessary, and get rid of any extra or duplicate fields.
### Populate Data From Previous Input

Instead of making users remember what they entered before, automatically fill in the new input with the previous data.
For fields that appear more than once, make sure there’s a way to populate them easily. This can be done in a number of ways:

Automatically filling the field and letting the user edit if needed
Providing a checkbox to let the user choose to fill the field with previous information
Asking the user to confirm if the previous information is still correct. If not, showing new input fields

Purchase Form where the user has the option to populate the billing address with the previously entered shipping address.

## Conclusion

By avoiding repeated data entry and helping users remember information from previous steps, we can reduce stress and mistakes. Using techniques to eliminate duplicate inputs and automatically fill in data can improve the usability and accessibility of web forms and processes.

## Related Success Criteria

