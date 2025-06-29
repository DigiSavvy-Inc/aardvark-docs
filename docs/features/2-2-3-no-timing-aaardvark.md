# 2.2.3 No Timing - AAArdvark

[Operable](https://aaardvarkaccessibility.com/wcag-principle/operable/)

[Enough Time](https://aaardvarkaccessibility.com/wcag-guideline/enough-time/)

WCAG 2.0, 2.1, 2.2
Level AAA

[View official documentation for WCAG 2.2.3](https://www.w3.org/WAI/WCAG22/Understanding/no-timing.html)

# 2.2.3 No Timing

Unless it’s a live broadcast or something else that’s happening in real time, there are no time constraints placed on the user.

[Forms](https://aaardvarkaccessibility.com/wcag-theme/forms/), [Sensory](https://aaardvarkaccessibility.com/wcag-theme/sensory/) 

 

[Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Visual](https://aaardvarkaccessibility.com/wcag-disability/visual/) 

 

[Code](https://aaardvarkaccessibility.com/wcag-responsibility/code/) 

## What is it?

Time limits must not be applied to website content and activities. This success criterion focuses on giving users as much time as they need to complete tasks and access information without any pressure from a ticking clock.
Timing constraints become a barrier for users who need more time to read, navigate, or interact with digital content. While WCAG 2.2.1 Timing Adjustable gives users the option to add more time, this criterion takes it a step further to promote web content that avoids timing altogether.
However, due to the nature of some content, there are a few exceptions:

Non-interactive video or audio content like livestreams, movies, podcasts, etc.
Live events and functionality like voting deadlines or auctions

## Why does it matter?

Not everyone experiences or interacts with digital content at the same pace. People with disabilities often need more time to process content, and when time limits are imposed, it can lead to unnecessary frustration, mistakes, or complete exclusion.
When content is tied to a timer, users may feel rushed or anxious. They might miss key information, submit incomplete forms, or get logged out before finishing a task.
Even worse, if there's no way to pause, extend, or remove the time limit, the user may have to start over entirely—creating a barrier that has nothing to do with ability or intent, and everything to do with racing against a clock they can’t control.
A partially completed multi-step form stuck at Step 7: “Fill Out Your Address.” A large pop-up message reads “Uh-Oh! Time is Up. Sorry, the form timed out. Please restart and try again,” with a blue “Restart” button below. This illustrates a failure to meet WCAG 2.2.3 No Timing, showing how progress can be lost when users are forced to complete tasks within strict time limits.

## Who is affected?

People with physical or motor impairments. People who are blind. People with low vision. People with cognitive disabilities. People who are d/Deaf.

People with physical or motor impairments may need more time to move a mouse, tap a screen, or type responses, especially if they use assistive devices.
People who are blind often navigate using screen readers, which can take longer to interpret layouts, identify elements, and read through content.
People with low vision may need extra time to locate information on the page, zoom in, adjust settings, or use screen magnifiers effectively.
People with cognitive disabilities may take longer to process instructions, understand content, or make decisions, especially when dealing with complex layouts or unfamiliar tasks.
People who are d/Deaf may take longer to read written content if it's not their primary language, mainly if they communicate primarily in sign language.

## How to implement 2.2.3

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

### Avoid Timers and Time-Based Restrictions

The simplest way to meet this criterion is to design without timers altogether. That also means avoiding situations where speed impacts the user experience, like grading users based on how quickly they finish a task.
If your content or features are not time-sensitive, let users take as long as they need.
Content, activities, and features that must follow this rule:

Forms and applications, especially multi-step forms
Checkout and shopping carts
Games that penalize slow responses
Auto-rotating carousels and testimonial sliders
News tickers and announcements banners
Popups that disappear automatically
Authentication sessions
Online courses and modules

Two job application forms side by side. The left version shows “08:34 Minutes Remaining!” and warns users they must reapply next year if they don’t finish in time, marked with a thumbs-down icon. The right version says “Please Take Your Time,” encouraging users to complete the application at their own pace, marked with a thumbs-up icon.
#### Use Turn-based or Paused Interactions

If you're building an interactive experience like a game or quiz, consider using turn-based mechanics or allowing users to pause. That way, the experience can still be engaging without requiring quick reactions or a timer.
#### Avoid Session Timeouts

If users are filling out a form, writing a message, or working through a multi-step process, avoid session timeouts. Or at the very least, ensure that progress is saved and can be resumed later.
This situation is also covered in WCAG 2.2.6 Timeouts. While 2.2.6 ensures users are warned before a timeout that may cause data loss, 2.2.3 takes it further, requiring you to avoid time limits entirely whenever possible.
A shopping cart checkout session for an accessibility dog harness. The user is in the middle of entering credit card details when a message appears: “00:00 Minutes Remaining — Your cart has expired. All items have been removed.” This demonstrates a failure of WCAG 2.2.3, where time limits disrupt task completion without alternatives.
### Exceptions for Time-Based Content

While WCAG 2.2.3 enforces removing time limits, some content can’t exist without them. In those cases, the goal is to focus on clear communication and accessible alternatives.
If real-time participation isn’t possible, offering follow-up content like event recaps, post-auction summaries, or a results page helps keep the experience inclusive.
#### For Non-Interactive Media like livestreams, movies, or podcasts

Provide transcripts for audio or video-only content
Offer captions and audio descriptions where applicable
If a recording will be available later, clearly state when and where users can access it

#### For Real-Time Events like live voting or auctions:

Clearly display the start and end times in a readable format
Include reminders or countdowns with sufficient contrast and screen reader support
Where possible, offer alternative participation options, like email submissions or extended voting windows for users who need accommodations.

A live auction screen showing a person announcing bids for a refreshable braille display. Text bubbles read “Current bid is $850” and “$900, Anyone?!”. A laptop with a braille display is shown on the right. A countdown timer shows 12:58 minutes left. This illustrates a real-time event that is an exception under WCAG 2.2.3, where time-based interaction is essential.

## Conclusion

The core idea behind WCAG 2.2.3 is simple: don’t impose a timer on any content. Removing time-based restrictions creates a more inclusive and less stressful experience for everyone, especially those who need more time to interact with your content.

## Related Success Criteria

