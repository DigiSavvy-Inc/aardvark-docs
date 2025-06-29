# 3.1.2 Language of Parts - AAArdvark

[Understandable](https://aaardvarkaccessibility.com/wcag-principle/understandable/)

[Readable](https://aaardvarkaccessibility.com/wcag-guideline/readable/)

WCAG 2.0, 2.1, 2.2
Level AA

[View official documentation for WCAG 3.1.2](https://www.w3.org/WAI/WCAG22/Understanding/language-of-parts.html)

# 3.1.2 Language of Parts

Any parts of the page that are in a different language to the page itself are marked up with the appropriate lang value. Names and phrases derived from other languages, like “Déjà vu” in English, don’t need this.

[Code and Labels](https://aaardvarkaccessibility.com/wcag-theme/code-and-labels/), [Wording](https://aaardvarkaccessibility.com/wcag-theme/wording/) 

 

[Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Visual](https://aaardvarkaccessibility.com/wcag-disability/visual/) 

 

[Content](https://aaardvarkaccessibility.com/wcag-responsibility/content/) 

## What is it?

If some parts of a webpage use a different language, they should be marked so that assistive technology can detect and announce language changes to users. This is in addition to setting the page's default language, as required by WCAG 3.1.1 Language of Page .
Tagging different languages helps assistive technology in several ways:

Ensures speech synthesizers use the right pronunciation rules
Helps braille translation software follow language changes
Ensures browsers display the correct characters and enables tools like dictionaries to function properly

The goal of this success criterion is to make sure that assistive technology can recognize and handle different languages properly when they appear on a page.
An English web page with some French content is shown alongside a table comparing their pronunciation in both languages. “Propos” in French sounds like "proh-poh", but in English, it would be "praw-pus". “Appelez” in French sounds like "ah-puh-lay", but in English, it would be "ap-ull-lez". “Faisons” in French sounds like "feh-zohn", but in English, it would be "fay-zuns".

## Why does it matter?

When a webpage doesn't properly tag language changes, users—especially those using assistive technology—can run into problems. Assistive technologies like screen readers, text-to-speech tools, and braille translators rely on language tags to ensure correct pronunciation and text display. Otherwise, the text might sound garbled or confusing when read aloud.
Some languages also have unique characters, and if the language isn't set correctly, browsers might not display the text properly, making it unreadable. For example, Japanese, Arabic, or accented Latin characters may not render correctly if the language is not properly specified.

## Who is affected?

People with low or limited vision. People who are blind. People with difficulty reading written material. People with cognitive impairments.

People with vision impairments or blindness are most affected since they often use text-to-speech tools, braille translators, or screen readers. These tools work best when languages are properly marked, helping users avoid confusion.
People with reading difficulties or cognitive disabilities, like language processing or learning disorders, might also struggle. If a screen reader pronounces words incorrectly, it could make understanding content harder.

## How to implement 3.1.2

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

### Language Attribute for Specific Content Elements

For any text that's in a different language than the page’s default, use the lang attribute to tell browsers and assistive tech what language it is.
The main language of a page is set using the lang attribute in the <html> element. You can check it by looking at the page’s HTML.
To find and verify the correct language code, refer to “BCP 47: Tags for the Identification of Languages” or a common language subtags list.
Here's an example of a web page using Spanish as the main language, but one paragraph is in French. The lang="fr" attribute ensures that assistive technology recognizes French text correctly.
<!doctype html>
<strong><html lang="es"> <!-- The page's default language is Spanish --></strong>
<head>
    <meta charset="utf-8">
        <title>documento escrito en español</title>
    </head>
    <body>
        … documento escrito en español …
        <strong><p lang="fr">Ce paragraphe est en français.</p>
    </body>
</html>

## Conclusion

The lang attribute ensures accurate pronunciation, proper text display, and better comprehension for users relying on assistive technology. This small but important step improves the experience for people using screen readers, text-to-speech tools, and other assistive devices—making the web more inclusive for everyone.

## Related Success Criteria

