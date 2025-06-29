# 1.3.5 Identify Input Purpose - AAArdvark

[Perceivable](https://aaardvarkaccessibility.com/wcag-principle/perceivable/)

[Adaptable](https://aaardvarkaccessibility.com/wcag-guideline/adaptable/)

WCAG 2.1, 2.2
Level AA

[View official documentation for WCAG 1.3.5](https://www.w3.org/WAI/WCAG22/Understanding/identify-input-purpose.html)

# 1.3.5 Identify Input Purpose

The purpose of form fields can be identified by the browser, so that auto-complete suggestions can be offered in a dropdown.

[Forms](https://aaardvarkaccessibility.com/wcag-theme/forms/) 

 

[Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Visual](https://aaardvarkaccessibility.com/wcag-disability/visual/) 

 

[Code](https://aaardvarkaccessibility.com/wcag-responsibility/code/) 

## What is it?

Form fields should be programmatically identifiable so that assistive technology can communicate the purpose with users or so that auto-fill functionality can be used.
This means adding extra code to identify the purpose of specific fields. With that, assistive technology can easily swap field labels with easily recognizable icons. Or, auto-fill functionality can kick in and help users avoid entering basic information such as name, email, address, etc.
The goal is to make forms easier to fill out by reducing the need for manual typing and making it possible to simplify, especially for people who may struggle with remembering details, understanding labels, or who have limited mobility.

## Why does it matter?

When form fields aren’t programmatically identifiable, users with limited mobility or motor impairments have to do extra typing, which can be exhausting and physically demanding. Without clear coding to specify field purposes, assistive technology can’t auto-fill basic information, so users have to type everything manually—even standard details like name and email. This can make filling out forms slow, frustrating.
For users who struggle with memory or understanding labels, not having auto-fill or icon-based cues means they might not recognize what’s needed in each field, leading to confusion and mistakes.

## Who is affected?

People with limited mobility or motor impairments. People with cognitive disabilities.

People with limited mobility or motor impairments may find it difficult to type into form fields manually. Without basic auto-fill functionality, these users may find filling out a form tiring or even painful.
People with cognitive disabilities, including those with reading, learning, or memory impairments, may struggle to understand or remember what each form field asks for, especially if the labels are unclear or complex. Without identifying the input purpose, users can’t make swaps for helpful icon cues or use auto-fill, making filling out the form confusing and prone to errors.

## How to implement 1.3.5

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

### Autocomplete Attribute to Enable Auto-Fill

Use the autocomplete attribute to help define input purposes like "name", "tel", or "bday" to ensure that assistive technologies can interpret them correctly and to enable auto-fill functionality. Use the W3 Input Purposes reference for the autocomplete attribute values.
<label for="your-name">First Name:</label>
<input autocomplete="given-name" id="your-name" type="text">

 
<label for="your-email">Email Address:</label>
<input autocomplete="email" id="your-email" type="text">

 
<label for="your-birthday">Birthday:</label>
<input autocomplete="bday" id="your-birthday" type="text">

 
Autocomplete options appear on a form field to help the user fill out the form faster. The field asks for the user’s First Name, and a dropdown appears with their pre-saved First Name options.
### Clear Labels

In addition to using the autocomplete attribute wherever possible, make sure to use clear labels on input fields so their purpose is easy to understand. That way, even if icon cues can’t be used or auto-fill is not possible, the user has a better chance of understanding the purpose of the input.

## Conclusion

Making form input purposes clear and accessible helps everyone, especially people with cognitive and motor impairments. By defining these fields with autocomplete or clear labels, users can fill out forms faster, with less guesswork or manual entry, creating a smoother experience.

## Related Success Criteria

