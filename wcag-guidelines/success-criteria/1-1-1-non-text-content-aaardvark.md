# 1.1.1 Non-text Content - AAArdvark

[Perceivable](https://aaardvarkaccessibility.com/wcag-principle/perceivable/)

[Text Alternatives](https://aaardvarkaccessibility.com/wcag-guideline/text-alternatives/)

WCAG 2.0, 2.1, 2.2
Level A

[View official documentation for WCAG 1.1.1](https://www.w3.org/WAI/WCAG21/Understanding/non-text-content)

# 1.1.1 Non-text Content

Images must have descriptive alternative text.

[Code and Labels](https://aaardvarkaccessibility.com/wcag-theme/code-and-labels/), [Sensory](https://aaardvarkaccessibility.com/wcag-theme/sensory/), [Wording](https://aaardvarkaccessibility.com/wcag-theme/wording/) 

 

[Auditory/Hearing](https://aaardvarkaccessibility.com/wcag-disability/auditory-hearing/), [Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Visual](https://aaardvarkaccessibility.com/wcag-disability/visual/) 

 

[Code](https://aaardvarkaccessibility.com/wcag-responsibility/code/), [Content](https://aaardvarkaccessibility.com/wcag-responsibility/content/) 

## What is it?

WCAG 1.1.1 focuses on non-text content and ensuring this content has a text alternative. Non-text content is anything on a website other than text, such as images, video, audio, and other visual and auditory content. People with vision impairment, hearing impairment, or information processing challenges can have trouble perceiving or understanding content shared through means other than text.
Text alternatives help make non-text content accessible to everyone. The information shared can be read separately by the individual, read aloud by screen readers, passed through refreshable braille displays, or translated into other languages.
Non-text content can take on many forms, including:

Informational visuals such as charts, diagrams, infographics
Audio recordings, such as podcasts
Prerecorded videos without audio, like animated gifs or memes
Prerecorded videos with audio, such as movies or TV shows
Live audio-only or video-only tracks
Images, photos, and animations
Decorative or aesthetic elements or images
Music and artwork
Visual user inputs, such as icon buttons or image maps
Online tests or quizzes where the questions and/or possible answers contain images or other non-text content
Captchas or other exercises to prove you are a human

Phew! That’s a lot to cover, but this success criterion aims to make all these forms of non-text content accessible. Due to the sheer variety of non-text content out there, this success criterion is quite large compared to some others. But we’ve done our best to break it down so that you can quickly and easily learn how to correctly manage the content that you’re working with.

## Why does it matter?

Non-text content can be a barrier for many different people, including anyone who has vision impairment, hearing impairment, or cognitive disabilities. In addition, it’s inaccessible for users who don’t understand the language the content is presented in.
Text alternatives offer a way for everyone to access the same content and information otherwise only provided through visual or auditory means.
Text alternatives also give the added benefit of making visual and auditory content searchable and provide the opportunity to repurpose content in new ways.

## Who is affected?

People with low or limited vision. People with hearing impairments. And people with reading and learning disabilities.

People who cannot perceive visual content will miss out on important information included in diagrams, videos, pictures, visual user inputs, etc. Providing a text alternative allows them to access the content with assistive technology, like a screen reader or refreshable braille display.
Likewise, people who are deaf or hard of hearing cannot perceive auditory content included in podcasts, movies, music, etc. A text alternative can enhance their experience by allowing them to read and learn about any additional context they may be missing out on.
Additionally, people who have difficulty processing visual or auditory content can benefit from text alternatives by providing multiple ways to explain the same content.

## How to implement 1.1.1

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

With the large variety of non-text content available, each piece of content will need to be treated differently to meet this success criterion. Look for the category of non-text content that best matches the piece of content you’re working with and start from there.
### Images

When adding images to pages, review the image and decide whether it’s important for understanding the overall context and if it helps convey information on the page.
Use the HTML alt attribute to give the image “alt text” that explains the meaning of the image and any text it contains. Alt text is meant to be short and sweet, and a good rule of thumb is to keep it around 125 characters long - typically about a sentence.
Because of its brevity, the alt text should focus on including information around the context of the image within the page and avoid including too much description that is not related to the context. Avoid including the words “image of” or “picture of” in the alt text, and avoid repeating the image’s caption.
#### Decorative Images

Decorative images enhance a page's aesthetic but don’t have a meaningful purpose or convey information. If the image is purely decorative, it does not require a text alternative.
In these cases, we can indicate that assistive technology should ignore decorative images. To do this, use an alt attribute for <img> elements and leave the alt text value blank or empty. Just note that excluding the alt attribute altogether is not the same as leaving it blank; it must be present and empty for assistive technology to ignore it.
<img src="decorative-pattern.png" alt="">

Another technique would be to use CSS to include decorative images since assistive technology can turn off CSS at the user’s request, and it’s common for these tools to ignore it by default. In this approach, the decorative images are added through the following CSS properties:

Background
Background-image
Content used alongside the before and after pseudo-elements
List-style-image

Still not sure whether an image needs alt text or not? Check out this super helpful alt decision-tree resource to help you decide.
An image that requires alt text, labeled "Aardvark named Aaron celebrating his birthday by wearing a blue party hat under blue and white banners," describes the scene. Below, abstract blue shapes are shown with empty double quotes as alt text to indicate the image is decorative.
### <a> Elements & Links

Links within the page need to include either text or non-text content with an alt attribute to describe the purpose of the <a> element since the URI of the destination is typically not descriptive enough. Although not required to meet the criterion, users also prefer to know the file type if the link opens a file, for example:
<a href="aardvark_care_guide.pdf">Aardvark Instructional Care Guide for Beginners (PDF)</a>

#### Linked Images

Links that contain both an image and text may leave the image’s alt attribute blank. This prevents screen readers from reading redundant information, as the purpose of the link is already clear from the accompanying text. However, if the images add more context or information, additional alt text can be added.
### Adjacent Linked Images and Text With the Same Destination

In an effort to reduce redundant links that point to the same destination or resource, it’s important to review linked images that are adjacent to linked text. This layout is pretty common across the web; for example, blog listings or product listings with a featured image next to a linked title where both point to the same page.
In these cases, you’ll need to make sure your HTML is set up so that the <img> element is contained within the <a> element. Once the image is contained, you can also apply alt text to it if it describes the image or adds context to the link.
This makes it easier for screen readers to navigate the page since it does not contain duplicate links to the same resource and doesn’t have to read aloud duplicate information.
Do:
<a href="https://dog.com/dancing-shoes">
    <img alt="Dog wearing dancing shoes with the text 'Buy Now' below" src="dancing_dog.png" />
    Buy Doggy Dancing Shoes Today!
</a>

Don't:
<a href="https://dog.com/dancing-shoes">
    <img alt="Dog wearing dancing shoes with the text 'Buy Now' below" src="dancing_dog.png" />
</a>
<a href="https://dog.com/dancing-shoes">
    Buy Doggy Dancing Shoes Today!
</a>

Product listing where the featured image depicts a dog wearing dancing shoes and the linked title says, “Buy Doggy Dancing Shoes Today”. A click icon is shown over the image and the title to convey that both elements are linked.
### Groupings Of Non-Text Content

In cases where you have a grouping of non-text content that is meant to convey information as a whole, you’ll need to work on three things:

Avoid providing duplicate text alternatives - avoid repetition when it’s redundant.
Provide a text alternative that provides context for the grouping of content as a whole unit and assign it to only one element in the group.
Lastly, mark elements within the grouping that are to be ignored by assistive technology when possible.

An example of this situation is a star-rating system on a web page. Each star element could be added as an individual image, and it may seem correct to label each image’s alt text as simply “star icon”.
However, the end user who uses the text alternative will get no context out of it since the information they’re receiving is repeating “star icon” info. Instead, the grouping as a whole can use alt text with the first image only. It could say “4 out of 5 stars”, while the other star image elements can leave their alt text blank.
A star rating system with alt text, “Rating of 4 of 5 stars”, applied to the first element; the remaining star icons use alt text, “” (empty double quotes).
### Emoji, Emoticons, ASCII Art

Emoji and anything made with ASCII characters, such as emoticons or ASCII art, can be confusing for screen readers because they read aloud the actual names and characters of the content.
Emojis have pre-defined names that don’t always match the overall content’s intended purpose. This is because emojis tend to have a social or cultural meaning behind them that doesn’t always match their literal meanings. For example, 🌝 (Full Moon Face) might not make much sense when read aloud, but for users who can see the emoji, it conveys irony or sarcasm.
Similarly, screen readers will read emoticons and ASCII art out loud, one character at a time. So something like >:) will be read as “greater than, colon, right parenthesis” instead of being interpreted as a mischievous smiley face.
Because of these challenges, emoji and ASCII art will need to include alt text or a text-based alternative to convey its meaning. This can be in the form of:

Containing the element in an HTML span tag with an aria-label
<span aria-label="mischievous smile" role="img">>:)</span>
If your emoji is included as an image, you can use the alt attribute
<img alt="mischievous smile" src="smiling_face_with_horns.png">
Including a description of the element in parenthesis immediately after
>:) (mischievous smile)

A poem where emoji are embellished throughout the text compared to the same poem with a screen reader’s interpretation of the emoji.
### Audio, Music, or Artwork

If you’re working with specific audio files or music and artwork, it’s necessary to include the given names of the material. This could mean including the name of the art piece and the artist. Or include the name of the sound file.
Other information you can include is the medium used for the art, the date it was created, and a brief description of what it depicts.
Music could include information about the genre, composer, date performed, link to lyrics, or a brief description of the lyrical content.
For example, a sound player includes an alternate text of “Take a Chance On Me, by ABBA”.
The artwork is displayed next to a short description, including the name, artist, medium, date, and brief overview of the content depicted.
### Image Maps

Image Maps are special types of images that include selectable regions within them. Alongside the image’s overall alt text description, each area must also provide its own alt attribute to describe its purpose.
A world map with clickable highlighted areas for the continents to learn more. Each continent has its own alt text, for example, “Learn about Asia”.
### Form Controls

If you’re working with a form on a site (for example, contact forms), each <input> element within the form needs to have an accompanying <label> element whose for attribute matches the <input> element's id attribute.
Usually, the <label> element for each form <input> is descriptive of what the form control requires, making it straightforward for users to understand the purpose of a field. Including the <label> element also makes the field's clickable area larger, making it easier for users with impaired motor control to click on the field.
A <label> element must be included with each form <input> element, with the exception of buttons and hidden fields. Here’s an example of the first name <input> field accompanied by the <label> element describing the purpose:
<label for="firstname">First name:</label>
<input id="firstname" name="firstname" type="text">

### CAPTCHAs

CAPTCHAs are typically visual or auditory tests on forms that help determine whether the user is a human or not. Because they include image-heavy or audio-related tasks, they are not typically accessible to people with visual or auditory impairments.
In order to make CAPTCHA accessible, the web page will need to:

Provide a text alternative that describes the purpose of the CAPTCHA and include instructions on where to find the alternate CAPTCHA
Provide an alternate CAPTCHA on the page that uses a different task-type approach; Including both visual and audio CAPTCHAS on the page makes sure that a user can complete one or the other if needed.

A side-by-side comparison of CAPTCHA with a visual task and one with an auditory task. Buttons are available in each CAPTCHA to switch between the modules.
### Complex Content

Complex content is anything that cannot be described using a short and sweet text alternative. If alt text is too lengthy, it can disrupt the reader’s experience as they read through a web page. Anything that strays too far from the topic or gives too much information can be distracting.
When working with complex content, provide long text alternatives so that a user can dig deeper into that piece of content at their own discretion.
Cases where a long description is necessary to describe longer and more complex pieces of content:

Informational visuals, such as charts, diagrams, and infographics
Audio recordings, such as podcasts
(For audio and video) Full-text alternatives are covered in WCAG 1.2.1 - Audio-only and Video-only (Pre-recorded)
Prerecorded videos without audio, like animated gifs
(For audio and video) Full-text alternatives are covered in WCAG 1.2.1 - Audio-only and Video-only (Prerecorded)
Prerecorded videos with audio, such as movies or TV shows
(For video) Audio Descriptions are covered in WCAG 1.2.3 - Audio Description or Media Alternative (Prerecorded)
Live audio-only or video-only tracks
Live audio is covered in WCAG 1.2.9 Audio-only (Live), and live captions for video are covered in WCAG 1.2.4 Captions (Live)

Long text alternatives are meant to thoroughly describe in detail what the content includes and how it fits into the larger context. The information you provide for long text alternatives tends to be detail-driven, where you focus on fully describing each portion or component of the non-text content.
The long text alternative should be able to substitute the non-text content. Replacing the non-text content with the short and long text alternatives would provide the same function and information.
When writing the long text description, ask yourself: What information is it presenting? And what is it doing here? However, be detailed about it - fill in all the visual, auditory, and contextual information about it.
#### Linking to Long Text Alternatives If Needed

When providing the long text description, it may not always be suitable to add it directly next to the non-text content since it may be too bulky for the page, for example. In those cases, you can also host the long description in another location, as long as the link to the description is either:

Listed right next to the non-text content that it’s describing
Listed in the short description of the non-text content

#### Brief Description Of Complex Content

When using the long text alternative approach, it’s also necessary to provide a brief description or short text alternative to summarize or just give the gist of a piece of content in addition to the longer text alternative.
For example, a large infographic may contain a lot of information and graphics that require a long text description to capture the entire piece’s full meaning. In this case, it would also be necessary to give the user an added short description to summarize the purpose, such as “Infographic Explaining the Benefits of Aardvark Rehabilitation.”
When writing the brief description, ask yourself: What information is it presenting? And what is it doing here?
Image with brief alt text, “Infographic covering the Big Business LLC business report for the third quarter of 2024”. A link to “Read full third quarter 2024 report for Big Business LLC” is listed next to the image.

## Conclusion

Wow, that was a lot to cover, am I right? While WCAG 1.1.1 is a more complicated success criterion to cover, it’s certainly worth it and will make all the difference for non-text content and making non-text content accessible to everyone regardless of disabilities. If it’s not text, make sure there’s a meaningful way for users to access the same information.

## Related Success Criteria

