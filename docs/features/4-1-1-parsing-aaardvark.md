# 4.1.1 Parsing - AAArdvark

[Robust](https://aaardvarkaccessibility.com/wcag-principle/robust/)

[Compatible](https://aaardvarkaccessibility.com/wcag-guideline/compatible/)

WCAG 2.0, 2.1
Level A

[View official documentation for WCAG 4.1.1](https://www.w3.org/WAI/WCAG22/Understanding/parsing.html)

# 4.1.1 Parsing

The markup has been validated and there are no errors, such as duplicate ids, missing tags, and invalid child elements.

[Code and Labels](https://aaardvarkaccessibility.com/wcag-theme/code-and-labels/) 

 

[Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Visual](https://aaardvarkaccessibility.com/wcag-disability/visual/) 

 

[Code](https://aaardvarkaccessibility.com/wcag-responsibility/code/) 

## What is it?

The goal of this success criterion is to make sure that browsers and assistive technologies can read and understand the webpage content correctly. If the content is poorly coded, assistive technologies might show it differently or fail to read it at all.
To avoid this, the content needs to be valid and well-formed in terms of how it’s coded. For example, in HTML, mistakes like broken tags can mess things up for assistive technologies trying to parse or read the content.
However, keep in mind that this criterion has been removed from WCAG 2.2. HTML and browsers have improved at handling coding errors. And, assistive technology no longer parses the code directly, but now relies on the browser to do it, making this guideline outdated. Most issues it covered will now fall under WCAG 1.3.1 Info and Relationships or WCAG 4.1.2 Name, Role, Value criteria.

## Why does it matter?

When this success criterion was in use and done correctly, it would ensure assistive technologies like screen readers can understand and interpret the content without errors.
If the page was coded incorrectly, such as having tags missing or incorrectly nested, it would lead to assistive technologies misinterpreting the page, or even crashing.

## Who is affected?

People who use screen readers or other assistive technologies.

People who rely on screen readers, magnifiers, or speech recognition technology. These tools depend on well-structured code to work correctly, and when it’s not, they might misinterpret the content, read it in the wrong order, skip important sections, or fail to convey the intended meaning. And, in worse scenarios, it can cause the assistive technology to crash or act unpredictably.
##

## How to implement 4.1.1

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

### Markup or HTML Used According to Spec

The main way to meet this guideline is to make sure the code follows the official specs for the code being used, like HTML. Using a validator helps catch errors and ambiguities in the code, ensuring it works correctly across different browsers and assistive technologies.
#### Opening and Closing Tags Used Properly

Make sure that each element in the page’s code includes the expected opening and closing tags. For example, a paragraph that starts with <p> needs to have the corresponding closing tag of </p>.
#### Unique ID Attributes

Make sure every ID attribute on the page is unique. You can check for duplicate IDs manually or use validation tools to flag this issue.
In this example, two different <a> elements use the same ID attribute value of “mylink”.
<a id="mylink" href=#>One of my links</a>
<a id="mylink" href=#>My other link!</a>

#### Duplicate Attributes Within One Element

Check and make sure that the same HTML element doesn’t include duplicate attributes, which can confuse assistive technologies. For example, take this heading that declares the ID attribute twice:
<h1 id="myHeading" id="heading1">Page Heading</h1>

## Conclusion

WCAG 4.1.1 was designed to ensure that web content was coded correctly so that assistive technologies like screen readers could accurately interpret it. Although this criterion has been removed in WCAG 2.2 due to advancements in HTML, browsers, and assistive technologies, the principles it promoted are still important. Proper coding—such as using correct opening and closing tags, unique IDs, and avoiding duplicate attributes—remains crucial for web accessibility.

## Related Success Criteria

