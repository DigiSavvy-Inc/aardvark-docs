# 2.3.1 Three Flashes or Below Threshold - AAArdvark

[Operable](https://aaardvarkaccessibility.com/wcag-principle/operable/)

[Seizures and Physical Reactions](https://aaardvarkaccessibility.com/wcag-guideline/seizures-and-physical-reactions/)

WCAG 2.0, 2.1, 2.2
Level A

[View official documentation for WCAG 2.3.1](https://www.w3.org/WAI/WCAG22/Understanding/three-flashes-or-below-threshold.html)

# 2.3.1 Three Flashes or Below Threshold

Flashing content must not exceed three flashes per second unless it is within safe limits.

[Sensory](https://aaardvarkaccessibility.com/wcag-theme/sensory/) 

 

[Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Visual](https://aaardvarkaccessibility.com/wcag-disability/visual/) 

 

[Content](https://aaardvarkaccessibility.com/wcag-responsibility/content/), [Design](https://aaardvarkaccessibility.com/wcag-responsibility/design/) 

## What is it?

Content such as videos, gifs, or other animations on a web page can sometimes include rapid flashing between dark and light colors. For example, this could be a bright and eye-catching music video or a browser game that shows colorful explosions as part of the gameplay.
While this can make content intriguing and exciting, to some people, flashing lights on a web page can trigger potentially severe and dangerous seizures.
The goal of this success criterion is to make sure any flashing on a web page meets the three flash criteria or falls below a threshold so that seizures are unlikely to get triggered.

## Why does it matter?

People who experience photosensitive disorders cannot control their body's reactions. Any unexpected flashing may put the user in potentially life-threatening situations or, at the least, very uncomfortable ones.
When flashing is not adjusted for a web page, users will miss the whole experience of the content - even if text alternatives are provided. For example, think of an action movie with a lot of flashing scenes; a user would not be able to experience the film to the same extent by reading the script.

## Who is affected?

People with photosensitive epilepsy or seizure disorders.

People with photosensitive epilepsy or seizure disorders can be affected by flashing lights or colors. Unexpected exposure to flashing can trigger dangerous or uncomfortable reactions in users' bodies. Without moderating the flash, a user will miss out on experiencing the content.

## How to implement 2.3.1

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

To meet this criterion, one or both of the following techniques should be implemented.
### Less Than Three Flashes Per Second

One technique for meeting the WCAG 2.3.1 criterion is to reduce the rate of flashing to less than three flashes per one-second period.
Note that a flash is defined by abrupt changes in contrasting light or colors. Each transition counts as a flash.
Examples of contrasting colors. Abruptly changing between colors, such as the ones shown, is considered a ‘flash’. Examples include the “same color with different saturation levels”, “classic black and white or similar”, and “two colors with different saturation.”
### Small Flashing Area

If you have content that flashes more than three times per second, an alternate approach is to reduce the area that flashes on the screen.
A general rule of thumb is to keep the area less than 25% of the central 10 degrees of vision. Essentially, the “central 10° of vision” refers to the rectangular shape that 10° captures from the viewer's perspective, given their distance. The goal is to keep the flashing area below a 25% square pixel threshold of that rectangular-shaped area.
Note that the shape and location of the flashing area don’t matter; we’re focusing on it in terms of square pixels and how much of the page it occupies at any given time.
A user viewing a computer screen, the viewing distance is pointed out, and a triangle outlining the rectangle shape on the screen represents their “central 10° of vision. A smaller box is highlighted to represent the 25% square pixel area of the rectangle.

## Conclusion

In conclusion, making sure that flashing content on web pages meets the WCAG 2.3.1 criterion is crucial for the safety and accessibility of all users, particularly those with photosensitive epilepsy or seizure disorders.
By limiting flashing to less than three flashes per second or reducing the flashing area to less than 25% of the central 10 degrees of vision, we can significantly reduce the risk of triggering seizures and make sure that everyone can safely engage with online content.

## Related Success Criteria

