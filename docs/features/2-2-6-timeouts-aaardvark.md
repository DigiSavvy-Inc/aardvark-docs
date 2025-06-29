# 2.2.6 Timeouts - AAArdvark

[Operable](https://aaardvarkaccessibility.com/wcag-principle/operable/)

[Enough Time](https://aaardvarkaccessibility.com/wcag-guideline/enough-time/)

WCAG 2.1, 2.2
Level AAA

[View official documentation for WCAG 2.2.6](https://www.w3.org/WAI/WCAG22/Understanding/timeouts.html)

# 2.2.6 Timeouts

A warning is shown if a logged-in session is about to expire.

[Forms](https://aaardvarkaccessibility.com/wcag-theme/forms/) 

 

[Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Visual](https://aaardvarkaccessibility.com/wcag-disability/visual/) 

 

[Code](https://aaardvarkaccessibility.com/wcag-responsibility/code/) 

## What is it?

If a site uses an inactivity timeout that might cause users to lose work, it must let users know how long they can be inactive before that happens. That way, users can plan their time, take breaks, and come back without being blindsided.
Some websites or web apps automatically log users out or wipe data after a period of inactivity, which might be for security, privacy, or server performance reasons. Familiar places you’ll see inactivity timeouts:

Job or school applications
Long multi-page forms
Online shopping carts or checkouts
Financial or medical tools
Account dashboards and portals

The goal of this success criterion is to make sure people are aware of timeouts and their exact length to help avoid data loss.
### Timing Adjustable vs. Timouts

WCAG 2.2.1 Timing Adjustable is about giving users control over active time limits, like when a page auto-refreshes or a form has a countdown. Users should be able to turn off, extend, or adjust those timers unless the timing is essential.
On the other hand, WCAG 2.2.6 Timeouts aims to warn users when inactivity could cause data loss. If someone walks away and their session will expire, they need to know how long they have, unless the system keeps their data for at least 20 hours.
This 20-hour window is based on the assumption that the user might return to a task later the same day or the next morning, and should be able to do so without starting over.

## Why does it matter?

Some users need more time to complete tasks, and if their work disappears because they took a break or got distracted, it can be very frustrating and discouraging.
Imagine filling out a detailed form, stepping away for lunch, and coming back to find your session expired with all of the info gone missing. Now imagine you’re someone who processes information slowly, or who needs extra time due to memory, focus, or motor limitations. Losing your progress makes the whole task harder or even impossible to finish.
By giving users a simple heads-up about the timeout, you can let them decide whether to continue now or come back when they’re ready.
A person with a cane and a guide dog walks away from a laptop, thinking about getting coffee. On the laptop screen, a large “TIMEOUT!” warning appears, indicating that their session has expired while they were away.

## Who is affected?

People with memory-related conditions. People with language processing disorders.

People with memory-related conditions may forget where they left off or need extra time to review instructions and double-check their input. Unexpected timeouts can make it harder to complete tasks and force them to start over.
People with language processing disorders might need more time to read, comprehend, and respond to content. A timeout that cuts them off mid-task can interrupt their flow and make it difficult to complete complex forms or multi-step processes.
A multi-step form shows progress through step 7, labeled “Fill Out Your Address.” A modal appears with a sad face icon and the message: “Uh-oh! Session Timed Out. Sorry, the form timed out. Please restart and try again.” The message implies the user’s entered data has been lost due to the timeout.

## How to implement 2.2.6

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

### Preserve Sessions or Data for 20+ Hours

One way to meet this criterion is by ensuring users don’t lose access or progress for at least 20 hours of inactivity. This can be done in two ways:

Store their data so they can return later and pick up where they left off
Extend the session timeout to 20+ hours so the page doesn’t expire too soon

If storing data isn’t possible, setting a session timeout to 20+ hours achieves the same outcome. Users won’t be logged out or lose information, and you won’t need to show a timeout warning.
When you store sensitive data, especially if the user hasn't logged in yet, just be mindful of privacy rules like HIPAA. If they are logged in, make sure to also check out WCAG 2.2.5 Re-authenticating for more guidance on saving data when a login process is involved.
### Notify Users of Timeouts

If you can’t store the data for at least 20 hours and need shorter timeouts, tell users up front how long they have before experiencing a timeout. To avoid interrupting users mid-task, display the timeout warning at the start, before they begin entering information.
Here’s what a reasonable notice might look like:
“For security reasons, your session will expire after 30 minutes of inactivity. Make sure to save your progress.”
A shopping cart page displays a dog harness in the cart. An initial pop-up message warns: “Your session has a time limit. Items will be removed from your cart after 30 minutes.” A button below says “Confirm & Checkout.”
### Don’t Use Timeouts at All

If possible, just don’t implement an inactivity timeout. Many simple forms and interactions don’t need one. If nothing happens when a user sits idle for an hour, there’s nothing to warn them about, and they can step away or take breaks freely.
If there's no risk of losing user data, this success criterion doesn't apply.

## Conclusion

Inactivity timeouts are common, but without clear communication, they can create serious issues, especially for users who need more time. If users might lose work due to inactivity, they need to know how long they have. Whether you extend the timeout to 20+ hours or provide a clear notice at the start of a task, the goal is to prevent surprise data loss and give people the chance to complete tasks at their own pace.

## Related Success Criteria

