# 2.5.4 Motion Actuation - AAArdvark

[Operable](https://aaardvarkaccessibility.com/wcag-principle/operable/)

[Input Modalities](https://aaardvarkaccessibility.com/wcag-guideline/input-modalities/)

WCAG 2.1, 2.2
Level A

[View official documentation for WCAG 2.5.4](https://www.w3.org/WAI/WCAG22/Understanding/motion-actuation.html)

# 2.5.4 Motion Actuation

There is no reliance on device motion, like shaking or tilting, to carry out an action.

[Gestures](https://aaardvarkaccessibility.com/wcag-theme/gestures/) 

 

[Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Physical/Motor](https://aaardvarkaccessibility.com/wcag-disability/physical-motor/), [Visual](https://aaardvarkaccessibility.com/wcag-disability/visual/) 

 

[Code](https://aaardvarkaccessibility.com/wcag-responsibility/code/) 

## What is it?

Motion actuation involves using device movements like shaking, tilting, or gesturing to control content on a webpage. While this can add dynamic aspects to a page or make interesting shortcut features, it can also limit accessibility for some users.
Some examples of motion-activated content include:

“Shake to undo” gestures
Photo or video controls that scroll based on mouse movement
Page navigation that relies on tilting to change pages

The goal of WCAG 2.5.4 is to ensure that all web content, including interactive functions, can be controlled without relying solely on these motions. However, exceptions exist for cases where motion is essential, such as in pedometer apps that count steps based on device movement.
Comparing a text editor interface that asks the user to “Shake to undo” versus one where the user has a button to Undo and Redo as well as a button to disable the motion actuation.

## Why does it matter?

Not everyone can perform the specific motions required to interact with content controlled by device sensors, such as shaking, tilting, or gesturing on a device. This reliance on motion controls can prevent users from accessing important content and functions, creating barriers and a frustrating user experience.
People with limited mobility may struggle with these actions due to conditions like paralysis or arthritis. At the same time, those with motor impairments, such as tremors from Parkinson's disease, might unintentionally trigger actions. Users of assistive devices like screen readers or switch controls often find these motion-based inputs incompatible with their technology, leading to frustration and difficulty in completing tasks.

## Who is affected?

People with limited mobility or motor impairments. People with low or limited vision. People who are blind.

People with limited mobility might not be able to shake, tilt, or perform gestures on their devices. And, if they can, it may be difficult to be precise in their movements or otherwise be painful for them to perform.
People with motor impairments, such as those caused by Parkinson’s disease or cerebral palsy, might unintentionally trigger actions due to tremors or other involuntary movements. These involuntary movements can make it difficult to perform precise motions required to control devices and their actions.
People with low vision or blindness might have difficulty aligning gestures accurately because they cannot clearly see the visual cues or feedback. These users might also find it challenging to orient the device correctly or understand the extent of motion needed for a specific action, leading to repeated unsuccessful attempts or unintended actions.
People who are blind rely entirely on non-visual interactions, such as screen readers or Braille displays, to navigate digital content. These assistive technologies typically don't support motion-based inputs like shaking, tilting, or gesturing. As a result, users of these devices might find it incredibly frustrating if a website or app relies solely on such inputs for critical functions.

## How to implement 2.5.4

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

To successfully meet this criterion, all the techniques and suggestions listed below must be implemented. Note that these need to be true for all types of devices, specifically tablets and smartphones, where gestures are more commonly used.
### Control Alternatives

When working with web pages that use device motions like tilting or shaking for input, make sure there are alternative methods to control the same content. Some commonly used alternatives include buttons and links to achieve the same functionality.
For example, a website can offer a feature called “Tilt Right To Go To Next Blog Post” for tablet and mobile users. The control alternative is a simple link that says “Next Blog Post” to navigate to the next post.
### Turn Off Motion Controls

Give users an option to turn off motion actuation altogether to avoid accidental triggers, especially for those with motor impairments. For example, if shaking a device undoes an action, also include a backspace key or a clear button and let users disable the shake-to-undo feature.
#### Support System Level Features to Disable Motion Actuation

Many devices have settings like "Turn off Shake to Undo" that let users disable motion-based interactions. Check that the webpage respects such settings and adjust your content accordingly.
For example, Apple offers built-in iOS settings to “Turn off Shake to Undo” on their iPhones and iPads. And Android offers settings such as Accessibility > Interaction and dexterity > Motions and gestures where users can disable features like Double tap, Motion gestures, or Lift to wake, depending on the device and Android version.
An image slider section that lets users tilt to go to the following image also allows users to turn off motion controls and use buttons to navigate between the images.

## Conclusion

Making sure web content and interactive functions do not rely solely on motion-based inputs is critical for accessibility. Offering alternative control methods, like keyboard inputs, and allowing users to disable motion controls ensures that everyone can interact with digital content effectively and comfortably.

## Related Success Criteria

