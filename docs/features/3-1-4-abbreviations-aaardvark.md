# 3.1.4 Abbreviations - AAArdvark

[Understandable](https://aaardvarkaccessibility.com/wcag-principle/understandable/)

[Readable](https://aaardvarkaccessibility.com/wcag-guideline/readable/)

WCAG 2.0, 2.1, 2.2
Level AAA

[View official documentation for WCAG 3.1.4](https://www.w3.org/WAI/WCAG22/Understanding/abbreviations.html)

# 3.1.4 Abbreviations

Acronyms and shortened words should be avoided when possible. When they are used, they must be defined the first time they appear on a page.

[Wording](https://aaardvarkaccessibility.com/wcag-theme/wording/) 

 

[Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Visual](https://aaardvarkaccessibility.com/wcag-disability/visual/) 

 

[Content](https://aaardvarkaccessibility.com/wcag-responsibility/content/) 

## What is it?

Abbreviations must include ways to learn about the shortened word and its meaning. This could include showing the whole word, linking to a definition, or offering a dictionary search.
Abbreviations can inlcude acronyms, initialisms, and shorted words. This success criterion ensures that people can understand the content without needing to guess or look things up elsewhere.

## Why does it matter?

Not everyone knows what abbreviations like "JS," "CMS," or "WCAG" mean. Some abbreviations look like regular words or sound like other terms, which makes them harder to interpret.
If a reader doesn't recognize an abbreviation, they may need to pause their reading, open another tab, and search for a definition. That interruption can cause confusion, furstration, or even lead someone to abandon the content altogether.
Clear definitions help keep readers focused and make content easier to understand for a wide audience.

## Who is affected?

People with cognitive disabilities. People with a different native language. People with low vision.

People with cognitive disabilities may find abbreviations harder to decode, interpret, or remember, especially when they appear without explanation.
People with a different native language may not recognize abbreviations that don’t translate clearly, and some may carry entirely different meanings in other cultures or languages, making the intended message unclear.
People with low vision who use screen magnifiers typically view only a small portion of the screen at a time. This limited view can cause them to miss the surrounding context that explains an abbreviation, making it harder to understand what it means.

## How to implement 3.1.4

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

### Provide the Full Form at First Use

The easiest way to meet this requirement is to write the full term the first time it appears on a page, followed by the abbreviation in parentheses or vice versa.
Example:
"The World Wide Web Consortium (W3C) is responsible for publishing web standards."
Or:
"The W3C (World Wide Web Consortium) publishes web standards."
You only need to define the abbreviation once per page, as long as it always means the same thing. If it's used with different meanings, define it each time.
#### Be Careful with Confusing Abbreviations

Abbreviations can be tricky because they can change between different contexts and can derive from other languages.
If the context changes, make sure to include the new expanded form definition.
For abbreviations borrowed from other languages, like Latin, you must also explain what they mean in plain language, rather than just showing the original expanded form.
Some abbreviations are trickier than others:

"St." could mean Street, Saint, or State, depending on context.
"MVP" – Could mean Most Valuable Player, or Minimum Viable Product in tech/startups.
"E.g." is short for exempli gratia in Latin, which means "for example."

Dr. used for both Doctor and Drive, showing different meanings of the same abbreviation.
### Link to a Glossary or Description List

If your content uses a lot of abbreviations, create a glossary. Just make sure the terms are easy to find and link to them when possible. Or create a description list section on the page and provide anchor links to find the full form of the abbreviations.
<p>Our platform supports <a href="#definition-1">CMS</a>
<h3>Definitions:</h3>
<dl>
    <dt id="definition-1">CMS</dt>
    <dd>Content Management System: software that helps people create, manage, and modify content on a website without needing to code.</dd>
</dl>

#### <dl>, <dt>, and <dd> Elements

Use <dl>, <dt>, and <dd>elements for semantically meaningful definitions of multiple terms. This structure is great for glossaries, FAQs, or any list of paired terms and explanations.

<dl>: Definition list is the wrapper for a group of terms and their definitions.
<dt>: Definiton term is the word or phrase you're defining
<dd>: Definiton description is the explanation or meaning of the term.

 
<dl>
    <dt>HTML</dt>
    <dd>HyperText Markup Language: The standard markup language for creating web pages.</dd>
    <dt>CSS</dt>
    <dd>Cascading Style Sheets: A language used to describe the style of a document written in HTML.</dd>
</dl>

This can be visually output and styled:

HTML
HyperText Markup Language: The standard markup language for creating web pages.
CSS
Cascading Style Sheets: A language used to describe the style of a document written in HTML.

Sentence showing GPS linked to a glossary entry that defines it as Global Positioning System.
### Use an Online Dictionary for Definitions

Instead of building your own glossary, you can add a feature to your web page that lets users search an online dictionary. This gives users a built-in way to look them up. This could be a search box connected to a trusted online acronym or abbreviation dictionary.
Just make sure the dictionary you link to gives accurate results. This method helps users understand jargon, abbreviations, or uncommon words without leaving your site entirely.

## Conclusion

Abbreviations are helpful—but only when everyone knows what they mean! Give readers the full form, add tooltips, or offer a way to look them up. It's a small step that makes a big difference in helping people stay focused and understand your content.

## Related Success Criteria

