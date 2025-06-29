# 1.3.1 Info and Relationships - AAArdvark

[Perceivable](https://aaardvarkaccessibility.com/wcag-principle/perceivable/)

[Adaptable](https://aaardvarkaccessibility.com/wcag-guideline/adaptable/)

WCAG 2.0, 2.1, 2.2
Level A

[View official documentation for WCAG 1.3.1](https://www.w3.org/WAI/WCAG22/Understanding/info-and-relationships.html)

# 1.3.1 Info and Relationships

Information or relationships between content that is visual is also conveyed through the code, via HTML or ARIA (for example the for attribute on a form label, or aria-describedby on an input that has hint text).

[Code and Labels](https://aaardvarkaccessibility.com/wcag-theme/code-and-labels/), [Wording](https://aaardvarkaccessibility.com/wcag-theme/wording/) 

 

[Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Visual](https://aaardvarkaccessibility.com/wcag-disability/visual/) 

 

[Code](https://aaardvarkaccessibility.com/wcag-responsibility/code/), [Content](https://aaardvarkaccessibility.com/wcag-responsibility/content/) 

## What is it?

Web content often includes little visual or audio cues to show how things are connected. Things like layout, color, symbols, bold or italic text, grouping, table organization, sound effects, etc. These cues can help us quickly understand meaning and structure. For example:

Bold text might show something is important.
Grouped form fields might suggest they belong together.
A sound chime might signal that there is new content on the page.

These clues make content easier to follow for people who can see or hear them. But if someone is using a screen reader or can't see the screen, those subtle clues might not be available, unless they are built into the underlying code.
That's what this guideline is all about: making sure any information or relationships that are shown visually (or with sound) are also coded properly using HTML or ARIA, so assistive technology can understand and share them with users.
Webpage without semantic markup vs one with semantic markup to help organize and provide additional information on subtle cues and content groupings.

## Why does it matter?

People who can't see or hear the page content might not catch all the meaning if that meaning is only conveyed through appearance or sound. When those cues aren't available, assistive tech needs extra help, and that's where proper coding comes in.
Even subtle formatting choices (like putting items close together or changing font size) can communicate important relationships. Without coding those relationships too, they can get lost for people using screen readers or braille displays.

## Who is affected?

People with low or limited vision. And people who are deaf-blind.

People who use screen readers or other assistive tech rely on the underlying structure of the code to understand what's on the page. If the content only looks structured visually, but isn't built that way in code, it's harder to follow, and sometimes even impossible to understand.
This applies to both visual and auditory content. The more those subtle cues are backed up with proper markup, the more accessible your content will be.

## How to implement 1.3.1

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

### Semantic HTML and Structure

#### Identifying Regions of a Page with Landmarks

Landmarks help assistive tech users jump to key parts of a page without having to go through everything line by line. These are created using semantic HTML tags like:

<header>: Usually holds site-wide elements like the logo and navigation
<nav>: Used for menus or internal page links
<main>: Marks the main content of the page

Using these tags helps assistive tech users quickly get to the part of the page they want.
Example Landmarks and their corresponding sections on a webpage.
#### Markup For Semantic Elements

Use proper HTML tags for each type of content so assistive tools know what it is:

Headings: <h1>, <h2>, etc.
Paragraphs: <p>
Links: <a>
Quotes: <blockquote> or <cite>
Abbreviations: <abbr>

Also, keep the order of elements logical. For example, don't jump from an <h1> to an <h4>) - that can be confusing for assistive tech users.
<h1>How to find an Aardvark</h1>
<p>Step One: Finding an Aardvark is a challenging feat. It takes bravery, determination, and most importantly…</p>
<cite>Steve Irwin</cite>
<a href="aardvarkfinder.com">How to find Aardvarks in more detail</a>

#### Headings

According to WebAIMs 2023 screen reader survey , over 70% of users navigate using headings.
That makes heading structure super important. It helps users jump between sections and understand how the content is organized just by listening.
Properly organized headings allow users to navigate the page and understand the content.
#### Lists and Groups of Links

Lists should always use proper HTML list elements:

<ul> for unordered (bulleted) lists
<ol> for ordered (numbered) lists
<li> for each list item

Don't use dashes, asterisks, or line breaks to fake a list visually. Assistive tech won't recognize them as a list unless they're marked up properly.
### Style Cues

Color, size, and style (like bold or italics) can help emphasize content, but they don't mean much to users who can't see them.
For example, if red asterisks are used to show required form fields, be sure to also explain in text that the field is required, or use proper form markup so screen readers can announce it.
### Tables

If your content is laid out like a spreadsheet or grid, where information is in rows and columns, you'll need to use proper HTML table markup:

<table>
<tr> for table rows
<th> for table headings
<td> for table cells

Also include a <caption> to give the table a title, which helps users understand what it's for.
<table>
    <caption>Sunset and Sunrise Times for March in Los Angeles</caption>
    ...
</table>

Avoid using tabs or columns created with spacing alone since assistive tech can't make sense of those.
### Form Controls

Every form field (like a text input) needs a matching <label> tag, connected with a for attribute. This tells users what each field is for and makes forms easier to use, especially for assistive tech users or those with motor challenges.
<label for="firstname">First name:</label>
<input id="firstname" name="firstname" type="text">

#### Grouping for Related Form Controls

For sets of related fields (like address information or multiple checkboxes), group them using <fieldset> and <legend> to give users extra context.
<fieldset>
    <legend>Your Residential Address</legend>
    <div>
        <label for="raddress">Address:</label>
        <input autocomplete="street-address" id="raddress" name="raddress" type="text">
        </div>
        <div>
            <label for="rzip">Postal/Zip Code:</label>
            <input autocomplete="postal-code" id="rzip" name="rzip" type="text">
            </div>
        </fieldset>

Group of Form Fields For Collecting an Address.
### ARIA Landmarks and Roles

HTML first, ARIA second. ARIA (Accessible Rich Internet Applications) should only be used when there's no native HTML solution.
#### ARIA for Identifying Page Regions

Aria role attributes let you label different page regions, just like semantic tags.
<div role="banner"> site logo and name, etc. here </div>

<div role="search"> search functionality here </div>

<div role="navigation"> a list of navigation links here </div>

#### aria-labelledby attribute

This helps connect elements together. For example, a heading or label can describe a region, form field, or group of controls.
#### ARIA to Identify Headings

If you can't use real <h1>-<h6> tags because of a legacy system, you can use:
<div role="heading">Breaking News: Aardvark Species Learns Sign Language</div>

...but native heading tags are always better when possible.

## Conclusion

WCAG 1.3.1 is one of the most comment problem areas on the web, and one of the most important for real-world accessibility.
If your content has meaning in its layout, style, structure, or sounds, make sure those meanings are also baked into the code. That way, everyone, including assistive tech users, can understand the full story and move through your code with confidence.

## Related Success Criteria

