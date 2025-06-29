# 2.5.7 Dragging Movements - AAArdvark

[Operable](https://aaardvarkaccessibility.com/wcag-principle/operable/)

[Input Modalities](https://aaardvarkaccessibility.com/wcag-guideline/input-modalities/)

WCAG 2.2
Level AA

[View official documentation for WCAG 2.5.7](https://www.w3.org/WAI/WCAG22/Understanding/dragging-movements.html)

# 2.5.7 Dragging Movements

Any action requiring dragging, such as reordering items, must also be possible using buttons or other non-drag methods.

[Gestures](https://aaardvarkaccessibility.com/wcag-theme/gestures/) 

 

[Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Physical/Motor](https://aaardvarkaccessibility.com/wcag-disability/physical-motor/) 

 

[Code](https://aaardvarkaccessibility.com/wcag-responsibility/code/) 

## What is it?

If a task on your website requires dragging, there must be an easier alternative provided. Instead of dragging, users should be able to complete the same action with a single tap, click, or other simple input. Dragging motions are typically found in things like sliders, color pickers, sortable lists, Kanban boards (where you drag and drop tasks), and interactive maps.
While this sounds a lot like WCAG 2.5.1 Pointer Gestures, they aren’t the same: with dragging, only the start and end points matter, but gestures usually mean the user has to follow a path with their mouse or finger.
Similarly, the WCAG 2.1.1 Keyboard success criteria require that dragging movements be keyboard accessible. However, that’s not enough to meet this one. Dragging must also work with a single tap or click for users who don’t use keyboards.
Illustration comparing path-based gestures on the left, such as dragging and dropping, and multipoint gestures on the right, such as pinching to zoom.

## Why does it matter?

Without single-pointer options for dragging, some users might not be able to use certain parts of a website. People with mobility issues might find dragging difficult or tiring, like when panning across a map or dragging items in a website builder.
People who use assistive tools like trackballs or eye-gaze systems might not be able to make dragging motions at all. Simple features like sliders for volume control can be completely inaccessible.

## Who is affected?

People with mobility and fine motor control impairments.

People with mobility or fine motor control issues might find dragging motions difficult or painful. A single tap or click option can avoid extra effort.
People using different types of input devices might not be able to make dragging motions with their devices. Simple inputs work best to make sure they can do the same tasks.

## How to implement 2.5.7

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

### Single Pointer Alternatives

For any component, element, or interface that needs dragging, make sure there’s an easy single-pointer option as an alternative.
Single-pointer options can include clicking a button or typing in a value. For example:

For a volume slider, allow users to type a number value into an input or click simple +/- buttons to adjust the volume
For sortable lists, allow users to reorder items with up/down buttons
For interactive maps, allow users to pan using directional buttons

Remember, while offering keyboard shortcuts as alternatives to dragging is great and necessary for other success criteria, it’s not sufficient to meet this success criterion. You need to provide a single-click/tap alternative or a simple input.
A map with two ways to navigate the view. Users can either drag the map to reposition it or use arrow buttons to move in any of the four directions with a simple tap.

## Conclusion

Adding single-pointer alternatives for dragging makes sure everyone can use your interface, including people with mobility issues or those using assistive devices. Simple options like buttons, text fields, or single-tap solutions make your components easy to use for all users.

## Related Success Criteria

