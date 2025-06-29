# What is true accessibility? - AAArdvark

# What is true accessibility?

 

## (Beyond WCAG  and Legal Compliance)

 

![](https://aaardvarkaccessibility.com/wp-content/uploads/2023/05/4.d-Robust.png)

Share the Post: 

[Share on LinkedIn](https://www.linkedin.com/shareArticle?mini=1&url=https%3A%2F%2Faaardvarkaccessibility.com%2Fwhat-is-true-accessibility%2F&title=What%20is%20true%20accessibility%3F&source=https%3A%2F%2Faaardvarkaccessibility.com)[Share on X (Twitter)](https://twitter.com/intent/tweet?text=What%20is%20true%20accessibility%3F&url=https%3A%2F%2Faaardvarkaccessibility.com%2Fwhat-is-true-accessibility%2F&via=aaardvarka11y&related=aaardvarka11y)[Share on Reddit](https://www.reddit.com/submit?url=https%3A%2F%2Faaardvarkaccessibility.com%2Fwhat-is-true-accessibility%2F)[Share on Facebook](https://www.facebook.com/sharer/sharer.php?u=https%3A%2F%2Faaardvarkaccessibility.com%2Fwhat-is-true-accessibility%2F)[Share on Email](https://aaardvarkaccessibility.com/cdn-cgi/l/email-protection#18277a777c6125513d2a286a7d797c3d2a286c70716b3d2a2868776b6c3d2a2877763d2a285959596a7c6e796a733d2a2879767c3d2a286f79766c7d7c3d2a286c773d2a286b70796a7d3d2a28716c3d2a286f716c703d2a2861776d363d2a28507d6a7d3d2a2f6b3d2a286c707d3d2a28747176733d2b593d2a28706c6c686b3d2b593d2a5e3d2a5e7979796a7c6e796a73797b7b7d6b6b717a7174716c61367b77753d2a5e6f70796c35716b356c6a6d7d35797b7b7d6b6b717a7174716c613d2a5e3e3b282b20236b6d7a727d7b6c255b707d7b733d2a28576d6c3d2a284c70716b3d2a285959596a7c6e796a733d2a28597b7b7d6b6b717a7174716c613d2a285a74777f3d2a293d2a284f70796c3d2a28716b3d2a286c6a6d7d3d2a28797b7b7d6b6b717a7174716c613d2b5e)

True accessibility isn’t just about meeting legal requirements—it’s about real people. It’s about ensuring that anyone, regardless of who they are, can interact with your website with dignity. It’s about respecting the civil right of equal access to information and services. True accessibility means individuals with disabilities can navigate, interact with, and benefit from digital spaces just as easily as anyone else. While WCAG compliance is a good starting point, it’s not the final goal.

## The problem with a checklist mentality

WCAG guidelines are a crucial foundation for digital accessibility, but they just don’t capture everything. Think of WCAG as a baseline rather than a finish line. Meeting compliance requirements can ensure that your site meets a minimum level of accessibility, but true inclusivity requires going beyond those standards.

If we know one approach is more accessible, why do we need a rule to justify doing it?

You can follow WCAG to the letter and still not build an experience that is truly accessible to users, because accessibility is about more than technical compliance. Many organizations stop at compliance because they see accessibility as a legal safeguard rather than a user experience priority.

This mindset showed up recently in a conversation I had with someone asking about accessibility in a form. They wanted to use a heading instead of a fieldset and legend. I explained that while the two options might look visually similar, a legend is specifically designed to group related form fields and is announced correctly by screen readers, providing a significantly better experience for people who rely on assistive technology.

Their response? “Ok, thanks. But is it a WCAG violation?”

That question stopped me. Of course WCAG is important. But accessibility isn’t just about avoiding violations. It’s about creating the best possible experience for everyone.

If we know one approach is more accessible, why do we need a rule to justify doing it?

The best accessibility work happens when we go beyond the checklist. Instead of asking, “Is this a WCAG violation?”, we should be asking, “Is this the best experience for all users?”

## Where WCAG falls short

Even in areas where WCAG offers guidance, it doesn’t always go far enough. Here are a few examples where simply complying with WCAG success criteria won’t quite get you to true accessibility:

### Alternative text for images

WCAG requires that informational images have alternative text, but it doesn’t offer any guidelines on the length or quality of that text. Overly detailed or poorly written descriptions can be more of a hindrance than a help, especially when screen readers can’t pause or rewind that alt text easily.

### Icon-only buttons

WCAG allows icon-only buttons as long as they have text alternatives, but if users can’t recognize the icons or are unsure what they do, they miss out on functionality or may have a hard time making sense of a user interface.

### Color contrast exemptions

WCAG allows some elements to be exempt from color contrast requirements, such as logos and disabled form elements. Yet, these elements are still difficult to perceive for low vision users if they have insufficient contrast.

### Disabled buttons

Speaking of disabled buttons, in addition to being exempt from color contrast requirements, they often can’t receive focus and are therefore invisible to screen reader users. Keyboard-only users might also have a difficult time understanding why they can’t move focus to a disabled button.

### Switching color schemes

Alternating light-on-dark and dark-on-light sections of content on a single page is fine by WCAG standards as long as the text has sufficient contrast with whatever background color it happens to appear on. But switching color schemes like this can cause eye fatigue or make the page difficult to parse for users with low vision.

### Auto-rotating carousels

WCAG allows carousels that animate on their own as long as they can be paused or stopped, but offers no guidance on the timing of the animations. Screen readers can’t always keep up. Sometimes the screen reader is interrupted in the midst of reading a panel when the carousel advances to the next panel.

## What WCAG doesn’t cover at all

Some design and development choices can have a huge impact on users, yet WCAG does not address them at all. For example:

### Font size and readability

Believe it or not, there are no WCAG rules about minimum font size or typeface legibility. A site could use a tiny or overly stylized font and still pass.

### Content layout and readability

Dense blocks of unstructured text can be overwhelming, especially for users with cognitive disabilities. Structuring content with clear headings, bullet points, and concise paragraphs improves readability, but it’s not a WCAG requirement.

### QR codes

Alternative text that reads something like “Scan QR code” gives no context about what users are scanning. There are no WCAG requirements to describe where QR codes will take users.

### Chart and data accessibility

A chart might meet technical accessibility requirements, but without audio descriptions, ARIA instructions, or clear guidance on how to explore the data, screen reader users may struggle to understand or navigate it effectively. And while these enhancements can make a chart more usable, WCAG does not currently require them—leaving a gap between what passes and what works well for real users.

### Overuse or misuse of ARIA

Just adding ARIA attributes doesn’t make something accessible—especially if the roles or labels are outdated, misleading, or improperly used. Misapplied ARIA can interfere with screen reader behavior, confuse users, or override native HTML semantics in ways that hinder rather than help. It’s important to use ARIA thoughtfully and only when necessary, complementing a solid foundation of semantic HTML.

![Illustration of two people seated at a table using laptops. One is using a refreshable braille display and the other is using a screen reader.](https://aaardvarkaccessibility.com/wp-content/uploads/2023/05/1.-People-with-disabilities-working-on-their-laptops-300x200.png)
## Inclusive usability testing matters

Inclusive design doesn’t just benefit users with disabilities

Usability testing often focuses on the “general public,” but this can leave out a wide range of user experiences. If no one in the testing group uses a screen reader, relies on keyboard navigation, or has cognitive or motor challenges, the results may not reflect how accessible the site truly is.

People with disabilities are frequently underrepresented in usability studies, despite making up a significant portion of the population. As a result, accessibility barriers may go unnoticed and unaddressed. A site that feels intuitive to someone using a mouse and a screen might be frustrating for someone using assistive technology.

Inclusive design doesn’t just benefit users with disabilities. Accessibility makes the experience better for everyone. High-contrast text, clear headings, captions, and plain language improve usability across the board.

Truly inclusive usability testing includes participants with a variety of disabilities, ensuring your website works for as many people as possible.

## Understanding real-world accessibility

Real accessibility means considering the entire user experience, not just technical compliance. This requires engaging with people with disabilities, gathering feedback, and conducting usability testing that goes beyond automated scans.

### What real users experience

People with disabilities have diverse and sometimes conflicting needs. What improves usability for one user may create a barrier for another. That’s why accessibility work must be iterative, inclusive, and rooted in real user testing, not just the technical specs.

## Moving beyond compliance to true accessibility

Accessibility isn’t just about passing a test. It’s about making sure real people can use your site.

Accessibility isn’t just about passing a test. It’s about making sure real people can use your site.

If your accessibility efforts stop at WCAG compliance, you might be missing the bigger picture. By prioritizing usability and engaging with real users, you’ll not only meet compliance standards but also create a better, more inclusive digital experience for everyone.

To create genuinely accessible experiences, organizations should:

## AAArdvark can help!

AAArdvark goes beyond automated testing to provide the tools you need to identify, track, and fix accessibility issues that impact real users. Take accessibility beyond compliance.

Try AAArdvark for free today and start making real improvements that matter.

[Try AAArdvark for free](https://app.aaardvarkaccessibility.com/register)

No credit card required.

Share the Post: 

[Share on LinkedIn](https://www.linkedin.com/shareArticle?mini=1&url=https%3A%2F%2Faaardvarkaccessibility.com%2Fwhat-is-true-accessibility%2F&title=What%20is%20true%20accessibility%3F&source=https%3A%2F%2Faaardvarkaccessibility.com)[Share on X (Twitter)](https://twitter.com/intent/tweet?text=What%20is%20true%20accessibility%3F&url=https%3A%2F%2Faaardvarkaccessibility.com%2Fwhat-is-true-accessibility%2F&via=aaardvarka11y&related=aaardvarka11y)[Share on Reddit](https://www.reddit.com/submit?url=https%3A%2F%2Faaardvarkaccessibility.com%2Fwhat-is-true-accessibility%2F)[Share on Facebook](https://www.facebook.com/sharer/sharer.php?u=https%3A%2F%2Faaardvarkaccessibility.com%2Fwhat-is-true-accessibility%2F)[Share on Email](https://aaardvarkaccessibility.com/cdn-cgi/l/email-protection#c6f9a4a9a2bffb8fe3f4f6b4a3a7a2e3f4f6b2aeafb5e3f4f6b6a9b5b2e3f4f6a9a8e3f4f6878787b4a2b0a7b4ade3f4f6a7a8a2e3f4f6b1a7a8b2a3a2e3f4f6b2a9e3f4f6b5aea7b4a3e3f4f6afb2e3f4f6b1afb2aee3f4f6bfa9b3e8e3f4f68ea3b4a3e3f4f1b5e3f4f6b2aea3e3f4f6aaafa8ade3f587e3f4f6aeb2b2b6b5e3f587e3f480e3f480a7a7a7b4a2b0a7b4ada7a5a5a3b5b5afa4afaaafb2bfe8a5a9abe3f480b1aea7b2ebafb5ebb2b4b3a3eba7a5a5a3b5b5afa4afaaafb2bfe3f480e0e5f6f5fefdb5b3a4aca3a5b2fb85aea3a5ade3f4f689b3b2e3f4f692aeafb5e3f4f6878787b4a2b0a7b4ade3f4f687a5a5a3b5b5afa4afaaafb2bfe3f4f684aaa9a1e3f4f7e3f4f691aea7b2e3f4f6afb5e3f4f6b2b4b3a3e3f4f6a7a5a5a3b5b5afa4afaaafb2bfe3f580)

