# 2.5.6 Concurrent Input Mechanisms - AAArdvark

[Operable](https://aaardvarkaccessibility.com/wcag-principle/operable/)

[Input Modalities](https://aaardvarkaccessibility.com/wcag-guideline/input-modalities/)

WCAG 2.1, 2.2
Level AAA

[View official documentation for WCAG 2.5.6](https://www.w3.org/WAI/WCAG22/Understanding/concurrent-input-mechanisms.html)

# 2.5.6 Concurrent Input Mechanisms

The user can happily switch between using a mouse, touchscreen, keyboard, or any other input device.

[Gestures](https://aaardvarkaccessibility.com/wcag-theme/gestures/), [Keyboard](https://aaardvarkaccessibility.com/wcag-theme/keyboard/) 

 

[Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Physical/Motor](https://aaardvarkaccessibility.com/wcag-disability/physical-motor/) 

 

[Code](https://aaardvarkaccessibility.com/wcag-responsibility/code/) 

## What is it?

Users should be able to interact with a website using any input method they choose, whether that's a mouse, keyboard, touch, speech, stylus, or any combination of those. If your site works with one input type, it must work with all of them and must not prevent users from switching between them.
Like all WCAG success criteria, this one applies to the web content—not the browser or operating system. It just means users should be able to switch input methods at any time while interacting with the content.
Users should be able to:

Start a task with a mouse and finish with a keyboard
Use touch, then switch to voice or stylus
Plug in a new input device mid-task and keep going
Choose whichever method works best for them at any time

Exceptions are allowed if:

A specific input method is essential to the task (e.g., a typing tutorial or a biometric login)
The user has explicitly chosen to limit their input methods (e.g., device settings that disable touch)
The restriction is required for security or legal compliance

## Why does it matter?

Most users already use more than one input method in daily life. For some, switching between input types is a preference. For others, it's a necessity.
When a website blocks input types, either intentionally or accidentally, it can break functionality for assistive technology users or anyone who depends on switching between inputs to complete a task. That creates frustration and unnecessary barriers.
Some examples:

A person with limited dexterity might use a keyboard for typing and touch for quick selections.
A user with a temporary injury might rely on speech input for part of the day and a mouse later on.
A screen reader user might switch between touch gestures and a Bluetooth keyboard on a mobile device.

## Who is affected?

People with motor disabilities. People using assistive technology. People with temporary injuries.

People with motor disabilities may rely on alternative input devices like switch controls, eye-tracking systems, or adaptive keyboards. They often switch between inputs depending on the task or physical comfort.
People using assistive technology in general can find that without proper support for various input methods, their tools don’t work as intended. Tools like voice input or screen readers often simulate keyboard or mouse actions. When a site limits interaction to only touch or mouse input, these technologies may fail, making it difficult or impossible for users to access the content.
People with temporary injuries, such as a broken arm or strained wrist, tend to switch input methods. For example, they can shift between voice commands and using a mouse. Supporting multiple inputs helps ensure they can still use the site while recovering.

## How to implement 2.5.6

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

### Test with Multiple Input Mechanisms

Try using your website in different ways and switching inputs mid-task. Make sure everything still works.
Here’s a simple checklist:

Keyboard: Use Tab, Shift+Tab, Enter, Space, and arrow keys to navigate and activate interactive elements. This overlaps with testing for WCAG 2.1.1 Keyboard.
Mouse: Click all buttons, links, menus, and controls.
Touchscreen: Test your site on phones and tablets. Make sure interactive elements are large enough and respond  to tap and drag gestures.
Stylus or pen: If supported, test tapping and dragging just like with a finger.
Voice input: Use speech-to-text tools, which operating systems often have built-in, to navigate and activate controls.
Switch mid-task: Try starting a task with one input (like a mouse), then switch to another (like keyboard or speech) to finish it.

Illustration showing five ways to activate a "Contact" button: using a stylus, a mouse, a keyboard (pressing the spacebar), a voice command ("Click Contact"), and tapping on a smartphone screen. This demonstrates support for multiple input methods.
### Use Input-Agnostic Event Handlers

When writing JavaScript, use event handlers that support multiple input types. Avoid restricting interaction to just one method.
Instead of only listening for:
element.addEventListener('mousedown', handleClick);

Use events that work across input types, like:
element.addEventListener('click', handleClick);

You can also enhance with:

focus / blur for keyboard support
keydown to catch keyboard actions like Enter or Space

### Support Simultaneous Input Methods

If needed, you can register multiple handlers for the same element to cover more use cases:
element.addEventListener('click', handleClick); // Mouse or touch
element.addEventListener('keydown', handleKeyPress); // Keyboard

Just make sure the logic behind each handler is accessible and doesn't depend on one input type working first.

## Conclusion

Let users interact with your site however they need to—keyboard, mouse, touch, voice, or assistive tech. Don’t force them to choose just one. Supporting multiple input mechanisms isn’t just about accessibility—it’s good design for real-world use. Unless a restriction is truly essential, flexibility should be the default.

## Related Success Criteria

