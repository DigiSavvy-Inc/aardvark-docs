# 2.4.1 Bypass Blocks - AAArdvark

[Operable](https://aaardvarkaccessibility.com/wcag-principle/operable/)

[Navigable](https://aaardvarkaccessibility.com/wcag-guideline/navigable/)

WCAG 2.0, 2.1, 2.2
Level A

[View official documentation for WCAG 2.4.1](https://www.w3.org/WAI/WCAG22/Understanding/bypass-blocks.html)

# 2.4.1 Bypass Blocks

‘Skip links’ are available for keyboard users to jump past navigation.

[Keyboard](https://aaardvarkaccessibility.com/wcag-theme/keyboard/) 

 

[Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Physical/Motor](https://aaardvarkaccessibility.com/wcag-disability/physical-motor/), [Visual](https://aaardvarkaccessibility.com/wcag-disability/visual/) 

 

[Code](https://aaardvarkaccessibility.com/wcag-responsibility/code/), [Design](https://aaardvarkaccessibility.com/wcag-responsibility/design/) 

## What is it?

Users who rely on assistive technology, such as screen readers and keyboard navigation, can struggle with repetitive content that makes the main content difficult to reach. This can include elements such as navigation menus, search fields, banners, advertisements, etc.
While it’s okay or even expected to have repeated content across a site's pages, we also have to keep in mind that some users will find it helpful to bypass those blocks. For example, a heading section template that’s applied to all the pages of a site. Or a navigational sidebar that’s repeated across a blog.
The goal of this criterion is to help people skip over repetitive sections or blocks of content on websites and make it easy to get the main content on the page.
Web page that outlines standard repetitive blocks of content, including the navigational header, a banner image, ads, and a search bar.

## Why does it matter?

Allowing users to bypass blocks of content makes sure users who rely on assistive technology can quickly access the main content of a web page. Without the ability to skip to the main content, users may get frustrated or find websites downright unusable, given how bothersome it is to use each page.
Non-disabled users are often accustomed to ignoring content on the web and can quickly scroll past sections they want to ignore to get to the main sections. However, for some users, repetitive sections of content can be tedious at best. Trying to figure out how to move past the same large navigation section over and over on every page can be confusing or tiresome.

## Who is affected?

People with limited mobility. People with low or limited vision. People who are blind.

People with limited mobility who rely on keyboard navigation can find it challenging to navigate repetitive blocks of content, given the dozens of added keystrokes per page required to reach the main content. For some users, the high number of keystrokes per page can be very tiring and cause extra strain.
People with low or limited vision who use screen magnification may struggle with finding where the main content begins. When the page is heavily magnified, users often have to spend added time sifting through repetitive blocks to orient themselves and figure out where the main sections are.
People who are blind and rely on screen readers will find this the most helpful since they can avoid having to hear the same headings, navigation links, alt text, buttons, etc., on every page before hearing the main content. Imagine hearing the same 200 words repeated every time you open a new page just so that you can reach the content—it would drive anyone bonkers!

## How to implement 2.4.1

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

### Links to Skip Blocks of Repeated Content

There are a few different ways “skip links” can be implemented. Each case will be different, but you’re welcome to use any one of the following techniques as you see fit.
Skip links should preferably always be visible to all users. However, to meet this criterion, they’re only required to be visible when the user has a keyboard focus directly on them.
In all cases, the description of each link needs to communicate that it links to a specific section of the content.
#### Initial Skip to Content Link

The first clickable item on the page should be a link that moves focus directly to the main content. This is especially useful on pages with a single main content area and few navigation sections.
#### Mini Table of Contents

Another option would be to create a list of links at the start of the page, somewhat like a mini table of contents, letting users jump to different sections of the page. This technique is best used when there are many separate sections of equal importance to the main content.
#### Skip Specific Content

This technique helps users skip over sections of repeated content on a web page. A link at the start of each block or right before it lets users jump to the content immediately after the block. This is helpful when it’s necessary to bypass blocks that exist within the main content or after it.
Web page offers a skip link at the very beginning of the page. An arrow points to the main content to signify the link will skip the focus to that section after clicking.
### HTML Tags

Using HTML tags to implement landmarks is the best way to help users differentiate sections with assistive technology. Semantic HTML tags like <header>, <nav>, <main>, <aside>, and <footer> clearly define the structure and purpose of different parts of a webpage.
This ensures that screen readers and other assistive tools can accurately convey the layout and hierarchy to users, making navigation more intuitive. This allows users to easily locate and jump to the main content, navigation menus, and other key sections of a page.
### ARIA Landmarks

Please note that ARIA is not typically the preferred method of accessibility remediation. Instead this technique should be used as a supplement to the preferred techniques listed above in conjunction with proper semantic structure in the HTML such as using correct and accessible headings, lists, buttons, etc.
In this case, we would use ARIA landmarks to markup the different sections so that users can easily skip to the main region of a page. For example, you can assign certain sections a role attribute to give them ARIA landmarks such as “navigation”, “banner”, “search”, and most importantly, “main” for the page’s main content.
<div role="main">The page's main content is here.</div>

### Section Headings

This technique uses section headings to organize content clearly. Headings should help users find the start of the main content, unique sections, and navigation areas. Properly nested headings (e.g., <h2> under <h1>) create a logical hierarchy and allow assistive technology users to jump to headings quickly.
### Using Titles with Iframe Elements

When <iframe> elements potentially containing repetitive ads are used, and the <iframe> tag needs to receive a descriptive title attribute. That way, each <iframe> is labeled, and the user can determine which frame to enter or skip.
<iframe src="banner-ad.html" name="ad-iframe" title="Advertisement"></iframe>

### Collapsible and Expandable Menus

This technique helps users skip repeated content by placing it in a menu that can be expanded or collapsed. Users can hide the repeated material by collapsing the menu. There are several ways to create menus that let users skip navigation; however, to meet the criteria, the following needs to be true:

Make sure there's a control to expand or collapse the repeated content.
Ensure the expanded content appears in the correct place in the reading order.
When collapsed, the content should be excluded from the reading order.

## Conclusion

Making it easy for users to skip repetitive content helps everyone, especially those with disabilities, access the main info on a page quickly. Techniques like skip links, mini tables of contents, and collapsible menus can make a big difference.

## Related Success Criteria

