# 1.2.5 Audio Description (Pre-recorded) - AAArdvark

[Perceivable](https://aaardvarkaccessibility.com/wcag-principle/perceivable/)

[Time-based Media](https://aaardvarkaccessibility.com/wcag-guideline/time-based-media/)

WCAG 2.0, 2.1, 2.2
Level AA

[View official documentation for WCAG 1.2.5](https://www.w3.org/WAI/WCAG22/Understanding/audio-description-prerecorded.html)

# 1.2.5 Audio Description (Pre-recorded)

Actions, descriptions, and other important non-audio content in videos must be described in captions or a separate audio track.

[Sensory](https://aaardvarkaccessibility.com/wcag-theme/sensory/), [Wording](https://aaardvarkaccessibility.com/wcag-theme/wording/) 

 

[Visual](https://aaardvarkaccessibility.com/wcag-disability/visual/) 

 

[Content](https://aaardvarkaccessibility.com/wcag-responsibility/content/) 

## What is it?

Pre-recorded videos, with and without sounds, on web pages should include audio descriptions for any important visual information that’s not conveyed through dialogue. These descriptions narrate key visual elements, like actions, scene changes, and essential on-screen text, ensuring that people with visual impairments can fully understand what’s happening in the video.
The goal is to provide an audio alternative to visual details so that users who are blind or have low vision can grasp the content of pre-recorded videos as well.
A video player where the visuals of the current scene are doing the storytelling, and there’s no audio to help add context.

## Why does it matter?

Without audio descriptions, users who rely on sound to understand visual content might miss out on essential details. Audio descriptions provide context for visual information that isn't covered by the existing audio track, which can be crucial to understanding the whole story or the purpose of a video.
For example, in a video about a new art exhibit, the visuals might show the layout of the gallery and specific artworks being discussed. Without audio descriptions, a viewer who is blind wouldn’t know which artwork the narration refers to or how the gallery is arranged.
This is especially important for educational videos, documentaries, instructional content, or any media that contains significant visual storytelling.

## Who is affected?

People with low or limited vision. People who are blind. People with cognitive disabilities that make it difficult to process visual information.

People who are blind or have low vision rely on audio descriptions to interpret visual cues in videos. Without these descriptions, pre-recorded content becomes more challenging to follow, leaving them without crucial information.
People with cognitive disabilities may struggle with complex visuals, and quick scene changes can be overwhelming. Audio descriptions offer a more straightforward, verbal explanation of what’s happening on screen, making it easier for them to understand the content.

## How to implement 1.2.5

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

Unlike 1.2.3 Audio Description or Media Alternative, the only way to meet this success criterion is by providing an Audio Description. A text alternative is not enough to meet the Level AA standards. The only exception is talking head videos, which we’ll cover below.
### Audio Descriptions

An Audio Description is meant to add more context to the existing audio in the video or movie. Audio Descriptions are a second audio track added to a video to aurally add any information missing from the existing audio track. A good way to think of this is to imagine a commentator watching the movie alongside you and giving you information about the actions and information being shown on screen.
A video player where you can select the Audio Description soundtrack in various languages, such as English, French, and German, for a nature film where an aardvark is quietly eating from an ant pile.
 
#### Provide An Alternate Soundtrack or Movie That Offers Audio Descriptions

Many video players cannot simultaneously play multiple soundtracks or make use of an HTML5 <track> element. As the preferred option for Audio Descriptions, you can provide:

An alternative complete soundtrack that includes the audio description within it.
Or, an alternative video file altogether that has the audio description integrated into it.

Audio descriptions must respect the original audio; any additional information has to be added during pauses in dialogue or sound effects. This option can be limiting since descriptions may need to be squeezed between other audio elements.
The soundtrack alternative or video alternative can either be selected by the user or be the standard track or movie that everyone hears or sees.
#### Use the Track Element to Offer Audio Descriptions

An HTML5 <track> element can be used to add spoken audio descriptions of what’s happening in the video to be played alongside the video. This is also helpful when the visual component is not easily visible or accessible for users to interact with.
One thing to remember is that the audio description must be timed precisely to the action in the video. If there is not enough time to convey the audio to the user, it may be truncated.
#### Extended Audio Descriptions

Similar to the traditional audio description method described above, this technique is meant to provide a second version of the video content that includes added descriptions. However, this approach temporarily pauses in the original audio and video. This allows the narrator or commentator to include more information and give listeners a more thorough understanding of the imperceptible visual context.
### Static Text Alternative for Videos with Minimal Visuals ONLY

A static text document should only include a general description of the context of the environment, opening or closing credits, and any text that appears in the video and is not spoken.
This approach is meant to be used only when there is a single speaker and the visual surroundings are unchanging. Examples include videos that simply contain a “talking head,” such as press conferences or government announcements.
This is the only exception to this success criterion, for any other videos, an Audio Description is required.

## Conclusion

Providing audio descriptions for pre-recorded videos is essential for making visual content accessible to people who are blind or have low vision. These descriptions help ensure that all viewers, regardless of their ability to see, can fully understand and appreciate the video's content. While creating audio descriptions may require extra effort, it’s a critical step toward making media more inclusive.

## Related Success Criteria

