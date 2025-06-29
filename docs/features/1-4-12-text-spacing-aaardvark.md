# 1.4.12 Text Spacing - AAArdvark

[Perceivable](https://aaardvarkaccessibility.com/wcag-principle/perceivable/)

[Distinguishable](https://aaardvarkaccessibility.com/wcag-guideline/distinguishable/)

WCAG 2.0, 2.1, 2.2
Level AA

[View official documentation for WCAG 1.4.12](https://www.w3.org/WAI/WCAG22/Understanding/text-spacing.html)

# 1.4.12 Text Spacing

Users can increase letter, word, line, and paragraph spacing without cutting off content or breaking functionality.

[Zoom and Legibility](https://aaardvarkaccessibility.com/wcag-theme/zoom-and-legibility/) 

 

[Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Visual](https://aaardvarkaccessibility.com/wcag-disability/visual/) 

 

[Code](https://aaardvarkaccessibility.com/wcag-responsibility/code/), [Design](https://aaardvarkaccessibility.com/wcag-responsibility/design/) 

## What is it?

Text content should be able to adapt to user-defined text spacing settings, such as line height, paragraph spacing, letter spacing, and word spacing. These text properties should not cause content to break, overlap, or cut off.
The goal is to make the text more readable while keeping the original page design and layout intact and functional.

## Why does it matter?

Some people, like those with low vision or dyslexia, need custom text spacing to read effectively. Without this flexibility, content can become unreadable due to overlapping or truncated text.
Proper text spacing:

Helps readers focus
Reduces eye strain
Increases reading speed

When web content adjusts gracefully, everyone benefits, whether they’re using assistive tech or just adjusting settings for personal comfort.
Example of bad support for text spacing where overlapping text makes the page unreadable.

## Who is affected?

People with low or limited vision. People with dyslexia. And people with cognitive disabilities.

People with low vision need larger text and more space to help distinguish between characters, lines, and words.
People with dyslexia can benefit from increased space between lines, words, and letters to avoid confusion and improve their reading speed.
People with cognitive disabilities who rely on clear visual structure can also process content better when white space is applied between blocks of text to help them differentiate between sections.

## How to implement 1.4.12

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

### Allow for Text Spacing Override

Content should let users adjust text spacing with stylesheets, extensions, or apps. The key is making sure text containers have room to grow or expand to prevent content from getting cut off or overlapping.

Avoid setting fixed heights for text areas—let them adapt as needed to fit the content.
For non-wrapping text, make sure containers are at least 20% wider than the default width to account for the spacing adjustments. This helps prevent unwanted wrapping.
Specify the width and height of text containers using em or rem units to ensure they resize with text size changes. Fixed units risk text cropping when resized.

When testing, make sure that you can meet these requirements:

Line height to at least 1.5 times the font size
Paragraph spacing to at least 2 times the font size
Letter spacing to at least .12 times the font size
Word spacing to at least .16 times the font size

Page layout that allows for text spacing overrides and takes the potential changes into account. For example, text with a default font size of 1em or 16px would need to be checked for: Line height: 1.5 × 16px = 24px; Paragraph spacing: 2 × 16px = 32px; Letter spacing: 0.12 × 16px = 1.92px; Word spacing: 0.16 × 16px = 2.56px
The CSS below could be used to test out the requirements; if the page layout and content still look good after making these adjustments, then the success criterion is met.
/* Base font size of 16px or 1rem */
body { font-size: 1rem; }
 
/* Line height set to at least 1.5 times the font size */
p { line-height: 1.5; /* This automatically calculates as 24px for a 16px font size */ }
 
/* Paragraph spacing set to at least 2 times the font size */
p + p { margin-top: 2em; /* This ensures spacing between paragraphs is 32px */ }
 
/* Letter spacing set to at least 0.12 times the font size */
p { letter-spacing: 0.12em; /* This is 1.92px for a 16px font size */ }
 
/* Word spacing set to at least 0.16 times the font size */
p { word-spacing: 0.16em; /* This is 2.56px for a 16px font size */ }

## Conclusion

Giving users control over the content’s text spacing is important to make sure users can read comfortably. By following WCAG 1.4.12, you ensure your website works for everyone, including those with low vision, dyslexia, or other reading challenges.

## Related Success Criteria

