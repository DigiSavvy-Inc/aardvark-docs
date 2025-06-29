# 2.3.3 Animation from Interactions - AAArdvark

[Operable](https://aaardvarkaccessibility.com/wcag-principle/operable/)

[Seizures and Physical Reactions](https://aaardvarkaccessibility.com/wcag-guideline/seizures-and-physical-reactions/)

WCAG 2.1, 2.2
Level AAA

[View official documentation for WCAG 2.3.3](https://www.w3.org/WAI/WCAG22/Understanding/animation-from-interactions.html)

# 2.3.3 Animation from Interactions

Animations triggered by interactions like button presses can be turned off.

[Sensory](https://aaardvarkaccessibility.com/wcag-theme/sensory/) 

 

[Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Visual](https://aaardvarkaccessibility.com/wcag-disability/visual/) 

 

[Code](https://aaardvarkaccessibility.com/wcag-responsibility/code/), [Design](https://aaardvarkaccessibility.com/wcag-responsibility/design/) 

## What is it?

If the animation isn't critical to understanding the content or how something works, the user must be able to turn it off. Or, the animation should be removed by default.
WCAG 2.3.3 helps prevent unnecessary effects from happening when a person interacts with a website. Animations that are triggered after someone clicks, scrolls, or hovers can make people feel sick or dizzy.
This could include motion effects, like:

Parallax backgrounds where the foreground moves at a different pace than the background when scrolling
Bouncy or zooming transitions between pages or sections
Sliding content or flipping cards when the mouse hovers
Accordion sections open and close when clicked
Loading spinners when new content loads

### Comparing WCAG 2.2.2 Pause, Stop, Hide

WCAG 2.2.2 Pause, Stop, Hide covers stuff that moves on its own without user interaction. Meanwhile, WCAG 2.3.3 Animation from Interactions is relevant when the animation is caused by something the user does.

## Why does it matter?

Some people have vestibular disorders, which means motion effects can literally make them sick. Their symptoms can range from dizziness, migraines, nausea, or needing to lie down for a while. If your site is having the user trigger all kinds of animations for no reason, you might be harming real users.
Even minor extras like a zoomy fade or sliding in text during a scroll can break focus or ruin the experience for someone who's really sensitive to motion. Without the ability to opt out of motion effects, people might get seriously sick to access the information they need online.
 
A person holding a phone and looking dizzy, with spinning stars and swirls around their head. On the phone screen, a website is full of motion effects like swirling icons, a spinning refresh symbol, and animated lines.

## Who is affected?

People with vestibular disorders. People easily distracted by movement. People prone to migraines or motion sickness.

People with vestibular disorders may feel dizzy, nauseated, or disoriented when exposed to motion effects triggered by scrolling, clicking, or hovering.
People easily distracted by movement can struggle to focus or read content when animations keep pulling their attention away.
People prone to migraines or motion sickness might experience headaches, nausea, or need to stop using the site altogether if motion effects are too intense or unexpected.

## How to implement 2.3.3

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

### Respect Reduced Motion Settings

Use the prefers-reduced-motion CSS media query to check if someone has asked for less animation. If they have, make sure your site's animations respect those settings.
Most modern devices and browsers support the prefers-reduced-motion setting, which tells websites to limit or turn off motion effects.
Users can enable this setting in their browser or operating system's accessibility preferences. Usually named "Reduce Motion" or "Remove Animations".
When it’s on, your CSS using @media (prefers-reduced-motion: reduce) will take effect and reduce or remove animations automatically.
@media (prefers-reduced-motion: reduce) {
* {
animation: none !important;
transition: none !important;
}
}

Not all animations are created with CSS - some happen through JavaScript. To make sure your interactive motion effects respect users' preferences, add a quick check to your JavaScript, too. This helps you skip or simplify motion for people who've asked to reduce it in their system settings.
if (window.matchMedia('(prefers-reduced-motion: reduce)').matches) {
// User prefers reduced motion—avoid animation
} else {
// Safe to run animation
}

This small addition helps ensure that JavaScript-based animations, like bouncy scrolls, custom sliders, or dynamic UI effects, don't cause discomfort for users who need a calmer experience.
### Manual Toggle to Turn Off Motion

Not everyone's system is set up to reduce motion. That’s why it’s helpful to offer a manual site-wide control, like a setting in your menu or a simple toggle on the page, to switch off non-essential motion.
A mockup of a website homepage with an accessibility settings panel open. The panel offers toggles to “Remove Motion Effects” (switched ON) and “Dark Mode” (switched OFF).
### Don’t use motion unless it’s essential

Ask yourself: Is this animation helping someone understand what’s going on? If not, consider removing it or making it optional.
For example, in a design app where previewing an animation is the point of the feature, that’s essential. Leave it in. But if you’ve got floating confetti after someone submits a form? That’s probably just decorative, and users should be able to skip it.

## Conclusion

Animations can be fun, but only if they don’t make people dizzy or sick. WCAG 2.3.3 helps ensure that motion triggered by interactions doesn’t mess with people’s health or focus. So cut the extra flair when it’s not needed. Use prefers-reduced-motion, toggles, and better defaults to make sure your site is smooth for everyone.

## Related Success Criteria

