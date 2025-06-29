# 2.4.8 Location - AAArdvark

[Operable](https://aaardvarkaccessibility.com/wcag-principle/operable/)

[Navigable](https://aaardvarkaccessibility.com/wcag-guideline/navigable/)

WCAG 2.0, 2.1, 2.2
Level AAA

[View official documentation for WCAG 2.4.8](https://www.w3.org/WAI/WCAG22/Understanding/location.html)

# 2.4.8 Location

The user is clearly informed where they are in a set of pages.

[Whole Site](https://aaardvarkaccessibility.com/wcag-theme/whole-site/) 

 

[Cognitive](https://aaardvarkaccessibility.com/wcag-disability/cognitive/), [Visual](https://aaardvarkaccessibility.com/wcag-disability/visual/) 

 

[Code](https://aaardvarkaccessibility.com/wcag-responsibility/code/), [Design](https://aaardvarkaccessibility.com/wcag-responsibility/design/) 

## What is it?

Users must always know where they are within a website or group of pages. This helps them get oriented and navigate with confidence.
Location indicators to help meet the success criteria include:

Breadcrumbs
Highlighted Navigation Menu Items
Site Maps
Mini Table of Contents

A flowchart-style visual shows the structure of the Aardvarks Are Awesome website, branching out from the homepage to various categories and subpages. A large pin icon with the label “You Are Here” points to the “Photo Gallery” section to show the current location.

## Why does it matter?

Websites can sometimes be big and complex, and without any location markers, people with cognitive disabilities can get confused or disoriented.
Location indicators provide context to every page on a website. They show how one page fits into the larger picture and how to backtrack or explore related content without getting lost.

## Who is affected?

People with cognitive disabilities. People with short attention spans.

People with cognitive disabilities may have trouble understanding how a page fits into the bigger picture without clear navigation cues or context.
People with short attention spans can easily lose track of where they are on a site, especially if they click around quickly or get distracted.
In general, this success criterion is helpful to anyone landing deep in a site from a search result. Someone landing on a deeply nested page might wonder: Where am I? How did I get here? What else is nearby? Clear location cues reduce that confusion and help them decide what to do next.

## How to implement 2.4.8

This section offers a simplified explanation and examples to help you get started. For complete guidance, always refer to the official WCAG documentation.

### Give Each Page At Least One Location Indicator

Use navigation cues to show the current page’s position within your site structure. This can be done in various ways; just make sure each page on the website uses at least one of the methods listed below and is consistent to meet 3.2.3 Consistent Navigation.
#### Breadcrumb Trails

A breadcrumb trail shows the path from the homepage or the parent of a group of related pages to the current page. It helps users backtrack and understand the structure.
For example:
Home > Services > Web Design
Breadcrumbs also must include links to all the pages in the trail, with the exception of the current page; that page's title doesn't have to be linked. And, it's helpful to include a visual separator, like >, », |, or →.
A cartoon aardvark follows a trail of crumbs leading to a broken piece of bread. Below the crumbs is a breadcrumb-style navigation: “Homepage > Diet and Eating Habits > What Aardvarks Eat,” with each link styled to show the user’s current location.
#### Navigation Highlighting

Highlight or indicate the current page in menus or tabs. This helps users know where they are and which section they’re in. You can use styling, icons, or text like “You are here.”
An easy method to achieve this is to create a CSS class .active to style the current page link in your nav. Then add that class using JavaScript to the matching <a> tag in your HTML to highlight the active page.
A browser window shows a website titled "Aardvarks Are Awesome!" with a left sidebar menu. The “Aardvark Gallery” section is expanded, and “Photo Gallery” is highlighted in blue, indicating the current page. The main content area displays several photos of aardvarks.
#### Site Maps

A well-structured site map helps users see how everything is connected. They can check where they are and what’s around them, without relying solely on menus.
To meet this criterion using site maps, make sure the link to the site map is available on each page. And, when viewing the site map, make sure:

All the links in the site map are correct and lead to the right pages
Each page in the site is included in the site map. Or that every page can be reached by links that start at the site map

A website sitemap page displays clickable links grouped by sections.
#### Page Titles or Headers

Titles can include context clues, such as “Part 2 of 4: Shipping Info” or “Support > Accessibility Tools.” This helps users understand where the page fits in a larger process or section.
If you use this method, make sure the page title clearly reflects its relationship to the rest of the site or content set. You can do this visually by adding it to the page heading or programmatically using metadata or HTML attributes like rel to show the page's relationship to others. It helps users orient themselves and understand how the current page connects to others around it.

## Conclusion

Helping users understand where they are on your site reduces confusion, especially for those with cognitive disabilities or short attention spans. A little context goes a long way in helping users avoid getting lost.

## Related Success Criteria

