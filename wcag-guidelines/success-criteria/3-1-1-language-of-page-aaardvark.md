# 3.1.1 Language of Page - AAArdvark

[Understandable](https://aaardvarkaccessibility.com/wcag-principle/understandable/)

[Readable](https://aaardvarkaccessibility.com/wcag-guideline/readable/)

WCAG 2.0, 2.1, 2.2
Level A

[View official documentation for WCAG 3.1.1](https://www.w3.org/WAI/WCAG22/Understanding/language-of-page.html)

# 3.1.1 Language of Page

There’s a lang attribute on the <html> element that matches the language of the page.

[Code and Labels](https://aaardvarkaccessibility.com/wcag-theme/code-and-labels/), [Wording](https://aaardvarkaccessibility.com/wcag-theme/wording/) 

 

[Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Visual](https://aaardvarkaccessibility.com/wcag-disability/visual/) 

 

[Code](https://aaardvarkaccessibility.com/wcag-responsibility/code/) 

## What is it?

Content can be presented in different languages and sometimes in multiple languages on the same page. Assistive technology requires that web pages programmatically identify the main language being used so that they can present the text correctly to the user.
Identifying the language on the page means that assistive technology can in turn load the correct pronunciation rules, browsers can display the correct characters and media players can show the correct corresponding captions.
The goal of this success criterion is to make sure that assistive technology can determine the default language programmatically.
A French web page shown next to a table comparing English and French pronunciations. The word “Propos” in French is pronounced “proh-poh” and in English “praw-pus”. The word “Appelez” in French is pronounced “ah-puh-lay” and in English “ap-ull-lez”. The word “Faisons” in French is pronounced “feh-zohn” and in English as “fay-zuns”.

## Why does it matter?

When a user encounters a webpage where the default language is not identified programmatically or is identified incorrectly, the user can face several types of challenges, especially if they use assistive technology. Screen readers, text-to-speech technology and braille translations need to receive information on what language the page is using so that the correct pronunciation rules can be used, otherwise the spoken text may be difficult to comprehend when spoken with synthetic speech.
Some languages also use special characters and when the language is not set programmatically, browsers may have trouble displaying the text to visual users. In some cases, this could make the text unreadable.
Lastly, captioning programs depend on the web page specifying the language so that the media players can correctly match up the users language to the correct captions. This is especially important when using multilingual websites, since multiple sets of captions could be provided for the same video.

## Who is affected?

People with low or limited vision. People who are blind. People with difficulty reading written material. People with cognitive impairments.

People with low or limited vision or who are blind are mainly affected by this since they’re most likely to use text-to-speech technology, braille translations, or screen readers. These assistive technologies can render text more accurately when the language is identified and can help these users avoid confusion.
People with difficulty reading written material or with certain cognitive impairments, such as language and learning disabilities, might face additional challenges with recognizing characters and alphabets or decoding words. They may also rely on text-to-speech technology where inaccurate pronunciations might make things confusing or difficult to understand..

## How to implement 3.1.1

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

### Language Attribute on the <html> element

Identify the default or main language of a web page, then set the language attribute for the <html> element on the page to this language. When a web page uses multiple languages, the default language should be the one used the most on the page.
To confirm, check that the <html> element on the page has a lang attribute and that the value conforms to the “BCP 47: Tags for the Identification of Languages” or use this list for common language subtags and that it reflects the primary language of the page.
Example where the <html> element for a web page is using Spanish, and the attribute is set to lang=”es”.
<!doctype html>
<strong><html lang="es"> </strong>
<head>
    <meta charset="utf-8">
        <title>documento escrito en español</title>
    </head>
    <body>
        … documento escrito en español …
    </body>
</html>

## Conclusion

Setting the main language of a webpage using the lang attribute is essential for making web content accessible and user-friendly. It ensures that assistive technology can function correctly and effectively. This simple step of identifying the default language means developers can significantly enhance the accessibility and usability of their websites for all users.

## Related Success Criteria

