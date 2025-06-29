# 3.3.9 Accessible Authentication (Enhanced) - AAArdvark

[Understandable](https://aaardvarkaccessibility.com/wcag-principle/understandable/)

[Input Assistance](https://aaardvarkaccessibility.com/wcag-guideline/input-assistance/)

WCAG 2.2
Level AAA

[View official documentation for WCAG 3.3.9](https://www.w3.org/WAI/WCAG22/Understanding/accessible-authentication-enhanced.html)

# 3.3.9 Accessible Authentication (Enhanced)

Authentication must be possible without any cognitive function test.

[Forms](https://aaardvarkaccessibility.com/wcag-theme/forms/) 

 

[Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Physical/Motor](https://aaardvarkaccessibility.com/wcag-disability/physical-motor/) 

 

[Code](https://aaardvarkaccessibility.com/wcag-responsibility/code/) 

## What is it?

Authentication, or the ability to log into a website, should not feel like a puzzle, especially not one that involves picking out objects in images, remembering pictures you uploaded weeks ago, or figuring out which blurry squares contain a bicycle.
WCAG 3.3.9 ensures that websites can't require recognition of images, videos, or media, even if the user provided them, as the only way to authenticate. At least one alternative must be available that doesn't rely on a cognitive function test.
It builds on the previous guideline, WCAG 3.3.8 Accessible Authentication (Minimum), by removing exceptions. The goal is to make logging in less mentally demanding, especially for people who struggle with memory, attention, or visual processing.

## Why does it matter?

If authentication relies on recognizing objects, identifying distorted pictures, or remembering which pet photo you uploaded months ago, people may struggle to access essential services or give up altogether. Complex authentication can be a major barrier for people with cognitive disabilities, including those with reading disabilities and memory or perception limitations.

## Who is affected?

People with cognitive disabilities.

People with cognitive disabilities vary widely:

Those with memory limitations may struggle with memory-based image recognition.
Those with reading disabilities, such as dyslexia or dyscalculia, might have trouble identifying distorted text or blurry visuals.
Those with attention disorders could forget which photo or image they previously uploaded.
Those with mental processing difficulties can have trouble identifying specific objects in images (like traffic lights or crosswalks).

## How to implement 3.3.9

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

To meet this criterion, you first must satisfy WCAG 3.3.8 Accessible Authentication (Minimum). That includes offering at least one login method that doesn't rely on a cognitive function test, such as memorizing a password or solving a puzzle.
While WCAG 3.3.8 allows limited exceptions, those exceptions are moved in WCAG 3.3.9 entirely. That means you cannot rely on recognition of images, patterns, media, or other visual cues as the sole means of authentication, even if those images were provided by the user themselves.
### Log in Without Visual Puzzles

Websites must offer at least one authentication method that doesn’t require users to solve image-based challenges or recognize previously uploaded media. These methods often pose barriers for users with cognitive, visual, or perceptual disabilities.
Avoid login methods such as:

Selecting previously uploaded images
Identifying objects in photos (e.g., click all the traffic lights)
Solving distorted-text CAPTCHAs
Matching audio clips to images

Examples of inaccessible login methods including image selection, distorted text CAPTCHA, previous upload recognition, and visual puzzle challenges.
Instead, offer more accessible login options, such as:

Login links sent via email or SMS
Biometric logins (fingerprints or facial recognition)
Integration with third-party identify providers
Password managers that autofill credentials without requiring recall

These approaches avoid memory- or recognition-based challenges and allow users to authenticate without unnecessary cognitive effort.
#### If You Must Use CAPTCHAs

Whenever possible, avoid CAPTCHAs entirely as they often introduce significant barriers. But if you must use one:

Offer a non-cognitive alternative, like a simple "I'm not a robot" checkbox that doesn't require solving a challenge.
Don't rely on distorted images or audio that requires complex interpretation.
Make sure the CAPTCHA is not the only way to complete the authentication process. At least one fully accessible method must be available.

## Conclusion

Authentication shouldn’t be a barrier. By removing image-based challenges and offering simple, accessible login methods, websites can ensure that everyone, including those with cognitive and visual disabilities, can easily sign in.

## Related Success Criteria

