# 1.2.3 Audio Description or Media Alternative (Pre-recorded) - AAArdvark

[Perceivable](https://aaardvarkaccessibility.com/wcag-principle/perceivable/)

[Time-based Media](https://aaardvarkaccessibility.com/wcag-guideline/time-based-media/)

WCAG 2.0, 2.1, 2.2
Level A

[View official documentation for WCAG 1.2.3](https://www.w3.org/WAI/WCAG22/Understanding/audio-description-or-media-alternative-prerecorded.html)

# 1.2.3 Audio Description or Media Alternative (Pre-recorded)

Actions, descriptions, and other important non-audio content in videos must be described in captions, a separate audio track, or a text-based alternative like a screenplay.

[Sensory](https://aaardvarkaccessibility.com/wcag-theme/sensory/), [Wording](https://aaardvarkaccessibility.com/wcag-theme/wording/) 

 

[Visual](https://aaardvarkaccessibility.com/wcag-disability/visual/) 

 

[Content](https://aaardvarkaccessibility.com/wcag-responsibility/content/) 

## What is it?

WCAG 1.2.3 focuses on providing audio descriptions or media alternatives to synchronized media such as videos, TV shows, and movies. This success criteria also only applies to prerecorded media.
Please note that this success criterion is meant to help add context to media where certain elements are only expressed visually. This criterion should fill in any gaps in the audio that will help the user understand the video or movie.
For example, the video may include information that's only expressed visually, such as:

Actions, including any significant movement happening on the screen
Characters, including any significant actions or expressions a person makes on the screen
Scene or Background Changes
On-Screen Text or Graphics
Human non-dialogue, including sounds that humans make but require additional context to understand their meaning, such as laughter or off-screen voices
Sound effects that also require more description to help convey meaning, such as:

Nature sounds, including animal noises, weather-related noise (thunder, rain, wind)
Background noise, for example, fans whirring, computer typing, etc.
Music and its musical information
Sudden sounds like crashes, booms, scrapes, etc.

## Why does it matter?

For users with vision impairments or who have trouble processing visual information, being able to access the information communicated in videos or movies another way - either through audio descriptions or text means that they get access to the visual content they would otherwise not be able to enjoy.
Additionally, assistive technology can help take the suggestion in this success criterion further - a screen reader can read the full video content in the form of a screenplay aloud, or a refreshable braille display can turn the text content to braille.
A screenshot of a video where two people secretly and quietly exchange a note that says “Top Secret” on screen, captions read “silence”.

## Who is affected?

People who are blind or have limited vision. People with reading and learning disabilities.

Vision impairments can make it difficult to see and perceive visual details. Visual content can cause confusion when the audio doesn't thoroughly convey everything shown on screen. For video and movie content, you should provide an audio description that describes anything significant happening in the video that&rsquo;s not being covered by the audio, including who is doing what and any important information that is conveyed. You might also elect to provide a complete screenplay of the video for users to listen to separately.
Some people also have difficulty processing information presented visually and can benefit from having an alternative. Sometimes, listening to information on the actions or changes being presented visually can be helpful for comprehension.

## How to implement 1.2.3

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

1.2.3 presents two approaches to meet the criterion successfully. Implementing either option is perfectly acceptable. However, a screenplay or text alternative is preferred since it offers a much more complete representation of a video or movie.
### Audio Descriptions

An Audio Description is meant to add more context to the existing audio in the video or movie. Audio Descriptions are a second audio track added to a video to aurally add any information missing from the existing audio track. A good way to think of this is to imagine a commentator watching the movie alongside you and giving you information about the actions and information being shown on screen.
#### Provide An Alternate Soundtrack or Movie That Offers Audio Descriptions

Many video players cannot simultaneously play multiple soundtracks or make use of an HTML5 track element. As the preferred option for Audio Descriptions, you can provide:

An alternative complete soundtrack that includes the audio description within it.
Or, an alternative video file altogether that has the audio description integrated into it.

Audio descriptions must respect the original audio; any additional information has to be added during pauses in dialogue or sound effects. This option can be limiting since descriptions may need to be squeezed between other audio elements.
The soundtrack alternative or video alternative can either be selected by the user, or it can be the standard track or movie that everyone hears or sees.
A video player where you can select the Audio Description soundtrack.
#### Use the Track Element to Offer Audio Descriptions

An HTML5 track element can be used to add spoken audio descriptions of what's happening in the video to be played alongside the video. This is also helpful when the visual component is not easily visible or accessible for users to interact with.
One thing to remember is that the audio description must be timed precisely to the action in the video. If there is not enough time to convey the audio to the user, it may be truncated.
#### Extended Audio Descriptions

Similar to the traditional audio description method described above, this technique is meant to provide a second version of the video content that includes added descriptions. However, this approach temporarily pauses in the original audio and video. This allows the narrator or commentator to include more information and give listeners a more thorough understanding of the imperceptible visual context.
### Screenplay or Text Alternative

This approach requires writing a thorough and complete screenplay document that tells the same story and presents the same information as the video. This includes all the essential dialogue and actions as well as descriptions of the background, characters, text or graphics, and sound effects that are part of the story.
Screenplays typically follow a standardized format. Following the widely accepted format can also help users load the document into a screenplay reader to experience the content.
For example, here is a short screenplay of a video where a wildlife explorer discovers an aardvark:

EXT. (signifying an exterior shot) SUB-SAHARAN AFRICAN GRASSLAND — NIGHT
STEVE IRWIN, WILDLIFE EXPLORER, slowly walks across the grassy patch of land, a flashlight in his hand.
STEVE IRWIN
(excitedly) Oh crikey! Look at this beauty we have here!
An aardvark is seen in the short distance and is devouring an ant-pile. He crouches down and begins to approach the aardvark. The cry of a hyena is faintly heard in the background.
STEVE IRWIN
(whispers) Let’s get a closer look at the bugger. Notice the interestingly long tongue he uses to capture his tiny ant prey.

### Static Text Alternative

As opposed to an in-depth screenplay, a static text document has no important visual details described within the text. A static text document should only include a general description of the context of the environment, opening or closing credits, and any text that appears in the video and is not spoken.
This approach is meant to be used only when there is a single speaker, and the visual surroundings are unchanging. This makes a great and straightforward option for videos that simply contain a “talking head,” such as press conferences or government announcements.
### Handling Interactions Within Videos, TV Shows, or Movies

Certain videos call for interactivity from the viewer. Any links shared visually in these videos must also be included in the Audio Description, Screenplay, or Text Alternative.
To handle this, any links in the video must be listed alongside the video on the webpage or included in the screenplay and text alternative. And, if the user needs to return to the original video after reviewing the link, the link must have a back function available to get the user back to the same location in the video content.
Some examples of interactive videos:

YouTube videos where the person on screen directs the viewer to click the link placed on top of the video.
Promotional videos where they ask the viewer to visit the website URL shown on screen.
Company training videos where they ask you to move on to the next video in the tutorial series.

A video player where links are provided next to the video.

## Conclusion

Sites that meet WCAG 1.2.3 Audio Description or Media Alternative (Prerecorded) for their videos, TV shows, and movies make their content accessible for users with limited vision or learning disabilities. Using audio descriptions, screenplays, or text alternatives makes videos with imperceptible visual content more accessible by giving users an alternative way to experience the entire video without the need to see it physically.

## Related Success Criteria

