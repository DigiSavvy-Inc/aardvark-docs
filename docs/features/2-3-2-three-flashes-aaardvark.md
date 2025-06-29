# 2.3.2 Three Flashes - AAArdvark

[Operable](https://aaardvarkaccessibility.com/wcag-principle/operable/)

[Seizures and Physical Reactions](https://aaardvarkaccessibility.com/wcag-guideline/seizures-and-physical-reactions/)

WCAG 2.0, 2.1, 2.2
Level AAA

[View official documentation for WCAG 2.3.2](https://www.w3.org/WAI/WCAG22/Understanding/three-flashes.html)

# 2.3.2 Three Flashes

Flashing content must never exceed three flashes per second, without exceptions.

[Sensory](https://aaardvarkaccessibility.com/wcag-theme/sensory/) 

 

[Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Visual](https://aaardvarkaccessibility.com/wcag-disability/visual/) 

 

[Content](https://aaardvarkaccessibility.com/wcag-responsibility/content/), [Design](https://aaardvarkaccessibility.com/wcag-responsibility/design/) 

## What is it?

Nothing on the page should flash more than three times in any one-second period. It doesn’t matter how big or bright the flash is. If it flashes more than three times in a second, it fails.
Some web content, like videos, games, or animated graphics, can flash rapidly to grab attention or create excitement. But that kind of flashing can cause seizures or other serious health effects for users who are sensitive to flashing content.
### Comparing Flash Guidelines

WCAG 2.3.1 Three Flashes or Below Threshold allows some flashing if it meets specific conditions, like being dim enough or taking up a small portion of the screen.
Meanwhile, WCAG 2.3.2 Three Flashes doesn’t allow flashing more than three times per second, no matter how small or subtle. Even a single flashing pixel fails this rule.

## Why does it matter?

Fast flashing content doesn’t just cause seizures, it can also trigger migraines, nausea, dizziness, and other really unpleasant symptoms.
Some users are extremely sensitive. Even tiny flashing elements like a blinking button or a single pixel can be enough to cause harm, especially if they’re using screen magnifiers or high contrast settings.
This guideline helps keep digital spaces safe for everyone by eliminating rapid flashes, not just minimizing them.

## Who is affected?

People with photosensitive epilepsy or seizure disorders. People who are sensitive to flickering or fast motion, including those with migraines or vestibular disorders.

People with photosensitive epilepsy or seizure disorders can experience severe symptoms like seizures when exposed to flashing lights, even from small parts of a screen.
People who are sensitive to flickering or fast motion, including those with migraines or vestibular disorders, may feel dizzy, nauseous, or disoriented when viewing flashing or rapidly changing visuals.

## How to implement 2.3.2

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

### No Flashing Over 3 Times a Second

The best and only approach here is to flash nothing more than three times per second. Even small elements must follow this rule.
If you’ve got a flashing animation, slow it down. If you’re editing a video, cut or fade out overly rapid sequences. However, the safest bet is to avoid flashing entirely if you can.
If you're unsure whether your content meets the flash threshold, you can use tools like the Photosensitive Epilepsy Analysis Tool (PEAT) to check for violations. PEAT analyzes video and animations for flash frequency and intensity based on established seizure risk criteria.
A flash is defined by a pair of rapid, contrasting changes in brightness or color—like switching quickly from light to dark and back again. These are measured as flashes per second, and you must not exceed three.
Three examples of flashing “CALL!” buttons with phone icons, rapidly switching between high-contrast colors to demonstrate flashing sequences that could trigger seizures.
#### Flash vs. Blink

Blinking includes slower, repetitive changes that don't include high contrasts in color. These can be distracting, but not necessarily dangerous. See WCAG 2.2.2 Pause, Stop, Hide for rules on blinking.
A blinking element could be a notification light that turns on and off once every 5 seconds; it repeats, but it's slow and doesn't change colors.
Two examples of blinking UI elements, including notification bells with a “1” badge and pulsing “Sale” icons, showing slow, attention-grabbing animations that are distracting but not seizure-inducing.

## Conclusion

Flashing content can do serious harm, and not just to people with epilepsy. WCAG 2.3.2 sets a hard limit: no flashing more than three times per second, no exceptions.

## Related Success Criteria

