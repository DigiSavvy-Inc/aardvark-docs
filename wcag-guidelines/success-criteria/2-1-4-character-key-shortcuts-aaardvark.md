# 2.1.4 Character Key Shortcuts - AAArdvark

[Operable](https://aaardvarkaccessibility.com/wcag-principle/operable/)

[Keyboard Accessible](https://aaardvarkaccessibility.com/wcag-guideline/keyboard-accessible/)

WCAG 2.1, 2.2
Level A

[View official documentation for WCAG 2.1.4](https://www.w3.org/WAI/WCAG22/Understanding/character-key-shortcuts.html)

# 2.1.4 Character Key Shortcuts

Keyboard shortcuts must use modifier keys, like ctrl, command, or alt/option.

[Keyboard](https://aaardvarkaccessibility.com/wcag-theme/keyboard/) 

 

[Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Physical/Motor](https://aaardvarkaccessibility.com/wcag-disability/physical-motor/), [Visual](https://aaardvarkaccessibility.com/wcag-disability/visual/) 

 

[Code](https://aaardvarkaccessibility.com/wcag-responsibility/code/) 

## What is it?

As you test a web page's functionality and accessibility through keyboard navigation, you may encounter certain shortcuts that require single-character keys (for example, a-z keys, 1-9 keys, and punctuation keys). While these single-key shortcuts are convenient for keyboard-only users to navigate through the page, using standalone character keys for functions can cause issues for other users.
The goal of this success criterion is to allow all users control of single-character key shortcuts to help avoid accidental activation of those shortcuts.

## Why does it matter?

While it can be a convenience for some users to offer single-character key shortcuts, we need to keep all users in mind - some may use assistive technology or other methods of navigating through and between web pages.
For example, people who use their voice to navigate may unknowingly activate commands mapped to a letter, number, or punctuation key.
This gets even more problematic when multiple-character key shortcuts are in use at once—a speech user saying a voice command can accidentally trigger several commands in a row without even realizing it.
A puzzle game where commands are mapped to single-character keys. A user types "A", which conflicts with another user who is speaking a command.

## Who is affected?

People with low or limited vision. People with mobility disabilities and RSI (Repetitive Stress Injuries). People with fine motor control disabilities. People with cognitive disabilities.

People with a wide variety of disabilities, including vision impairment, mobility challenges, or repetitive stress injuries, may choose to use speech to navigate and operate web pages. All of these users may be impacted by single-key shortcuts that inadvertently fire while the computer is executing voice commands.
Additionally, people with fine motor control disabilities are prone to accidentally clicking on keys and may find it difficult to avoid causing unexpected functionality through single-key commands.
Lastly, since one way to implement this success criterion is to offer the ability to remap all shortcut keys, people with cognitive disabilities can benefit since they can assign similar actions to take place across different websites and applications.

## How to implement 2.1.4

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

As mentioned above, there are a few ways to meet this criterion. As you review a page and navigate through it with a keyboard, take note of each command that uses a single character key, such as:

A - Z keys
1 - 9 keys
Punctuation keys, ex. “semi-colon”, “exclamation point”, “question mark”, “comma”, etc.

If a webpage makes use of these single-key commands, then one or more of the following options must be implemented:
### Toggle Off and On

Web pages should let users turn off individual single-key commands or all of them altogether. This mechanism for disabling character-key shortcuts must be accessible.
### Remap Shortcuts

If you feel that your shortcuts are necessary for using the web page, for example, if the keys are used for special functionality in a web app such as a puzzle game, calendar widget, etc. In that case, a menu option where users can remap the shortcut keys can be used to give users the flexibility to remap the functionality to other keys that they find more familiar or less bothersome.
### Shortcut Only Active When Focused On Specific Element

Another option is to enable the shortcut only when certain elements are in focus on the page. For example, if a shortcut is tied to only the “Q” key, then it might only be active when a specific heading is focused on a page.
### Additional Key Dependency

Lastly, to help avoid chaos with single-character key shortcuts, you can also opt to add an additional key to the shortcut. Since the functionality depends on initiating an extra element, this can help reduce accidental firings of the shortcut.
For example, instead of firing an action by using “D,” you can swap the single-key trigger for a double-key trigger of “Ctrl” + “D.”
If you decide to go with this approach, you’ll also need to avoid common key commands or “sacred” keybindings to prevent conflicts. For example, “Ctrl” + “A” should be avoided since this typically allows a user to select all text.
A Tic-Tac-Toe module is being played; default single-character key command instructions are shown next to accessibility options that allow you to disable all single-character key commands or remap the commands.

## Conclusion

With all that said, WCAG 2.1.4 makes sure that while we’re making our pages accessible for keyboard-only users, we also consider other users, specifically those who use speech to navigate or those with cognitive and fine motor disabilities. By giving users the ability to toggle or remap character keys or disable them altogether, we can make web pages more inclusive for a variety of people with different navigational preferences.

## Related Success Criteria

