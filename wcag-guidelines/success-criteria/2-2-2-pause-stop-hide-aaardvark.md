# 2.2.2 Pause, Stop, Hide - AAArdvark

[Operable](https://aaardvarkaccessibility.com/wcag-principle/operable/)

[Enough Time](https://aaardvarkaccessibility.com/wcag-guideline/enough-time/)

WCAG 2.0, 2.1, 2.2
Level A

[View official documentation for WCAG 2.2.2](https://www.w3.org/WAI/WCAG22/Understanding/pause-stop-hide.html)

# 2.2.2 Pause, Stop, Hide

Automatically moving/animating content that lasts more than 5 seconds must be able to be stopped or hidden.

[Sensory](https://aaardvarkaccessibility.com/wcag-theme/sensory/) 

 

[Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Visual](https://aaardvarkaccessibility.com/wcag-disability/visual/) 

 

[Code](https://aaardvarkaccessibility.com/wcag-responsibility/code/), [Content](https://aaardvarkaccessibility.com/wcag-responsibility/content/), [Design](https://aaardvarkaccessibility.com/wcag-responsibility/design/) 

## What is it?

WCAG 2.2.2 focuses on emphasizing the importance of not distracting users when they are interacting with websites. Distractions include moving, blinking, or scrolling elements that start automatically and move, blink, or scroll for more than five seconds on the page. This also includes content that updates automatically on the page without warning.
Elements that automatically update or move about the page require some kind of control to pause, stop, or hide the element. Otherwise, this could be a problem for anyone with trouble reading or interacting quickly with moving objects. Elements that update automatically can also cause problems for screen reader users.

## Why does it matter?

Providing the ability to pause, stop, or hide moving and updating elements allows users with vision or mobility problems the chance to interact with the content on the page at their own pace. If elements are constantly moving around the screen, blinking into or out of existence, or scrolling for more than five seconds, it can be dizzying and overwhelming for anyone, but users with vestibular disorders or seizure disorders can be affected severely. Additionally, users with vision impairment or those with reading and learning disabilities may struggle to read content in that timeframe, and those with mobility challenges may not be able to get to it in time.
On top of that, if the information is constantly updated on the page, for example, a news ticker, this can be disorienting and difficult for screen reader users who are constantly interrupted while browsing the page with announcements of the updates.
Let’s take a look at an example where we are presented with a carousel of items on sale.

This is already quite annoying for everyone as the user is forced to wait to see the item they wanted to show up again and then must race to click it in time. However, this is decidedly problematic for users with vision, reading, or mobility problems. There’s no way to stop it from moving, and it doesn’t give the user a chance to add that coveted item to their shopping cart.
Such a situation can be easily rectified by ensuring that there is a way to pause the carousel altogether and even include a way to access the previous and next items so that they have a chance to make a purchase.

WCAG 2.2.2 seeks to ensure that users with visual, reading, and mobility impairments will be able to absorb content and identify elements without difficulty. And so that users with vestibular and seizure disorders aren’t triggered into a seizure or dizzy spell due to moving content. This guideline seeks to ensure that all users are able to access and control the content.

## Who is affected?

People with low or limited vision, people with cognitive disabilities, reading and learning disabilities, people with mobility issues or fine motor control issues, and people with vestibular and seizure disorders.

Animated, moving, or updating elements that display simultaneously with the site’s content can dramatically make or break a user’s experience on the site, especially if they have vision impairments, cognitive disabilities, or mobility issues. Vision impairments make it difficult to see and understand details, and if the content is moving, this makes it even more troublesome. Screen magnifiers may not help in this case as content could be constantly moving out of the visible range for someone zoomed in, leading to even more annoyance. Those with cognitive, reading, and learning disabilities also need more time to take in the information - as well as those with mobility issues. If the interactive element is jumping everywhere or already gone, you’ll only have frustrated users as a result.
For example, web advertisements that cover part of the content and don’t have any controls to pause or close them would hinder their overall site engagement. Or, a weather radar that offers no way to pause it would make it difficult for users to absorb the knowledge.
Users with seizure and vestibular disorders may also be triggered by moving content that they can’t control. There is a high chance the moving content can incite a seizure, which is downright terrible. Moving content can even instigate a dizzy spell where they will feel the urge to vomit, faint, fall over, or develop a migraine.
Take, for example, a news carousel that flips by without warning. The below image references a bad case where there are no controls; this would be difficult to read and control as it keeps scrolling to the next article in line.

Elements that move, blink, or scroll across the page need to offer some kind of control so that users are able to interact with and understand the content on the page. If users are not given the correct tools to control them, then this will lead to all sorts of focus and concentration issues.

## How to implement 2.2.2

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

### Do allow content to be paused and restarted

If there is scrolling or moving content on the site, you must provide a means of pausing or stopping such content. That way, the user can pause it to read the content or reduce the distraction being caused by such movement.
Some methods to address this would be to provide interactive controls or keyboard shortcuts, all of which should be clearly labeled and presented.
Good: Image of a scrolling news ticker with controls to pause it
Bad: Image of a scrolling news ticker with no control
### Do use scripts for adding the ability to control blinking and scrolling

Content that blinks or scrolls can be a hindrance when there isn’t a way to control what’s happening. This includes blinking elements that never stop. Such animations and movement can negatively impact user experience and those with disabilities.
To prevent that, including scripts to address these elements would largely benefit the user experience. One way would be to write a script that controls a blinking element and sets it to stop blinking within five seconds. Another would be to write some JavaScript that can display a control the user can use to access a ‘full’ version to read everything.
Blinking content should never last more than five seconds. This also applies to animated GIF images, which can be a little more tricky to address but far worth it in the long run. Animated GIF images utilize frames, frame rates, and repetitions to determine how long the image animates. The most common variable to adjust is the number of repetitions and make sure everything still fits within five seconds.
Examples of good and bad auto-scrolling social media feeds: the good example shows a button at the top of the screen to "Pause Live Feed."
### Ensure blinking, moving, or auto-updating content has a control

Flashing and blinking items can prove to be a huge distraction and tear the focus away. Animated GIF images are no exception to this rule - they can also be just as much of a menace if they go on too long. Providing a way to reduce the blinking action and control would be incredibly helpful.
This also includes auto-updating carousels, news tickers, and video players. There must be a way to pause or stop the content. Doing so will allow the user more control of their experience and give them time to read the content or stop the action so they can focus on the rest of the page.
Good: Auction items display a blinking tag for “new”, but stops within 5 seconds
Bad: Auction items display a blinking tag for “new” that doesn’t stop
### 

### Provide a mechanism for reloading the page without any blinking content

For people who absolutely cannot use a page with blinking content, it’s strongly advised to provide a control that will allow the user to reload the page without such blinking content. This will ultimately prevent issues with distraction, seizures, and dizziness.
Adding a control that says “Reload without animations” to the top of the page, for example, will dramatically help your user base and provide an accessible experience all around. When the page is reloaded, it should be identical in terms of the original page, but the content that was meant to be blinking or animated should now be static and highly visible. And, most importantly, not blinking.
In addition, adding a media query for prefers-reduced-motion would be a great opportunity for users to instantly land on a page and not have to deal with the hustle and bustle. This awesome query can help detect if the user is utilizing an operating system or browser preference to minimize the amount of animation or motion on their system. Both CSS and JavaScript can be used to check for the presence of this setting, and from there, the code can handle this situation much more efficiently. For example, a news carousel that animates automatically by default could be set to not animate if the user has indicated their preference for reduced motion.
Since this setting is rather obscure, it’s not super reliable, but it’s a great addition to your code and super handy to respect for those who have it set.
Good: A link at the top of a page that reloads the page with the blinking/scrolling/moving content remaining static now but obvious
Bad: No control, crazy site that is moving, blinking, scrolling, and general chaos.

## Conclusion

Meeting the 2.2.2 criterion for scrolling, moving, and blinking elements on the page will ensure that your content is accessible for all users without compromising their health and focus. Following these guidelines will allow everyone to perceive, understand, and focus on the information being communicated.

## Related Success Criteria

