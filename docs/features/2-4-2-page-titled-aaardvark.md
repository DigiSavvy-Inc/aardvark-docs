# 2.4.2 Page Titled - AAArdvark

[Operable](https://aaardvarkaccessibility.com/wcag-principle/operable/)

[Navigable](https://aaardvarkaccessibility.com/wcag-guideline/navigable/)

WCAG 2.0, 2.1, 2.2
Level A

[View official documentation for WCAG 2.4.2](https://www.w3.org/WAI/WCAG22/Understanding/page-titled.html)

# 2.4.2 Page Titled

Each page has a unique title element that describes what’s on that page.

[Code and Labels](https://aaardvarkaccessibility.com/wcag-theme/code-and-labels/), [Whole Site](https://aaardvarkaccessibility.com/wcag-theme/whole-site/), [Wording](https://aaardvarkaccessibility.com/wcag-theme/wording/) 

 

[Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Visual](https://aaardvarkaccessibility.com/wcag-disability/visual/) 

 

[Content](https://aaardvarkaccessibility.com/wcag-responsibility/content/) 

## What is it?

This guideline makes sure that web pages have clear and descriptive titles so that users can easily navigate and understand a page without having to read through any content. Good titles help users find what they need and know where they’re going.
Site titles are shown in a variety of ways, including:

Site maps
Search engine results
Tab names or window title bars

## Why does it matter?

When web pages don’t have clear titles, it’s much harder for users to find and understand the content they need. This could be particularly challenging for people with visual impairments, cognitive disabilities, or those relying on audio navigation.
They'd have to spend more time reading through each page to figure out if it's relevant. It would also be confusing to navigate, especially if someone has multiple tabs open, making it difficult to keep track of where they are.
Tabs for a browser where each page is showing vague and unclear text, demonstrating how difficult it would be to navigate without good page titles.

## Who is affected?

People with visual impairments. People with cognitive disabilities. People with mobility impairments.

People with visual impairments use screen readers or other assistive technology to read the page titles when they have multiple tabs open and before reading through the content. A user can quickly sift through a list of clear page titles and navigate accordingly.
People with cognitive disabilities benefit from clear page titles because they can quickly grasp what a page is about without having to sift through all of the content. Thus, they reduce their cognitive load and make it easier for them to remember what each page contains.
People with mobility impairments may rely on audio navigation, using voice commands, or other assistive technologies to browse the web. Clear titles are read out loud by their devices and allow them to understand the purpose of each page quickly. They can decide if a page is relevant for them more efficiently without putting unnecessary effort into navigating.

## How to implement 2.4.2

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

### Using the <title> Element

Every HTML document, including those in frames, has a <title> element in the <head> section that gives a simple phrase describing the document's purpose. This helps users quickly understand where they are on the site without digging through the page content.
It's important to note that the <title> element (which is required and only appears once per document) is different from the title attribute (which can be added to almost any HTML element).
For this guideline, make sure that the web page’s source code has a non-empty <title> element in the head section and uses unique descriptive title text.
<html lang="en">
    <head>
        <title>Aardvark Wikipedia Article</title>
    </head>
    <body>
        ...
    </body>
</html>

### Descriptive Titles for Web Pages

A good title lets users quickly identify the page without reading all the content. It makes it easier to spot the right page in site maps or search results and helps users navigate directly to what they need.
A web page title should always:

Clearly state what the page is about
Make sense on its own, even if read by a screen reader or in a list
Be concise
Identifies the site or resource it belongs to
Be unique within that site or resource

#### Identify the Page’s Relationship to a Larger Collection of Web Pages

This technique helps users understand how the current web page is related to other pages on the same site — the relationship is described in the page's title.
For example, an online textbook is divided into chapters. The title of each Web page includes the chapter number and title as well as the title of the textbook.
Example of a site map where each page uses clear, unique, and concise page titles. The page titles include “Cool Agency Homepage”, “Cool Agency Services”, “Web Design Service by Cool Agency”, “Graphic Design Service by Cool Agency”, “SEO Service by Cool Agency”, “Cool Agency Service Pricing”, and “Features and Benefits to Cool Agency Services”.

## Conclusion

WCAG 2.4.2 requires web pages to have clear and descriptive titles. This helps everyone, especially people with visual, cognitive, and mobility impairments, find and understand content easily. To follow this guideline, use the title element in the HTML head to describe the page's purpose clearly and uniquely.

## Related Success Criteria

