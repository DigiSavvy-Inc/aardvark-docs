# 1.3.2 Meaningful Sequence - AAArdvark

[Perceivable](https://aaardvarkaccessibility.com/wcag-principle/perceivable/)

[Adaptable](https://aaardvarkaccessibility.com/wcag-guideline/adaptable/)

WCAG 2.0, 2.1, 2.2
Level A

[View official documentation for WCAG 1.3.2](https://www.w3.org/WAI/WCAG22/Understanding/meaningful-sequence.html)

# 1.3.2 Meaningful Sequence

The visual presentation of the content matches what’s read out by a screen reader.

[Code and Labels](https://aaardvarkaccessibility.com/wcag-theme/code-and-labels/), [Wording](https://aaardvarkaccessibility.com/wcag-theme/wording/) 

 

[Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Visual](https://aaardvarkaccessibility.com/wcag-disability/visual/) 

 

[Code](https://aaardvarkaccessibility.com/wcag-responsibility/code/) 

## What is it?

Web Content can be reordered, styled, and moved around in a way that may make sense visually. But when that same content is processed by assistive technology, the order in which the content is presented needs to make sense, too.
It’s common for elements to get rearranged or displayed in a different order using CSS. For visual users, this can make sense on the page, but just keep in mind that CSS does not make changes to the HTML itself. This means that content contained within the HTML remains in its original order and will be used by assistive technology.
Sometimes, the order of elements doesn’t matter, in which case, that’s fine and can be left as-is (but don’t forget about the elements that also need to maintain Focus Order to meet WCAG 2.4.3!). However, any content that requires a set sequence to be useful needs to be presented in a way that the user can understand its meaning without getting confused.
Imagine it sort of like reading a book, but all the chapters are scrambled. You can also follow a recipe but with the steps sprinkled throughout a web page’s content instead of in a neat list. Some pieces of information just need to be neatly ordered or organized to be helpful.
The Chapter Guide for “Alice in Wonderland”, the chapters are scrambled and don’t follow their correct number order.

## Why does it matter?

When sequential content on a page isn’t structured linearly or doesn’t follow a meaningful order, it becomes useless for users who do not perceive information visually. If this is the case, using assistive technology will disorient or confuse users trying to navigate information presented in the wrong sequence.
Web page where steps for a cupcake recipe are scattered throughout the content and in the sidebar. The user must scan the page to find the next step, and assistive technology must read out all the page content to cover the full recipe.

## Who is affected?

People with low or limited vision. And people with reading and learning disabilities.

People with vision impairment or cognitive disabilities often rely on screen readers or other assistive technology to help them access content on a webpage. Providing content without a linear order (when needed) makes it difficult for assistive technology to convey the meaning of the content properly. It affects the user’s overall understanding of the information on the page.
People who cannot perceive visual content will miss out on important information included in content that requires a meaningful sequence. Making sure all the elements on a page follow a linear and intuitive order makes it so that a screen reader or refreshable braille display can process the information.

## How to implement 1.3.2

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

### Review the Content in Its Linear Order

In summary, implementing 1.3.2 will require that you review your web page and make sure that any elements or pieces of content that require a linear order to convey meaning stay intact when any visual layouts or styling is removed.
The best way to do this is to remove the layout styles using a tool that strips all the CSS and styling and outputs the page elements as assistive technology would process them.
Providing a particular linear order is only required where it affects the meaning of the content. There may be more than one order that is "correct". As long as the content yields the same meaning as the original, this is sufficient to meet the criteria. And only one correct order needs to be provided.
Examples of content that derives meaning from its sequence:

Numbered lists
Table of Contents of Page Content Listing
Video tutorials that require being watched in order
Letters in Words & Words in Sentences: splitting these up would not convey the same meaning
Tables
Form Fields
Corresponding Headers and Paragraphs

Some examples of content that doesn’t draw any meaning from the sequence:

Unordered lists
The relative order of the different sections on the page. For example, a sidebar may not affect the overall meaning if it’s presented before or after the blog content.
Product page listings

Section containing information about Dogs, Cats, and Birds where the corresponding header, image, and paragraph are not grouped together. The animal species headers are read aloud first, followed by the alt text for all the photos, and lastly, the paragraphs.
 
#### White Space

White space can sometimes be used for aesthetic purposes to bring emphasis to words and sentences. However, when using spacing, tabs, or any other text separators to create the white space, the meaning can be lost.
Take this heading, for example:
<h1>W e l c o m e</h1>

White spaces are added in between each letter of the word “Welcome”. Visually it’s clear that this was intended to spell out “Welcome”, but for assistive technology, this heading is considered “W”, “e”, “l”, “c”, “o”,”m”,”e”, which could be very dull or confusing to process, especially as the main heading for the page.
The same applies to sentences; if a sentence is split up in an aesthetically pleasing way, it can lose its meaning, especially if the linear order isn’t reviewed.
Web page where the headings are split up so that they read, “C” “A” “T” “S” “Cool” “Are” instead of “Cats are cool”.
 
#### Tables

HTML <table> elements need to be reviewed very carefully, the linearization of <table> content is often broken because when we make tables, we don’t often take into account how two dimensions get translated linearly.
Assistive technology processes the content row-by-row. Starting off with the first cell in the first row and making its way down to the last cell in the last row.
When working with tables that contain meaningful sequences, the content of each cell needs to be reviewed to make sure that the information makes sense when traversing the table in the way screen readers or refreshable braille keyboards would.
Linear order of a two-by-three table illustrated using numbers and arrows. The first linear element is in the first cell on the first row, moves to the right, and then goes down to the second row.

## Conclusion

WCAG 1.3.2 is a success criterion that helps users who rely on assistive technology to process content in the right order. By organizing and ordering information that requires a set sequence to have meaning, we can help users better understand our content and avoid confusing them.

## Related Success Criteria

