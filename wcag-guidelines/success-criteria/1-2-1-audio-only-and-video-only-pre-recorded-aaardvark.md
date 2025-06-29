# 1.2.1 Audio-only and Video-only (Pre-recorded) - AAArdvark

[Perceivable](https://aaardvarkaccessibility.com/wcag-principle/perceivable/)

[Time-based Media](https://aaardvarkaccessibility.com/wcag-guideline/time-based-media/)

WCAG 2.0, 2.1, 2.2
Level A

[View official documentation for WCAG 1.2.1](https://www.w3.org/WAI/WCAG21/Understanding/audio-only-and-video-only-prerecorded.html)

# 1.2.1 Audio-only and Video-only (Pre-recorded)

Any audio-only content must also be conveyed in text. Any video content with no audio track must also be described in text, but could also be described with audio.

[Sensory](https://aaardvarkaccessibility.com/wcag-theme/sensory/), [Wording](https://aaardvarkaccessibility.com/wcag-theme/wording/) 

 

[Auditory/Hearing](https://aaardvarkaccessibility.com/wcag-disability/auditory-hearing/) 

 

[Content](https://aaardvarkaccessibility.com/wcag-responsibility/content/) 

## What is it?

WCAG 1.2.1 focuses on two types of prerecorded media - audio-only and video-only. Prerecorded just means that the content isn’t live - it’s been recorded previously and is being played back. 
Just as it sounds, audio-only media refers to media that is just sound without visuals. This includes audio recordings of:

Speeches
Press conferences
Podcasts
Radio shows and the like.

Video-only media refers to video content that contains just visuals without sound. This includes:

Silent movies
Screen recordings
Memes
Simple instructional videos and the like.

This success criterion requires that you provide a way for users who cannot perceive audio-only content or video-only content to access the information being communicated in the media. For both video-only and audio-only content, the preferred alternative is a text transcript. Still, you might also consider captions for audio-only content or an audio description for video-only content.

## Why does it matter?

For users who are d/Deaf, hard of hearing, or who have trouble processing audio information, being able to access a text transcript or captions means they can perceive the information being shared in audio-only content. Otherwise, they would miss out entirely.
Likewise, for users with vision impairments or who have trouble processing visual information, being able to access the information communicated in video-only content another way - either a text transcript or an audio description means that they get access to the content they would otherwise not be able to enjoy.
Additionally, assistive technology can help further - a screen reader can read the text aloud, or a refreshable braille display can turn the text content to braille. Soon, technology will help us to turn text transcripts into sign language for users to understand as well.
Let’s take a peek at what seemingly looks like a nature video.
A silent video of foxes playing around
This is pretty neat - but to users who cannot perceive the video, there’s no information being communicated at all. Without any text cues, there is no access to the information in the video.
A video depicting foxes playing with a text transcript describing the video right next to it.
Now, this is more like it. WCAG 1.2.1 seeks to ensure that users with visual and hearing impairments can absorb and identify content and information without difficulty. This guideline is set in place to ensure all users can access the content in general.

## Who is affected?

People with low or limited vision, hearing impairment disabilities, and reading and learning disabilities.

People with low or limited vision, hearing impairment disabilities, and reading and learning disabilities.
Vision impairments can make it difficult to see and perceive visual details. Video-only content is quite useless for someone who cannot see it. For video-only content, you should provide a text transcript that describes what is happening in the video, including who is doing it and any important information that is conveyed. You might also elect to provide an audio description of the video for users to listen to.
Hearing impairments make it difficult to hear and understand audio-only media. Someone with a hearing impairment might want to enjoy a popular podcast but might have trouble understanding what the hosts are saying or be unable to hear them at all. By providing a text transcript of the show, including who is talking, laughing, etc., anyone can enjoy the podcast's content, regardless of their hearing capacity.
Some people also have difficulty processing information presented visually or aurally and can benefit from having an alternative - sometimes listening while reading along with a text transcript is helpful for comprehension. Other times, just reading the text transcript on its own is helpful.
A podcast player without a button or link for text transcripts.
Media that doesn’t provide any alternative, such as text or audio cues, diminishes the experience for the user on the site. There needs to be some kind of alternative for users to understand the information being conveyed.

## How to implement 1.2.1

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

### Do provide an alternative for prerecorded audio-only content

With audio-only presentations, information is conveyed via dialogue and sounds. For those with hearing impairments, they could miss out on some details and information without any accessible alternative. In this case, a complete text transcript is the best option to ensure they’re not missing anything and are receiving the information being shared.
Captions are another way to communicate information for audio-only content. However, it would be best to include an option for both transcripts and captions. This will allow the user to select which method they prefer; some may prefer to read at their own speed via transcripts or follow along with the captions provided as the audio is being relayed.
The transcripts and captions should not only include dialogue but also any sound, even background noise, that is part of the story.
Good: This is a podcast listing two speakers talking back and forth. It offers a text transcription of what is being said, as well as timestamps.
### Do provide an alternative for prerecorded video-only content

Video-only presentations should always include an alternative for those with visual impairments. Information is passed through various ways, including animation, graphics, background, expressions, actions, etc. A complete text transcript is the best option for conveying the same information in a different way. The text transcript should include descriptions of what’s happening, who’s doing it, any graphics or charts that might communicate information, and any instructions that might be shared in the video.
A good example of this would be a quiet animation that displays how to brew the perfect cup of tea with a set of visual instructions. For any visually impaired user, this would be difficult; there must be a text transcript detailing the steps taken and any critical detail relevant to the subject matter so that they understand what’s happening.
Optionally, audio descriptions can be included to ensure important information is communicated to users who might prefer to listen to the information rather than read it. However, the advantage of a text transcript is that assistive technology can access it easily - meaning a screen reader can read it aloud, or a refreshable braille display can convert the text to braille.
Good: A quiet animation that displays how to brew a perfect cup of tea, a text transcript is included with written brewing steps and instructions.
### Use the track element to offer audio descriptions

In addition to offering audio transcripts, the HTML5 <track> element can be used to add spoken audio descriptions of what’s happening in the video to be played alongside the video. This is also helpful when the visual component is not easily visible or accessible for users to interact with.
One thing to remember is that the audio description must be timed precisely to the action in the video. If there is not enough time to convey the audio to the user, it may be truncated.
<video controls>
    <source src="aardvark_in_the_wild.mp4" type="video/mp4" />
    <source src="aardvark_in_the_wild.ogg" type="video/ogg" />
    <track src="aardvark_in_the_wild_descriptions.vtt" kind="descriptions" srclang="en" label="English Audio Descriptions" />
</video>

Good: A video with an audio description button, e.g. “AD” and a volume bar for the audio description.

## Conclusion

Meeting the 1.2.1 criterion for prerecorded audio-only and video-only content will ensure that your content is accessible to all users without frustrating and confusing them. Following these guidelines will allow everyone to perceive, understand, and focus on communicated information.

## Related Success Criteria

