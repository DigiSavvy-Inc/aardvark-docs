# 1.4.9 Images of Text (No Exception) - AAArdvark

[Perceivable](https://aaardvarkaccessibility.com/wcag-principle/perceivable/)

[Distinguishable](https://aaardvarkaccessibility.com/wcag-guideline/distinguishable/)

WCAG 2.0, 2.1, 2.2
Level AAA

[View official documentation for WCAG 1.4.9](https://www.w3.org/WAI/WCAG22/Understanding/images-of-text-no-exception.html)

# 1.4.9 Images of Text (No Exception)

Text is actual text; never images of text.

[Sensory](https://aaardvarkaccessibility.com/wcag-theme/sensory/), [Zoom and Legibility](https://aaardvarkaccessibility.com/wcag-theme/zoom-and-legibility/) 

 

[Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Visual](https://aaardvarkaccessibility.com/wcag-disability/visual/) 

 

[Code](https://aaardvarkaccessibility.com/wcag-responsibility/code/), [Content](https://aaardvarkaccessibility.com/wcag-responsibility/content/), [Design](https://aaardvarkaccessibility.com/wcag-responsibility/design/) 

## What is it?

Text on a website should always be real, selectable, customizable text - never a picture of text. That means images of text are only allowed if there’s absolutely no other way to convey the information, like a logo.
Both WCAG 1.4.5 Images of Text and 1.4.9 focus on using real text instead of images. However, while 1.4.5 allows a few exceptions, 1.4.9 remove those exceptions. For AAA compliance, images of text are only allowed if the image itself is essential to the content.
Side-by-side comparison showing the difference between an image of text and real text. Left side: 'Image of Text: Blurry or Pixelated' shows a fuzzy, hard-to-read quote about aardvarks. Right side: 'Real Text: Clear and Customizable' shows the same quote in sharp, adjustable text.

## Why does it matter?

Static pictures of text make it impossible for people to change how text looks to improve readability. Text in images doesn’t scale well and can become pixelated, blurry, or unreadable when users zoom in. Unlike actual text on the page, image-based text won’t adjust to different screen sizes or user settings, making it harder to read on mobile or larger screens.
Users who need to change font size, color contrast, or background color to improve readability can’t do so with text embedded in images. This is challenging for users with low vision, color blindness, or cognitive disabilities who benefit from specific text formatting.
Screen readers can’t interpret text inside images, so people who rely on these tools won’t be able to access the content unless the image is properly captioned or has alt text.

## Who is affected?

People with low or limited vision. People with visual tracking issues. And people with cognitive disabilities.

People with low vision often need to zoom or change text colors. Text in images can’t adapt, and zooming just makes it blurry.
People with visual tracking issues can benefit from adjusting text alignment and spacing to help with eye strain and fatigue. Text in images prevents these users from making the customizations they need.
People with cognitive disabilities may need specific fonts, colors, or line spacing to help them read, and text inside of an image limits their ability to change the text settings.

## How to implement 1.4.9

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

### Never Use Images of Text

To meet this guideline, don’t use images to display written content—even decorative quotes or button labels. Stick with real text in HTML or CSS so users can resize and style it however they need.
Zoomed-in image of text on a mobile device; the text appears blurry and hard to read.
#### Exceptions for Essential Images of Text

Images of text are allowed only when absolutely necessary, such as:

A logo or wordmark that’s part of a brand identity
A graphic where text is visually essential to the design (e.g., art or diagrams)

Images of text are considered necessary only when the visual appearance of the text is required to understand the content (like a stylized logo or part of a graphic design with specific meaning).
If you must use an image of text, be sure to provide the content another way—like a caption or alt text—so it’s still accessible.
On the left, a text box reads: 'Alt Text: Logo for Dancing Dog Productions featuring a dancing corgi wearing star-patterned cowboy boots.' On the right, the logo shows a happy corgi in boots surrounded by the words 'Dancing Dog Productions.'
### CSS To Style Text

Use CSS to get a similar look to the text in the image, and stick with relative measurements like em, rem, %, vw, and vh. This way, the text scales smoothly on different screen sizes and adjusts easily when users zoom in or tweak their settings. Using relative units keeps things flexible, so the layout stays intact and readable across all devices.
This is also a success criterion of its own; check out WCAG 1.4.4 Resize Text for more information.

There are two examples: one where the text is part of the image and another where the text is pulled out and displayed as a heading above the image. CSS styles the heading so it looks similar to the original text in the image.

### Switch Between Image of Text and Plain Text

If you're using an image of text for design reasons—like a decorative heading—you can offer a plain text version too. This gives users a choice between visual style and accessibility.
But it's important to note that to meet 1.4.9, the real, acessible text must be either shown by default or immediately visible alongside the image. A toggle alone isn't enough. Real text must be part of the default experience.

## Conclusion

Text should act like text. If users can’t resize it, select it, change its color, or read it with a screen reader—it’s not truly accessible.
Unless you have a strong reason (like a logo), always use real text. It improves readability, supports personalization, and makes your content work better for everyone.

## Related Success Criteria

