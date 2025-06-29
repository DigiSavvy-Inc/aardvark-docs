# 1.4.2 Audio Control - AAArdvark

[Perceivable](https://aaardvarkaccessibility.com/wcag-principle/perceivable/)

[Distinguishable](https://aaardvarkaccessibility.com/wcag-guideline/distinguishable/)

WCAG 2.0, 2.1, 2.2
Level A

[View official documentation for WCAG 1.4.2](https://www.w3.org/WAI/WCAG22/Understanding/audio-control.html)

# 1.4.2 Audio Control

Auto playing audio that lasts more than 3 seconds can be turned down or stopped.

[Sensory](https://aaardvarkaccessibility.com/wcag-theme/sensory/) 

 

[Auditory/Hearing](https://aaardvarkaccessibility.com/wcag-disability/auditory-hearing/) 

 

[Code](https://aaardvarkaccessibility.com/wcag-responsibility/code/) 

## What is it?

WCAG 1.4.2 focuses on the ability to control audio on web pages. This can be in the form of audio-only content or also videos with audio. The overall goal is to give users the ability to raise or lower the volume independently on each piece of content that plays audio, especially if the track is longer than 3 seconds.

## Why does it matter?

Users who navigate web pages with screen readers can find it difficult to follow along with the speech output when audio tracks automatically play or when they can’t control the volume of the content alone.
Typically, screen readers use the system volume, and ideally, you’d want the content to have independent volume controls so that the user can adjust the different sound sources to their preference.

## Who is affected?

People with low or limited vision. People with reading or learning disabilities. People with cognitive disabilities.

People with vision impairments such as low or limited eyesight require the use of screen readers to navigate web pages. When proper audio controls are not provided for content, the entire web page can become unusable due to the conflicting sounds coming from the content and the screen reader output.
People with learning or cognitive disabilities also use screen readers and may find it difficult to focus on visual content (including text) when audio is playing.

## How to implement 1.4.2

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

To successfully meet WCAG 1.4.2 for Audio Controls, you’ll need to implement one of the following techniques.
### Play Sounds Only on User Request

The preferred technique requires that any audio included in the page only be played through the user’s manual request. The audio controls include all the expected functionality:

Play audio
Pause audio
Mute audio (if playing alongside a video)
Raise/Lower audio volume

### Automatic Sounds on Page Load

If a sound is automatically played when the page loads, make sure that the audio is no longer than 3 seconds. After 3 seconds, the sound coming from the content must either stop or you must provide sound controls according to the following technique.
### Providing Sound Controls Near the Beginning of the Page

If the page must auto-play audio for longer than 3 seconds, then a control towards the beginning of the page must be in place to give users the option to quickly mute the sounds. The control needs to be:

Operable via keyboard alone
Located early in the reading order
Clearly labeled as a control for the sounds playing
Able to raise or lower the volume for the specific audio track

Audio content is provided with controls to play and adjust volume. A separate link placed towards the top of the web page allows users to turn off the audio earlier in the page.

## Conclusion

Audio controls are very important to users who rely on screen reading assistive technology. Conflicting audio outputs can make an entire web page unusable and difficult to understand. This makes it crucial for content to provide a way for users to manage the audio for themselves.

## Related Success Criteria

