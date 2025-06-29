# 3.1.3 Unusual Words - AAArdvark

[Understandable](https://aaardvarkaccessibility.com/wcag-principle/understandable/)

[Readable](https://aaardvarkaccessibility.com/wcag-guideline/readable/)

WCAG 2.0, 2.1, 2.2
Level AAA

[View official documentation for WCAG 3.1.3](https://www.w3.org/WAI/WCAG22/Understanding/unusual-words.html)

# 3.1.3 Unusual Words

Jargon and figurative language is avoided, or, where not it’s possible, the words are defined or clarified the first time they’re used on a page.

[Wording](https://aaardvarkaccessibility.com/wcag-theme/wording/) 

 

[Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Visual](https://aaardvarkaccessibility.com/wcag-disability/visual/) 

 

[Content](https://aaardvarkaccessibility.com/wcag-responsibility/content/) 

## What is it?

Unusual words, including technical jargon or specialized wording, must include definitions and ways to learn more about the word. These definitions need to be included on the website itself to help avoid the interruptions of going to a dictionary website or searching for the meaning online.
This success criterion aims to ensure that users can read content and easily learn what unusual words mean in context.
This criterion applies only when understanding the word is necessary to understand the content. You don't need to define every uncommon word - just the ones that could confuse your users.
Puzzled person looking at a weather forecast that says “Raining Cats and Dogs,” with cats and dogs falling from clouds. This is a common idiom that means it's raining heavily, but the literal meaning makes no sense, especially to non-native speakers.

## Why does it matter?

Without identifying and defining unusual words or phrases, some people may struggle to read and understand content. This can be especially challenging for people with cognitive disabilities or those who speak different native languages.
Coming across an odd and uncommon word can throw a person off track, creating an interruption and causing them to open a separate tab to find out its meaning. By the time they get back, they could lose their place or get too frustrated to continue reading.

## Who is affected?

People with cognitive disabilities. People with a different native language. People with low vision.

People with cognitive disabilities may find it difficult to understand unfamiliar terms, idioms, or figures of speech without extra context or explanation.
People with a different native language might struggle with uncommon words, especially if they don't directly translate or have a different meaning in their language.
People with low vision often use screen magnifiers and may lose surrounding context when focused on a small portion of text. Clear definitions help avoid confusion when context is limited.

## How to implement 3.1.3

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

Ask yourself: Would most readers understand this without help? If you wouldn’t casually say the word to your audience without explaining it, define it.
Include a definition anytime you use:

Jargon: Words or phrases used by a specific group, profession, or industry - such as "UX audit" or "server-side rendering" - that may not be easily understood by people outside that group.
Idioms: Common phrases where the meaning isn’t literal, but understood culturally.
Specialized language: Terms that are specific to a subject area or profession, often requiring background knowledge to understand.

Highlighted word “cattywampus” shows a tooltip definition: Askew or out of order.
### Include Inline Definitions for Unusual Words

The easiest way to meet this criterion is to include definitions alongside the unusual word or phrase.
#### Define Terms at First Use

Give a definition the first time a word appears—unless the word is used differently in multiple places, in which case, define it every time.
This could include inline definitions where you place short definitions right in the sentence, like this:
 "Our app uses an API to pull real-time weather data from an external service. An API, or Application Programming Interface, lets software connect with other systems."
#### <dfn> Element

Use the <dfn> element to mark the spot where you define a term. Using <dfn> adds semantic meaning to your HTML and makes definitions more consistent and easier to recognize for assistive technology.
<p>A <dfn>cookie</dfn> is a small piece of data stored on the user's device to remember information.</p>
### Link to a Glossary or Description List

If you use several specialized terms, create a glossary page and link terms to it. Or create a description list section on the page and provide anchor links to easily find the definition.
<p>The<a href="#definition-1">aardvark</a> diet consists of ants and termites.</p>
<h3>Definitions:</h3>
<dl>
    <dt id="definition-1">Aardvark</dt>
    <dd>A nocturnal mammal native to Africa, known for its long snout and tongue used to eat ants and termites.</dd>
</dl>

#### <dl>, <dt>, and <dd> Elements

Use <dl>, <dt>, and <dd>elements to structure glossaries or term lists semantically. This structure is great for glossaries, FAQs, or any list of paired terms and explanations.

<dl>: Definition list is the wrapper for a group of terms and their definitions.
<dt>: Definiton term is the word or phrase you're defining
<dd>: Definiton description is the explanation or meaning of the term.

<dl>
    <dt>HTML</dt>
    <dd>The standard markup language for creating web pages.</dd>
    <dt>CSS</dt>
    <dd>A language used to describe the style of a document written in HTML.</dd>
</dl>

This can be visually output and styled:

HTML
The standard markup language for creating web pages.
CSS
A language used to describe the style of a document written in HTML.

### Use an Online Dictionary for Definitions

Instead of building your own glossary, you can add a feature to your web page that lets users search an online dictionary. This is especially useful for technical or specialized content. Just make sure the dictionary you link to provides accurate, accessible, and appropriate results.

## Conclusion

Including definitions right on the page means more people can follow along without breaking their focus to look something up. Making your writing easier to understand helps everyone, especially those with cognitive or language-related disabilities.

## Related Success Criteria

