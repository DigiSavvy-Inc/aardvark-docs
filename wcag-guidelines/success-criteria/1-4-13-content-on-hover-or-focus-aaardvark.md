# 1.4.13 Content on Hover or Focus - AAArdvark

[Perceivable](https://aaardvarkaccessibility.com/wcag-principle/perceivable/)

[Distinguishable](https://aaardvarkaccessibility.com/wcag-guideline/distinguishable/)

WCAG 2.0, 2.1, 2.2
Level AA

[View official documentation for WCAG 1.4.13](https://www.w3.org/WAI/WCAG22/Understanding/content-on-hover-or-focus.html)

# 1.4.13 Content on Hover or Focus

Tooltips and similar content should stay visible, be easy to dismiss (usually with the Esc key), and let users select and interact with the text.

[Gestures](https://aaardvarkaccessibility.com/wcag-theme/gestures/), [Keyboard](https://aaardvarkaccessibility.com/wcag-theme/keyboard/), [Zoom and Legibility](https://aaardvarkaccessibility.com/wcag-theme/zoom-and-legibility/) 

 

[Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Visual](https://aaardvarkaccessibility.com/wcag-disability/visual/) 

 

[Code](https://aaardvarkaccessibility.com/wcag-responsibility/code/), [Design](https://aaardvarkaccessibility.com/wcag-responsibility/design/) 

## What is it?

When content appears on hover or focus, users should be able to:

Dismiss it
Interact with it without it disappearing
Have enough time to read or engage with it

This applies to hover or keyboard focus-triggered content such as tooltips, sub-menus, or popups. It ensures that these elements are dismissible, hoverable, and persistent and don’t interfere with a user’s reading experience or cause them to miss content.
An illustration shows three common types of content triggered by hover or focus: a tooltip explaining a button, a sub-menu that appears from a top navigation bar, and a modal-style popup.

## Why does it matter?

When content isn’t dismissible, hoverable, or persistent, it can create significant frustrations for users or make pages unusable. If users can’t dismiss extra content, it might block key parts of the page, making it impossible to interact with the original content. For example, a tooltip or popup that can’t be closed can completely hide important information or buttons.
When hoverable content disappears the moment the pointer moves away, users might never get the chance to read or interact with it fully. This is challenging for people who need more time to process the content or who rely on screen magnification, where moving the pointer might require panning across a zoomed-in screen.
If content isn’t persistent and vanishes too quickly, it can leave users confused or frustrated, especially those with cognitive or motor impairments. They might not even realize what happened or have the time to engage with the content.

## Who is affected?

People with low or limited vision. People with motor impairments. And people with cognitive disabilities.

People with low or limited vision may need more time to read or dismiss content or may find it challenging to keep the pointer in the right spot on a zoomed-in screen.
People with motor impairments can find it difficult to maintain precise pointer movements to keep content visible for long enough to read or interact with it.
People with cognitive disabilities may find it hard to understand unpredictable content. They may not know what’s causing the content to show up or know that they need to read it quickly.

## How to implement 1.4.13

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

### Make Content on Focus or Hover Hoverable, Dismissible, and Persistent

Check that any content that appears on keyboard focus or hover actions can be dismissed, doesn’t suddenly disappear, and the user has enough time to read or engage with it.
#### Hover-Triggered Action

All content triggered by hover must meet three requirements. Here's what that means:

Hoverable: The pointer can be moved over the additional content without disappearing
Persistent: The additional content stays visible and doesn’t automatically close
Dismissible: The content can be closed by pressing the Esc key, pressing another shortcut, or activating the same trigger that opened it

#### Keyboard Focus-Triggered Action

All content triggered by focus must meet two requirements. Here's what that means:

Persistent: The additional content stays visible and doesn’t automatically close
Dismissible: The content can be closed by pressing the Esc key, pressing another shortcut, or moving the focus away

Illustration of a tooltip being hoverable, dismissible, and persistent. A side-by-side illustration of all these requirements is shown.
### ARIA role=”tooltip”

Use ARIA attributes like role="tooltip". This attribute signals to assistive technology, such as screen readers, that the associated content is a tooltip and makes it clear that it provides added information about a particular element.
When combined with aria-describedby attribute, you can link the tooltip to the trigger so that screen readers can announce the tooltip content when the trigger gains focus.
### CSS pseudo-classes

Using CSS pseudo-classes like :hover and :focus allows you to control how elements behave and look when a user interacts with them.

:hover Applies styles when a user hovers their pointer (mouse or trackpad) over an element.
:focus Applies styles when an element receives keyboard focus, such as when a user tabs to a button or input field.

These pseudo-classes help style interactive states, but they don’t control behavior like dismissing content. Use JavaScript or ARIA attributes for those interactions.

## Conclusion

Hover and focus-triggered content can be helpful—if it’s thoughtfully designed. By making it dismissible, hoverable, and persistent, you create a smoother, more inclusive experience for everyone.

## Related Success Criteria

