# 2.1.3 Keyboard (No Exception) - AAArdvark

[Operable](https://aaardvarkaccessibility.com/wcag-principle/operable/)

[Keyboard Accessible](https://aaardvarkaccessibility.com/wcag-guideline/keyboard-accessible/)

WCAG 2.0, 2.1, 2.2
Level AAA

[View official documentation for WCAG 2.1.3](https://www.w3.org/WAI/WCAG22/Understanding/keyboard-no-exception.html)

# 2.1.3 Keyboard (No Exception)

You can navigate and interact with a page using the keyboard alone.

[Keyboard](https://aaardvarkaccessibility.com/wcag-theme/keyboard/) 

 

[Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Physical/Motor](https://aaardvarkaccessibility.com/wcag-disability/physical-motor/), [Visual](https://aaardvarkaccessibility.com/wcag-disability/visual/) 

 

[Content](https://aaardvarkaccessibility.com/wcag-responsibility/content/), [Design](https://aaardvarkaccessibility.com/wcag-responsibility/design/) 

## What is it?

Everything on a web page must be fully usable with just a keyboard. If someone can do it with a mouse, touch, or gesture, they must also be able to do it using the keyboard—with no exceptions.
This builds on WCAG 2.1.1 Keyboard, which allows some exceptions for complex interactions (like freehand drawing). But 2.1.3 (Level AAA) removes those exceptions—everything must work using keyboard input.
That means users should be able to:

Navigate to all content
Activate all buttons and links
Fill out and submit forms
Use controls like sliders or dropdowns
Play videos or interactive media

And they shouldn’t need to rely on complex key combos or precise timing to do so.
A hand presses the spacebar to activate an on-screen “Click Here!” button, showing that all functionality works without using a mouse.

## Why does it matter?

Not everyone can use a mouse. Some people rely on:

A regular keyboard
An on-screen keyboard
Speech input software
Sip-and-puff devices
Switch controls or other assistive tech

All of these tools simulate keyboard input—so if your website only works with a mouse or touch, many people won’t be able to use it at all. They could be blocked from reading content, filling out a form, pressing a button, or completing important tasks.

## Who is affected?

People with low or limited vision. People with limited hand mobility. People with fine motor control disabilities.

People with low vision may not be able to see or use a mouse pointer and instead navigate with the keyboard. People with limited motor control or tremors may find it difficult or impossible to use a mouse.
Unlike 2.1.1, this success criterion allows no exceptions—even for drawing, gestures, or other complex interactions. Everything must be operable by keyboard.
Some users may rely on custom keyboards or other devices that emulate keystrokes. If your site doesn’t fully support keyboard navigation, these users may be completely locked out.

## How to implement 2.1.3

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

### Make Everything Keyboard-Accessible

Start by testing every part of your site with the keyboard alone:

Use the Tab key to move forward through interactive elements
Use Shift + Tab to move backward
Use Enter or Space to activate links and buttons
Use arrow keys to navigate menus, sliders, or tabs

If you can’t reach or operate something with the keyboard, it needs to be fixed.
The easiest and most reliable way to ensure keyboard accessibility is to use semantic HTML elements whenever possible. Built-in elements like:

<a href="...">
<button>
<input>, <select>, <textarea>

…are all keyboard-friendly by default. They support focus, interaction, and screen reader support automatically—no extra coding required.
 
Illustration of web content where arrows point to headings, links, and buttons to demonstrate the tabbing order of elements as the hand presses the tab key on a keyboard.
### Use Scripting and ARIA for Custom Components

If you are building a custom interactive component and there is no possible option to use semantic HTML elements to do so, you’ll need to manually add keyboard support. In these cases, tabindex="0" allows elements that aren't normally focusable—like <div> or <span>—to receive keyboard focus.
<div tabindex="0">Custom widget that accepts keyboard focus</div>

But this should be a fallback, not your first choice.
If you create custom components, you’ll need to:

Manage keyboard focus with JavaScript
Support key events (like arrow keys, Enter, or Space)
Use ARIA roles and properties to describe behavior to assistive tech

Whenever possible, start with native HTML controls—they're far easier to make accessible and work more dependably for more users.

## Conclusion

Everything must work with the keyboard.
That’s the bottom line for 2.1.3—no mouse, no exceptions. If any part of your site relies on gestures, clicks, or drag-and-drop, you’ll need to provide an equivalent keyboard interaction.
Supporting full keyboard access doesn’t just help screen reader users—it benefits anyone who uses alternative input methods, has limited mobility, or just prefers the keyboard. It’s a key part of making the web usable for everyone.

## Related Success Criteria

