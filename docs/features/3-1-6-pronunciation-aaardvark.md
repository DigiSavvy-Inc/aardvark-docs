# 3.1.6 Pronunciation - AAArdvark

[Understandable](https://aaardvarkaccessibility.com/wcag-principle/understandable/)

[Readable](https://aaardvarkaccessibility.com/wcag-guideline/readable/)

WCAG 2.0, 2.1, 2.2
Level AAA

[View official documentation for WCAG 3.1.6](https://www.w3.org/WAI/WCAG22/Understanding/pronunciation.html)

# 3.1.6 Pronunciation

If a word can be pronounced more than one way, and each way has a different meaning, the meaning is clarified to avoid ambiguity.

[Wording](https://aaardvarkaccessibility.com/wcag-theme/wording/) 

 

[Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Visual](https://aaardvarkaccessibility.com/wcag-disability/visual/) 

 

[Content](https://aaardvarkaccessibility.com/wcag-responsibility/content/) 

## What is it?

Sometimes, how you say a word changes what it means. This criterion is all about helping users figure out the right pronunciation when it's the only way to know the word’s meaning.
You only need to provide pronunciation help if someone wouldn’t be able to figure out the meaning without it. This situation is rare and typically applies only when a word's meaning is ambiguous and can't be clarified by context or other visual cues. This could mean adding a pronunciation guide, linking to a sound file, or using HTML tools like the <ruby> element.
Here are some examples of English words with double meanings:

Lead (a metal) vs. lead (to guide).
Bass (type of fish) vs. bass (a musical instrument)
Wind (moving air) vs. wind (to twist or turn)

This issue is especially common in languages like Japanese and Chinese, where a single written character can have multiple pronunciations and meanings depending on the context.
Table showing “Wind,” “Live,” and “Tear” with two pronunciations and meanings each, using text and icons to clarify differences.

## Why does it matter?

This success criterion applies to homographs—words that are spelled the same but pronounced differently, depending on their meaning. Words like bass, tear, or wind can be confusing, especially when there’s no hint about how they’re supposed to be read. This criterion is especially relevant for logographic languages like Chinese or Japanese, where a single written character may have multiple valid pronunciations.
If the meaning of the sentence depends on saying the word correctly, users who can’t hear or see that pronunciation clearly are at a disadvantage. This includes screen reader users, people with cognitive or reading disabilities, and anyone unfamiliar with the word. A mispronunciation can make the whole sentence unclear or misleading.
When users can’t rely on visual context or experience to understand a concept, they need a backup, like a pronunciation guide, sound file, or glossary entry, to help them understand what the content is actually saying.

## Who is affected?

People who are blind or low vision. People with reading or cognitive disabilities. People learning a language.

People who are blind or have low vision who use screen readers can run into issues where a mispronunciation makes the sentence confusing, mainly if the meaning depends on how the word is said, like with homographs or unfamiliar names.
People with reading or cognitive disabilities may already struggle with decoding or processing language and can get stuck if the pronunciation adds more ambiguity.
People learning a language can find it challenging when words are spelled the same but sound different because they may not yet know the alternate pronunciations or how context affects meaning.

## How to implement 3.1.6

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

You don’t need to explain every word with a double meaning. Only when pronunciation is the key to understanding.
### Show How to Say It

Give users a way to learn the pronunciation when they need it. This doesn’t mean every word needs help; it is just the ones whose meaning depends on how they are said or the context.
Instead of:
“They spotted a bass in the water.” (Could be a fish or a musical instrument.)
Try:
“They spotted a bass (rhymes with ‘class’) in the water.”
### Use <ruby> Annotations

In Japanese and some other languages, ruby text is used to show pronunciation. It sits above the word and is easy for screen readers and sighted users to pick up.
When using ruby annotations to show pronunciation, each <rb> (base text) should be paired with an <rt> element that contains the pronunciation. Most modern browsers support <ruby>, but fallback tags like <rp> ensure the pronunciation is still visible if not.
Example using HTML:
<ruby>lead<rp>(</rp>
<rt>leed</rt>
<rp>)</rp>

The output would then look like this, where the pronunciation information is shown above or below the word it's annotating. Or, if the <ruby> markup is not supported on the browser, it will use the fallback parentheses.
Comparison of how pronunciation is shown using ruby text versus fallback parentheses in unsupported browsers.
### Link to Sound Files

Let users click on a play button to hear the word. This can be especially helpful for unusual names, technical terms, or foreign phrases.
If taking this approach, make sure the audio player itself is accessible. That means:

It works with a keyboard.
It has good color contrast.
It's labeled clearly so screen reader users know what it's for.
There's also a text version of the pronunciation (like "reed" for "read").

For more information on accessible media players, check out our articles on 1.2.1, 2.1.1, 4.1.2, 1.4.11, and 2.4.6.
An interactive paragraph using homographs with pronunciation play buttons and an audio player for full narration.
### Add Pronunciation to Glossaries

If your site already has a glossary, include the pronunciation information alongside the definitions. Then, link words with double meanings in your content to the glossary entry.
### Use Diacritical Marks

In some languages, diacritical marks—like accents, tildes, or umlauts—are essential for showing how a word is pronounced. They can change both the sound and meaning of a word.
For example, in Spanish, "si" means "if" and "sí" means "yes."
If your site includes content with diacritical marks, be mindful that these are essential to pronunciation and meaning in many languages. Where appropriate, you can offer options to simplify or highlight them, but never remove them entirely.
Visual comparison of English words with and without diacritical marks: resume vs. résumé and expose vs. exposé.

## Conclusion

When pronunciation changes meaning, don’t leave users guessing. A quick tip, sound clip, or visual cue can go a long way in making sure your content is clear, especially for people using assistive tech or learning your language.

## Related Success Criteria

