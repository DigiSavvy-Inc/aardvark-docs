# 2.1.2 No Keyboard Trap - AAArdvark

[Operable](https://aaardvarkaccessibility.com/wcag-principle/operable/)

[Keyboard Accessible](https://aaardvarkaccessibility.com/wcag-guideline/keyboard-accessible/)

WCAG 2.0, 2.1, 2.2
Level A

[View official documentation for WCAG 2.1.2](https://www.w3.org/WAI/WCAG22/Understanding/no-keyboard-trap.html)

# 2.1.2 No Keyboard Trap

There must not be a situation where you enter a modal with the keyboard and can’t get back to where you were.

[Keyboard](https://aaardvarkaccessibility.com/wcag-theme/keyboard/) 

 

[Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Physical/Motor](https://aaardvarkaccessibility.com/wcag-disability/physical-motor/), [Visual](https://aaardvarkaccessibility.com/wcag-disability/visual/) 

 

[Code](https://aaardvarkaccessibility.com/wcag-responsibility/code/) 

## What is it?

This success criterion makes sure that a user operating a keyboard or alternate keyboard doesn’t get stuck in a subset of the page's content. The result of “trapping” the user in the content is caused by the keyboard focus not being handled correctly.
Content that unintentionally traps the user is typically seen in plugins, widgets, or embedded applications on a web page. For example:

Modal popup boxes
Embedded booking calendar widgets
Content with infinite scrolling
Inaccessible video players

## Why does it matter?

It’s important to test that the keyboard alone can be used to navigate to all content on the page without getting stuck; otherwise, it’s impossible to navigate the whole page without using a mouse to get unstuck.
Once a user gets stuck, they’ll likely have to close or refresh the browser or restart their system, which you can imagine can be very frustrating and tedious, especially if the content is important or crucial for the user to access.
Giving users a way to move across all the content and “untrap” the focus allows keyboard users to freely review everything on a web page.

## Who is affected?

People with low or limited vision. People with limited hand mobility. People with fine motor control disabilities.

People with vision impairments, such as low or limited eyesight, require the use of a keyboard to navigate and operate web pages. When a subset of content traps the user’s keyboard focus, it makes it difficult to fully experience the content since they may miss out on information placed after the “trapping” application.
People with mobility disabilities may find it difficult or impossible to use a mouse. They may prefer to use a keyboard or alternate keyboard, which makes this applicable to them as well.

## How to implement 2.1.2

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

### Tab Start to Finish

The best way to test against this technique is to use the Tab key to go through the page content from start to finish. If you get stuck in any piece of the content, then the page needs to provide a keyboard-specific method, usually the Esc key, to exit or get unstuck and continue through the rest of the page.
Instructions on how to exit the content or move focus back to the next item on the page need to be readily available and presented to the user before the subset of problematic content.
User tabbing through different content on a web page, an embedded puzzle widget in the middle of the page shows a dead-end sign to signify a user will get trapped there.

## Conclusion

Keyboard accessibility is very important to users who cannot or prefer not to use a mouse. This makes it crucial that content does not interrupt the user's experience, in this case, trapping their focus and causing them to get stuck.

## Related Success Criteria

