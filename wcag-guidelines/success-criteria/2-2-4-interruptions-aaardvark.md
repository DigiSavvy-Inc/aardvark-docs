# 2.2.4 Interruptions - AAArdvark

[Operable](https://aaardvarkaccessibility.com/wcag-principle/operable/)

[Enough Time](https://aaardvarkaccessibility.com/wcag-guideline/enough-time/)

WCAG 2.0, 2.1, 2.2
Level AAA

[View official documentation for WCAG 2.2.4](https://www.w3.org/WAI/WCAG22/Understanding/interruptions.html)

# 2.2.4 Interruptions

Pop-ups, notifications, and other interruptions can be switched off.

[Sensory](https://aaardvarkaccessibility.com/wcag-theme/sensory/) 

 

[Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Visual](https://aaardvarkaccessibility.com/wcag-disability/visual/) 

 

[Code](https://aaardvarkaccessibility.com/wcag-responsibility/code/), [Design](https://aaardvarkaccessibility.com/wcag-responsibility/design/) 

## What is it?

Websites must not interrupt users with sudden updates, like pop-ups, banners, or auto-refreshing content, unless it’s an emergency. Emergencies include alerts about threats to health, safety, property, or data.
This success criterion covers things like:

Non-urgent notifications or pop-up messages, like “You have a new message!”
Automatic page refreshes
Content updates that shift focus

For example, automatically jumping focus to a "new message" input field when a chat notification arrives can disorient screen reader users or cause people to lose their place.
Users with assistive technology or attention-related disabilities need a calm, predictable experience that allows them to stay focused. Ideally, these interruptions should be disabled by default, or users should be able to pause, postpone, or turn off these interruptions so they can stay focused on what they're doing.
A webpage showing an article titled “Chapter 3: What’s for Dinner?” is interrupted by multiple updates. A large modal in the center says, “Chapter Just Finished Loading. Refreshing Page Now…”, indicating an automatic refresh. In the bottom-left corner, a blue “New Message!” notification appears. A warning icon with an exclamation mark is also visible in the top-right corner, suggesting additional alerts. These interruptions overlap with the content and disrupt the reading experience.

## Why does it matter?

Interruptions can be disorienting for many users. A screen reader might be reading one thing, only to get hijacked by a pop-up update. Or someone with ADHD might lose their place entirely when a background task finishes and refreshes the page.
If users can’t postpone or turn off these interruptions, they can become confused or even abandon the task they were trying to complete.
A screen reader user is reading a heading and paragraph about aardvarks when a “New Message!” alert pops up on screen. Speech bubbles show the screen reader reading: “Heading level 2, Chapter 3: What’s for Dinner?”, “New Chat Message!”, and “Aardvarks have a pretty specific menu...”.

## Who is affected?

People with attention-related conditions, like ADHD. People who are blind. People who are low vision.

People with attention-related conditions, like ADHD, can get distracted or lose focus when unexpected updates pop up.
People who are blind rely on screen readers, so sudden changes can interrupt what they’re hearing and cause confusion.
People with low vision may be reading content slowly or zoomed in, so shifting updates can make it hard to keep their place.

## How to implement 2.2.4

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

### Let Users Control Notifications and Updates

Not all alerts are bad, but users should be able to control how and when they happen, especially if they shift the focus to another part of the page or refresh it. To meet this criterion:

Disable Updates by Default
Allow Users to Postpone Non-Essential Updates
Option to Voluntarily View Updates

Non-essential interrruptions are anything that can wait - updates that aren't urgent and don't relate to safety, security, or system failure.
#### Disable Non-Essential Updates by Default

This approach requires that non-essential notifications and updates be disabled by default. Users would then have the option to enable them on a settings page or modal.
A settings panel titled “Focus Settings” overlays an article. Toggles allow users to pause updates during a session, opt in to summary alerts, disable auto-refresh, and turn on non-essential alerts (off by default).
#### Allow Users to Postpone Non-Essential Updates

Use settings or toggles to let users pause or delay pop-ups, refreshes, and alerts. For example, a setting could allow users to choose how frequently the updates can be shown, such as only once a day.
A modal titled “Page Refresh Required” appears over an article. It explains that updates need a refresh to take effect, but gives two options: “Remind Me Later” and “Refresh Now,” with the ability to delay for up to 1 hour.
Or, if an update requires a page refresh, users should receive a warning with the option to delay it; this way, the interruption is controlled and doesn’t unexpectedly break their focus.
#### Option to Voluntarily View Updates

Instead of auto-refreshing or auto-updating, give users a button to request the update when they’re ready. For example, a page could offer a "Check for New Notifications" button.
Alternatively, offer users a dedicated updates page or area on the website where they can visit to get the newest notifications.
A small label in the corner of a webpage says “Checking…” with a refresh icon, while a button at the bottom right says “Check for updates. " This allows the user to manually trigger content updates instead of receiving them automatically.
### Exception for Emergency Updates

Emergency updates are the one case where interruptions are allowed. These include alerts about serious risks to health, safety, or property, like natural disasters, fire alarms, data loss, or connection timeouts. In these situations, it’s important to notify users right away, even if it means breaking focus.
For example, if a user’s session is about to expire or a file upload failed due to a lost connection, they should be alerted immediately so they can act before losing data or progress.
Use ARIA role="alert" and aria-live="assertive" for these status messages to make sure assistive technologies pick them up and announce them right away.

## Conclusion

No one likes to be interrupted, especially not by surprise updates while trying to finish a task. Giving users the ability to suppress non-essential interruptions helps everyone stay focused and makes the web more accessible, especially for folks using assistive tech or dealing with attention challenges.

## Related Success Criteria

