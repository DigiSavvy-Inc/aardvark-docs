# 2.2.1 Timing Adjustable - AAArdvark

[Operable](https://aaardvarkaccessibility.com/wcag-principle/operable/)

[Enough Time](https://aaardvarkaccessibility.com/wcag-guideline/enough-time/)

WCAG 2.0, 2.1, 2.2
Level A

[View official documentation for WCAG 2.2.1](https://www.w3.org/WAI/WCAG22/Understanding/timing-adjustable.html)

# 2.2.1 Timing Adjustable

Time limits must be avoided unless they’re able to be extended.

[Forms](https://aaardvarkaccessibility.com/wcag-theme/forms/), [Sensory](https://aaardvarkaccessibility.com/wcag-theme/sensory/) 

 

[Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Visual](https://aaardvarkaccessibility.com/wcag-disability/visual/) 

 

[Code](https://aaardvarkaccessibility.com/wcag-responsibility/code/) 

## What is it?

Sometimes, content is time-sensitive—like text that’s only available for a short while, actions users need to take quickly, or things that move or change automatically over time.
That said, with any content that involves particular timing, we also need to consider that some users may need more time to interact or interpret a piece of content. By making the timing adjustable for that content, we can make it accessible to everyone.
Some examples of content that involves a timing variable include:

Forms that limit the time you have to fill out
Image or testimonial carousels
Error message popups, snack bars, and toasters
Moving text or news tickers
Time limits for inactivity

However, there are some exceptions to this criterion, specifically around content related to auctions or live-action events where the time limits are essential to uphold, and it would not be sensible to change them. This category of exceptions also includes other activities that necessitate a timer, such as qualification exams.

## Why does it matter?

People with disabilities often need more time to consume content or carry out functions, and setting time limits can make it difficult to understand or use a webpage.
Content that quickly times out can be frustrating to use, especially when the user is forced to start all over again or just misses out on it altogether. For example, think of an online quiz that has a timer tied to it; if the user can’t complete it in time, they will need to restart it. Or an online dashboard that times out after 15 minutes of inactivity.
Long form almost fully filled out showing a notification modal that the timer expired and the user needs to restart

## Who is affected?

People with low or limited vision. People with cognitive disabilities, reading, and learning disabilities. People with mobility issues or fine motor control issues. People who are deaf or communicate in sign language.

People with low or limited vision can have a hard time thoroughly reading and understanding content if they’re limited by time constraints. They may struggle to complete forms or view content when using assistive technology to process a web page since it can take longer for assistive technology to recognize layouts, find text, and process controls.
People with cognitive disabilities, reading, and learning disabilities will also find it challenging to process all the content on a page, given a time limit. They may find themselves running out of time because they take longer to comprehend the information.
People with mobility issues or fine motor control issues may have trouble keeping up with timed content. They may have a slower capacity to react, type, and complete actions on the page, making it more demanding to fill out forms or interact with content, especially if it’s auto-scrolling or moving on the page.
People who are deaf and communicate in sign language may need more time to read content translated to text format or to watch sign-language audio interpretations on the page.

## How to implement 2.2.1

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

Timing Adjustable success criteria can fall under a few different categories, so let’s break them down.
### Making Time Limits Accessible

#### Turn Off Session Time Limits

When session time limits are in place for a page or form, the most straightforward solution is to provide a way to turn off the timer. The mechanism itself must be near the top of the page and cannot have a time limit tied to it.
For example, a page auto-updates the set of 3 news articles shown every minute, and a toggle above the articles gives the user the ability to turn off the timer so they have enough time to read.
Section where three news articles are listed and a toggle to turn off the auto-update timer is enabled.
#### Adjust Time Limits

An alternate approach to removing the session limits altogether through a mechanism is to give users the option to extend the time limits to a specified range.
For example, a cart checkout may time out after 10 minutes to let other users claim the items. A visible timer at the top of the page includes a “Need more time?” button. Clicking it lets users choose to extend the timer to 20, 30, or 45 minutes using radio buttons.
Shopping cart checkout page displaying a timer with radio buttons to extend and save the timer duration.
#### Form Time Limits

Session timeouts applied to forms, especially multi-part forms, should include a checkbox to either request additional time (ex., 20 minutes) or disable the time limits altogether. This is super important in forms that will discard a user's progress if the session timer runs out.
### Notifying User of Time Limits

When time limits are used, a notification dialog is presented to warn users that the time limit is running out, along with options to reject extensions to the timer or increase the time limit.
Notification dialog warning the user the timer is expiring and to choose an option to continue.
### Moving or Scrolling Content

In cases where the content is moving or scrolling according to a timer, there needs to be a mechanism to pause and restart the content. The controls for pausing should conform to the WCAG 2.1.1 Keyboard standards and not conflict with WCAG 2.1.4 Character Key Shortcuts criteria. The controls for pausing and restarting moving content need to be documented clearly on the page.
This can apply to content such as news tickers, banners, animations, etc.
Section showing live news broadcast where a news ticker is scrolling through the headline. A ticker control section is visible with information on how to pause and restart.
#### Static Content Alternatives

As an alternative to providing a pause or restart mechanism for scrolling or moving content, you may provide all the content in static form in a separate area or window.
This approach should not be used if all the text can be displayed all at once on the current screen; in that case, the page should provide a mechanism to switch layouts on the same page.
### Time-Essential Content or Activities

As mentioned above, there are some exceptions to this criteria where the content or activity needs to be tied to a time constraint and doesn’t have to include alternatives. This is true for content related to:

Auctions and bidding forms
Live-action events (ex., Vote for today’s best singer by midnight.)
Qualification exams

However, it’s suggested that in these types of instances, the details of the time limits and any consequences when the timer expires are clearly stated. That way, a user can at least be prepared and know what will happen.
Or, offer alternatives outside of the webpage and leave notes on who to contact. For example, a university office may offer different testing approaches to online qualification exams so that users with disabilities can qualify in person without time constraints.

## Conclusion

In conclusion, timing plays a crucial role in online content, affecting how users interact with websites and complete tasks. While some content requires time limits for various reasons, it's vital to ensure accessibility by allowing adjustments for users who may need more time due to disabilities or other factors.
By implementing features like adjustable time limits, notifications, and pausing mechanisms, we can make online experiences more inclusive for everyone, making sure that no one is left behind due to restrictive timing constraints.

