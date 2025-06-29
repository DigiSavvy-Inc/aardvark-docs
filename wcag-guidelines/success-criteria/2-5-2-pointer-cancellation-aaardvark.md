# 2.5.2 Pointer Cancellation - AAArdvark

[Operable](https://aaardvarkaccessibility.com/wcag-principle/operable/)

[Input Modalities](https://aaardvarkaccessibility.com/wcag-guideline/input-modalities/)

WCAG 2.1, 2.2
Level A

[View official documentation for WCAG 2.5.2](https://www.w3.org/WAI/WCAG22/Understanding/pointer-cancellation.html)

# 2.5.2 Pointer Cancellation

Actions (like pressing a button) aren’t triggered on mouse-down; rather on mouse-up.

[Gestures](https://aaardvarkaccessibility.com/wcag-theme/gestures/) 

 

[Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Physical/Motor](https://aaardvarkaccessibility.com/wcag-disability/physical-motor/), [Visual](https://aaardvarkaccessibility.com/wcag-disability/visual/) 

 

[Code](https://aaardvarkaccessibility.com/wcag-responsibility/code/) 

## What is it?

For any functionality that relies on single-pointer inputs, the trigger for execution must only activate after the user completes the “up-event” or make it easy for the user to undo or reverse their action. Single-pointer inputs include interactions such as single taps and clicks, double-taps and clicks, long presses, and path-based gestures.
All of these interactions have two code-related events in common. They begin with a “down event” and end with an “up event.” A down event is triggered when a finger is first pressed on a screen, or the mouse button is clicked down. The up event is triggered anytime the finger is lifted from the touch screen or the mouse button is released.
This success criterion aims to ensure that users can prevent unintentional touch or mouse inputs and easily cancel unintentional actions.
Illustration of a single pointer input that shows the two events side-by-side. On the left, you can see a hand pressing down on a button, which depicts the “down event.” On the right, another hand is shown lifting its finger off the button, depicting the “up-event.

## Why does it matter?

Accidental activation can lead to errors and frustration, especially for users with visual, mobility, or cognitive disabilities. Making activation occur on the release of a pointer (up-event) helps prevent unintended actions. This is crucial for users who might struggle with precise control, like those with motor impairments.
Giving users an easy way to undo or cancel actions can also help with the inputs that happen, even with the added preventative measures. Otherwise, users may find themselves in a situation where they’re not sure how to revert back, which causes frustration.
It also helps to make the resulting functionality give noticeable and visual feedback so that users can understand the result of their actions and be aware that they may need to undo or cancel whatever just happened. It can be confusing when users accidentally trigger a function without realizing it.

## Who is affected?

People with low or limited vision. People with limited mobility. People with cognitive disabilities.

People with low or limited vision might accidentally trigger actions by using a single pointer input on a page. For these users, it’s essential to make the activated functionality clear and provide an option to cancel and reverse their actions.
People with limited mobility may similarly trigger inputs unintentionally. Making it easy to undo or reverse the action can help prevent frustration.
People with cognitive disabilities may find it difficult to detect changes in context, become disoriented when functionality is unexpectedly triggered, and not know how to revert.

## How to implement 2.5.2

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

Any functionality operated using a single-pointer interaction must have at least one of the following behaviors to meet this success criterion.
However, please note that there are exceptions where triggering based on up-events or providing undo options would not make sense. If it’s essential for specific functionality to be immediately triggered via the down-event, this criterion can be skipped. Some examples of this are piano emulator apps or games where the user's first down-event input is inherent to the context. This exception also applies to typing letters or numbers on a keyboard.
### Activation or Completion on Up-Event

The simplest way to meet this success criterion is to stick to the default behavior of controls and avoid overriding it with an explicit down-event trigger. The up-event is typically the default for most controls in any programming or markup language. For example, this includes using the native onclick event in Javascript or using <button> elements in HTML.
For all clickable controls, check that the functionality is triggered only after releasing the touch from the screen or the mouse button. This also includes making sure that the action is not triggered if the user moves their mouse or finger outside of the targeted area.
Side-by-side illustrations where one side shows a hand actively pressing down on a button with their mouse. The other side shows the user actively pressing down and their cursor moved outside of the button. Both images depict the power of the activation on the up-event, where no functionality is triggered in both cases.
### Abort or Undo Options

If you provide ways to easily undo or abort the action, you can use the down event without failing the success criterion. Options to abort or undo can include confirmation dialogs or undo buttons.
Illustration of a contact form popup where the user accidentally clicks the close button, and it triggers a confirmation dialog box, ensuring that the user doesn’t accidentally lose their form entry progress.
### Reversal on Up-Event

Some functionality can be triggered with single-pointer interactions and instantly reversed with the final up-event, such as tooltips that pop up on down-events and then are hidden again on up-events. These types of actions perfectly meet this success criterion since activation does not cause any significant changes to the page and are quickly canceled as soon as they’re released.
#### Drag & Drop

For draggable content, check that the drag-and-drop action can be canceled or reversed after picking up an item. Users can do this by releasing the item outside a drop area, moving it back to its original position, or confirming the action through a dialog or undo command after dropping the item.
An example would be dragging an item on the page over to a trash can icon. If the user releases the item anywhere else on the page, it moves back to its original position.

## Conclusion

Implementing predictable pointer cancellation helps all users, particularly those with visual or cognitive disabilities, avoid accidental actions and recover quickly from mistakes. By focusing on up-event activations and providing clear options for aborting or undoing actions, developers can create more accessible and user-friendly interfaces.

## Related Success Criteria

