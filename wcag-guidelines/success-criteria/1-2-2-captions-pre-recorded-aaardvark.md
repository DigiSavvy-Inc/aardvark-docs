# 1.2.2 Captions (Pre-recorded) - AAArdvark

[Perceivable](https://aaardvarkaccessibility.com/wcag-principle/perceivable/)

[Time-based Media](https://aaardvarkaccessibility.com/wcag-guideline/time-based-media/)

WCAG 2.0, 2.1, 2.2
Level A

[View official documentation for WCAG 1.2.2](https://www.w3.org/WAI/WCAG22/Understanding/captions-prerecorded.html)

# 1.2.2 Captions (Pre-recorded)

The audio in videos must be captioned.

[Sensory](https://aaardvarkaccessibility.com/wcag-theme/sensory/), [Wording](https://aaardvarkaccessibility.com/wcag-theme/wording/) 

 

[Auditory/Hearing](https://aaardvarkaccessibility.com/wcag-disability/auditory-hearing/) 

 

[Content](https://aaardvarkaccessibility.com/wcag-responsibility/content/) 

## What is it?

WCAG 1.2.2 provides details on including captions with prerecorded media. Prerecorded media just means that the content isn’t live—it’s been recorded previously and is being played back on the page. This success criterion refers to any prerecorded media that contains sounds, including both audio-only media and video with sound.
Audio-only media includes podcasts, radio shows, recordings of speeches or press conferences, and the like. Videos with sound include tutorial videos, movies, music videos, commercials, and the like.
Captions can include sounds such as:

Dialogue, including information on who is speaking and their location
Human non-dialogue, including sounds that humans make but they’re not necessarily speaking, such as laughter or coughing
Meaningful sound effects such as nature sounds, background noise, and music and its musical information

The one exception to providing captions is for audio-only tracks or videos that exist as media alternatives for text-based content. For example, if an audio track is added to your webpage to describe an image, audio-only media would not need captions.
### Captions vs Subtitles

Captions and subtitles are not equal. Subtitles provide only the dialogue and don’t include essential information on the other sounds in the audio-only track or video.
Subtitles are also commonly used for translation purposes as opposed to captions, which are exclusively meant to enhance accessibility. However, closed captions can be translated relatively easily as well!
### Captions vs Transcriptions

Captions are timed with the audio or visual tracks and are usually presented alongside or on top of the video. A transcription is more like a script of all of the dialog from the audio or video content and is usually a plain text file or a really simple HTML file that can be downloaded and viewed separately.

## Why does it matter?

For users who are d/Deaf, hard of hearing, or who have trouble processing auditory information, being able to access captions means they can perceive the information being shared in audio-only or video content. Otherwise, they could miss out on important information communicated through sound.

## Who is affected?

People with hearing impairment disabilities and reading and learning disabilities.

Hearing impairments make it difficult to hear and understand audio-only or video media. Someone with a hearing impairment might want to enjoy a popular podcast but might have trouble understanding what the hosts are saying or be unable to hear them at all. By providing captions of the show, including who is talking, laughing, etc., anyone can enjoy the podcast's content, regardless of their hearing capacity.
Some people also have difficulty processing information presented aurally and can benefit from having an alternative - sometimes listening while reading along with captions is helpful for comprehension.

## How to implement 1.2.2

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

Implement one of the techniques listed below to meet success criterion 1.2.2 for Captions (Prerecorded).
### Providing closed captions

Closed captions include descriptions of the text and sounds embedded in the media player. This is done by uploading a captions information file alongside the video or audio track to the designated media player. Closed captions are typically hidden in the media player unless the user manually turns them on.
Closed captions are the preferred captioning method because they offer a lot of benefits to the users who need them:

The captions' font color, background color, typeface, font size, and positioning can be adjusted by the end user to suit their needs or preferences.
Closed captions can easily be translated into other languages
Closed captions can be accessed, viewed, and/or downloaded separately from the video, and the user is not required to watch the video or use the video player to understand the content
Closed captions are searchable.

Example of closed captions and their settings in a media player, options to choose the typeface, colors, and language are shown.
#### Note on Auto-Generated Closed Captions

Recent technology makes closed captioning easier by automatically generating captions to accompany the audio or video. But beware: If you’re using a media player that offers this functionality, please make an effort to review and edit the captions generated and make sure they thoroughly describe the speaker’s dialogues, information, and any other details about the sounds in the video that are important to convey.
These auto-captioning features are far from perfect, and it’s best to make sure the captions are actually helpful from a non-hearing person’s perspective rather than just ticking off the box to meet the “caption criteria”.
### Providing open (always visible) captions

Open captions include descriptions of the text and sounds embedded directly into the video. This is done during the video editing process; the video editor will need to add the captions to the video's visuals. Because they’re edited directly onto the video visuals, they’ll always be visible to the user.
Open captions are helpful because they don’t require any special support from video players or any added steps by the user to see them. This makes it great for simple online video players that don’t offer a captioning feature or to help users who may not know how to turn on captions on media players.
In direct contrast to closed captions, the downsides to open captions include:

The font color, background color, typeface, font size, and positioning of the captions cannot be adjusted by the end user to suit their needs or preferences. The video editor makes these visual choices for the captions.
Closed captions cannot be easily translated into other languages
Closed captions cannot be accessed, viewed, and/or downloaded separately from the video unless you provide a separate text file that includes all the captions used in the video.
Closed captions are not searchable.

Video editors opting to use open captions in their videos must also adhere to other success criteria relating to the WCAG Perceivable principle and Distinguishable guidelines to make the captions easy to read and maintain accessibility:

WCAG 1.4.1 Use of Color (Level A)
WCAG 1.4.3 Contrast (Minimum) (Level AA)
WCAG 1.4.6 Contrast (Enhanced) (Level AAA)
WCAG 1.4.12 Text Spacing (Level AA)

Because of this technique's inherent nature, open captions cannot be used with audio-only content. Please use closed captions for audio-only media instead.
Example of open captions edited directly into the video. Since the text is embedded in the video itself, you cannot edit the typeface, colors, or language.
### Tips on Captioning

Captions can simplify the spoken text to make it easier to read or to avoid users having to read at high speeds. Using simplified language doesn’t invalidate the captions.
When creating captions for audio or video files that include music, in addition to capturing dialog and lyrics verbatim, you could also identify non-vocal musical information such as the music by title, feeling, and composer or musician name. For example, [dramatic musical flourish] or [“Africa” by Toto plays].
Captions should also include human non-dialogue sounds if they can help convey meaning, such as [evil laughing], [heart throbbing], [quiet whimpering], or [laughing], as well as otherworldly sounds, such as [radio tuning], [monkey calls in the distance], or [rain gently hitting the window].
A video using both musical and human non-dialogue captions. They say, "[laughing]["Fernando" by ABBA plays]".

## Conclusion

Sites that meet WCAG 1.2.2 Captions for their prerecorded media make their video and audio tracks accessible for users with hearing impairments or learning disabilities. Captions make videos with sound and audio tracks more accessible by giving users an alternative way to experience the content without the need to hear or listen.

## Related Success Criteria

