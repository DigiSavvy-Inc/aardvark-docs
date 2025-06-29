# 2.4.4 Link Purpose (In Context) - AAArdvark

[Operable](https://aaardvarkaccessibility.com/wcag-principle/operable/)

[Navigable](https://aaardvarkaccessibility.com/wcag-guideline/navigable/)

WCAG 2.0, 2.1, 2.2
Level A

[View official documentation for WCAG 2.4.4](https://www.w3.org/WAI/WCAG22/Understanding/link-purpose-in-context.html)

# 2.4.4 Link Purpose (In Context)

A link’s destination must be clear from either the link text itself or the surrounding sentence context.

[Code and Labels](https://aaardvarkaccessibility.com/wcag-theme/code-and-labels/), [Wording](https://aaardvarkaccessibility.com/wcag-theme/wording/) 

 

[Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Visual](https://aaardvarkaccessibility.com/wcag-disability/visual/) 

 

[Content](https://aaardvarkaccessibility.com/wcag-responsibility/content/) 

## What is it?

This guideline aims to make website links clear and helpful for all users, especially those using assistive technology like screen readers. This typically means using descriptive link text that tells users where the link leads without needing extra explanation so that users can decide if they want to follow the link.
The only exception is for links where the purpose is intentionally hidden, like in a game where the mystery is part of the fun. In those cases, unclear link text is okay because it adds to the experience.
Unclear links compared to a clearly defined link. The unclear link examples have question marks next to them to signify that their purpose is unclear. The other link says, “Aardvark Wikipedia Article” and shows a web page illustration next to it where you can clearly understand the link’s purpose based on the destination.

## Why does it matter?

When links are unclear, users can feel frustrated because they don't know where the link will take them. This lack of clarity makes it harder for them to decide if they want to click on the link or not.
Imagine trying to navigate a website where every link says "click here" or "read more" without any indication of what you'll find on the other side. It's like trying to choose a door without knowing what's behind it.
This uncertainty can make the browsing experience confusing and inefficient, especially for people using assistive technology who rely on clear link descriptions to understand the content of a webpage. Ultimately, unclear links disrupt the flow of navigation and can lead to users feeling discouraged or giving up on exploring the website altogether.
Illustration of a maze where vague links are scattered along the way. Navigating a site with unclear links can make users feel like they’re going through a maze.

## Who is affected?

People with limited mobility. People with cognitive disabilities. People with low or limited vision.

People with limited mobility can benefit from clear link descriptions by allowing them to skip links that they’re not interested in, saving them from unnecessary keystrokes from visiting irrelevant content. This makes navigation less physically demanding and more efficient.
People with cognitive disabilities may find unclear links and repetitive navigation options confusing. Clear links will make it easier to navigate without becoming disoriented or overwhelmed.
People with low or limited vision who rely on screen readers or other assistive technologies require that links be clear and descriptive. Otherwise, a lot of time is wasted trying to navigate solely based on the context around the links. Screen readers commonly present links in a list to users for navigation around the site, and unclear links make it impossible for the user to know where they need to go or where they’re going.
Example of a section with unclear link text and how assistive technology would announce the links. The example includes link text such as “Popular”, “Dog”, “Playful” “Learn More” and “Download”.

## How to implement 2.4.4

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

### Descriptive Link Text

The simplest way to give links a purpose is through the link text contained within the <a> element. The text should be distinguishable from the other links on the webpage and make it clear where the link leads or what it does.
For example, a link could say “Aardvark Wikipedia Article” instead of just “Wiki”.
<a href="https://en.wikipedia.org/wiki/Aardvark">Aardvark Wikipedia Article</a>

### Descriptive Context Surrounding Links

Some exceptions to descriptive link text are for links found within:

Headings
Sentences
Paragraphs
List items
Nested list items
Table cells

The surrounding context should provide more information for an unclear link and should help users tell it apart from other links on the page. In each case, it’s important that the link or <a> element is enclosed within the <p>, <li>, or <td> elements that provide it with context.
It's most helpful if the extra information needed to understand the link comes before the link. If it comes after, it can confuse users who read the page from top to bottom.
#### Heading Examples

Links can be included within the heading itself.
<h2>Overview of the AAArdvark species
<a href="aardvark-report.com"> report</a>
</h2>

Or, they can derive purpose from a preceding headline, too.
<h2>Overview of the AAArdvark species report</h2>
<p><a href="aardvark-report.com">Read in PDF Format</a>
</p>

#### Sentence Examples

In this example, the standalone link is unclear as “click here”; however, the adjacent text helps explain the link's purpose and what you’ll find if you click it.
<p>To learn more about the AAArdvark species report
<a href="aardvark-report.com"> click here.</a>
</p>

#### Paragraph Examples

In this example, the link is outside of the sentence, but this still meets the criteria because the link is within the wrapping paragraph or <p> element. It also gives the user enough information to understand the purpose of the link.
<p>Coming soon: The finals for the corgi dancing competition.
<a href="dancing-corgi.com/finals">Read more</a>
</p>

#### List Item Example

Similarly, links contained within the list item or <li> elements can derive context from the information they’re listed with.
<ul>
    <li>Check out the Aardvark species report from last year's
    <a href="aardvark-report.com">Aardvark Charity event</a>
</li>
</ul>

#### Nested List Item Example

Links within nested list items can also derive added context from the parent list item.
<ul>
    <li>
        <a href="https://en.wikipedia.org/wiki/Aardvark">
            Everything To Know About Aardvarks
        </a>
        <ul>
            <li>
                <a href="https://en.wikipedia.org/wiki/Aardvark#Habitat_and_range">
                    Habitat and Range
                </a>
            </li>
        </ul>
    </li>
</ul>

#### Table Cell Example

Links within Table Cells can derive context from text within the same cell and the row or column headers.
<table>
    <caption>Aardvarks tracked by the Aardvark Charity Commission</caption>
    <tr>
        <th>Country of Habitat</th>
        <th>Kenya</th>
        <th>Uganda</th>
    </tr>
    <tr>
        <th scope="row">Number of Aardvarks Tracked Per Country</th>
        <td><a href="aaardvark-report.com/kenya">35</a></td>
        <td><a href="aaardvark-report.com/uganda">12</a></td>
    </tr>
</table>

### Links with Graphics or Images

If the link is solely graphical, for example, the only content within the <a> element is an image, then the alt attribute needs to be included to help describe the link.
<a href="https://en.wikipedia.org/wiki/Aardvark">
    <img src="aardvark_animal_icon.png" alt="Aardvark Wikipedia Article">
    </a>

However, if you include descriptive text within the <a> element to go alongside your graphic, and any added descriptions would be repetitive, then you can leave the alt attribute empty.
<a href="https://en.wikipedia.org/wiki/Aardvark">
    <img src="aardvark_animal_icon.png" alt="">Aardvark Wikipedia Article
</a>

### Adjacent Linked Images and Text With the Same Destination

In an effort to reduce redundant links that point to the same destination or resource, it’s important to review linked images that are adjacent to linked text. This layout is pretty common across the web; for example, blog listings or product listings with a featured image next to a linked title, where both point to the same page.
In these cases, you’ll need to make sure your HTML is set up so that the image or <img> element is contained within the <a> element. Once the image is contained, you can also apply alt text to the image if it describes the image or adds context to the link.
This makes it easier for screen readers to navigate the page since it does not contain duplicate links to the same resource and doesn’t have to read aloud duplicate information.
Do:
<a href="https://dog.com/dancing-shoes">
    <img alt="Dog wearing dancing shoes with the text 'Buy Now' below" src="dancing_dog.png">
        Buy Doggy Dancing Shoes Today!
    </a>

Don’t:
<a href="https://dog.com/dancing-shoes">
    <img alt="Dog wearing dancing shoes with text 'Buy Now' below" src="dancing_dog.png"
</a>
<a href="https://dog.com/dancing-shoes">
    Buy Doggy Dancing Shoes Today!
</a>

Product listing where the featured image depicts a dog wearing dancing shoes and the linked title says, “Buy Doggy Dancing Shoes Today”. A click icon is shown over the image and the title to convey that both elements are linked.
### CSS to Hide Descriptive Text

Another approach involves adding descriptive text to a link and using CSS to hide the extra text from being displayed. If done correctly, the text is still accessible to screen readers while allowing the visual design to stay clean.
CSS techniques using visibility: hidden or display: none would hide the text from screen readers. A better approach would be to place the descriptive text in a 1-pixel container with overflow: hidden, so it's not visible on screen but can be read by screen readers.
.visually-hidden {
clip-path: inset(100%);
clip: rect(1px, 1px, 1px, 1px);
height: 1px;
overflow: hidden;
position: absolute;
white-space: nowrap;
width: 1px;
}

And the style can be injected through a <span> contained within the <a> element, like so:
<a href="https://en.wikipedia.org/wiki/Aardvark">Wikipedia
<span class="visually-hidden">Article About Aardvarks</span>

#### Image Maps

Image Maps are special types of images that include selectable <area> regions within them that count as links. In addition to the <img> overall alt text description, each <area> must also provide its own alt attribute to describe its purpose.
A world map with clickable highlighted areas for the continents to learn more. Each continent has its own alt text, for example, “Learn about Asia”.
### aria-label and aria-labelledby

It’s worth noting that the best way to handle link purpose accessibility is through the methods listed above; however, if you must use custom interactive elements, ARIA can help ensure your links still have context.
The aria-label attribute adds a text label to a link when there is otherwise no visible text describing it. If there are visible descriptive elements, the aria-labelledby attribute should be used instead.
#### aria-labelledby attribute

Links can derive their meaning from adjacent visible text elements on the page and use the aria-labelledby attribute to make the connection. Any associated label text is announced to represent the link instead of the embedded link text.
In the following example, the link will be announced as “Aardvark Wikipedia Article” based on the heading instead of “Continue Reading….” which is included in the link markup.
<h2 id="aardvark-wiki-page">Aardvark Wikipedia Article</h2>
<a id="aardvark-wiki-link" aria-labelledby="aardvark-wiki-page aardvark-wiki-link"
href="https://en.wikipedia.org/wiki/Aardvark">
Continue Reading…
</a>

#### aria-label attribute

However, if no visible descriptive text elements on the page can be used to represent the link, then the link can use the aria-label attribute.
In this example, the link is announced as ”Continue reading about Aardvark habitats and food sources.” based on the aria-label found within the link or <a> element.
<a aria-label="Continue reading about Aardvarks and their habitats and food sources."
href="https://en.wikipedia.org/wiki/Aardvark">
Continue Reading…
</a>

## Conclusion

Following WCAG 2.4.4 makes sure website links are clear and easy to understand, especially for people using assistive technology. Descriptive link text or context helps users know where a link will take them, making navigation simpler and more efficient.

## Related Success Criteria

