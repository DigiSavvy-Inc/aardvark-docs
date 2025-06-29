# 2.5.8 Target Size (Minimum) - AAArdvark

[Operable](https://aaardvarkaccessibility.com/wcag-principle/operable/)

[Input Modalities](https://aaardvarkaccessibility.com/wcag-guideline/input-modalities/)

WCAG 2.2
Level AA

[View official documentation for WCAG 2.5.8](https://www.w3.org/WAI/WCAG22/Understanding/target-size-minimum.html)

# 2.5.8 Target Size (Minimum)

Clickable elements must be at least 24 by 24 pixels, except for inline links.

[Gestures](https://aaardvarkaccessibility.com/wcag-theme/gestures/) 

 

[Physical/Motor](https://aaardvarkaccessibility.com/wcag-disability/physical-motor/) 

 

[Design](https://aaardvarkaccessibility.com/wcag-responsibility/design/) 

## What is it?

Buttons, links, and other interactive elements should be at least 24 x 24 pixels. If that’s not possible, they should have enough empty space around them to make clicking easier.
Even if an element is smaller than 24 x 24 pixels, it can still pass as long as there’s enough space between it and other clickable elements. But it’s always a good idea to make them bigger for easier use.
For important buttons or links, the stricter 2.5.5 Target Size (Enhanced) rule is recommended.

## Why does it matter?

Tiny buttons and links are frustrating to click or tap, especially on touchscreens like phones and tablets. When they’re placed too close together, it’s even easier to tap the wrong one by mistake.
People with limited hand control–like those with tremors, arthritis, or other mobility challenges–may struggle to tap small buttons. If elements are too close together, they could tap or click the wrong one or not be able to use it at all.

## Who is affected?

People with mobility impairments. People on smaller screens. People in unstable environments. People with large fingers.

People with mobility impairments, such as hand tremors or conditions affecting fine motor skills, can find it challenging to select targets that are too small, especially if they’re placed close to other elements.
People using smaller screens, such as tablets or mobile devices, will also find smaller targets challenging to use. When tapping with a finger, the space selected is not exact, potentially selecting unwanted elements. This is especially true for people with large fingers.
People in unstable or shaking environments, like moving vehicles, will struggle to select elements that are too small.

## How to implement 2.5.8

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

### Minimum Size and Spacing

Make all buttons, links, and interactive elements at least 24 x 24 pixels. If that’s not possible, add extra space around them so they’re easier to tap.
To make sure buttons meet the size requirement, you can adjust CSS settings. Use the min-height and min-width CSS properties to set the minimum size. Or, add padding to help give them a total size of 24 x 24 with the extra spacing in between.
Example of passing and failing adjacent icons. In example 1, the buttons are at least 24 x 24 pixels, so they meet the rule. In example 2, the buttons are smaller, but because they have enough empty space around them, they still pass.In example 3, the buttons are both too small and too close together, making them hard to tap. They don’t meet the rule
### Equivalent Action Element

An exception to this rule is if there’s another element with the equivalent action on the page. If this is true, the element can keep its size smaller than 24 x 24 pixels. Note that other elements must meet this success criterion.
Example of a small interactive element to initial a call right next to a much larger button element with the equivalent action of calling.
### Exception for Inline Elements

Interactive Elements inline with text, such as sentences, paragraphs, etc., are an exception since the line height limits the size, and it’s impossible to tell where the interactive element will fall as screen sizes change and the text reflows.
However, it’s a good idea to increase the line height to keep the text readable and easy to tap or click.
Example of a paragraph containing three links, each line is only 12 pixels high, so the links would technically fail the success criterion. But, since they are part of inline text, they are an exception. However, it’s recommended that the line height be increased.
### Exception for Essentials

Lastly, if it’s absolutely necessary or legally required for the target size and spacing to be smaller than 24 x 24 pixels, this rule can be skipped.
This is an example of a map where the pins are too close together and not big enough, but it’s necessary since we can’t control where the pins will be placed, and if they are too large, they will be indistinguishable from each other.

## Conclusion

Bigger buttons and links aren’t just for people with disabilities–they make websites easier for everyone. Keeping buttons and links at least 24 x 24 pixels (or giving them enough space) helps users of all devices, making your website more user-friendly for all.

## Related Success Criteria

