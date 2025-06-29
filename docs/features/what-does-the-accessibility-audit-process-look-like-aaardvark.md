# What Does The Accessibility Audit Process Look Like? - AAArdvark

# What Does The Accessibility Audit Process Look Like?

 

## (Episode 7)

 

![](https://aaardvarkaccessibility.com/wp-content/uploads/2024/10/AAA-A11y-Podcast-Ep-7.png)

Share the Post: 

[Share on LinkedIn](https://www.linkedin.com/shareArticle?mini=1&url=https%3A%2F%2Faaardvarkaccessibility.com%2Fwhat-does-the-accessibility-audit-process-look-like%2F&title=What%20Does%20The%20Accessibility%20Audit%20Process%20Look%20Like%3F&source=https%3A%2F%2Faaardvarkaccessibility.com)[Share on X (Twitter)](https://twitter.com/intent/tweet?text=What%20Does%20The%20Accessibility%20Audit%20Process%20Look%20Like%3F&url=https%3A%2F%2Faaardvarkaccessibility.com%2Fwhat-does-the-accessibility-audit-process-look-like%2F&via=aaardvarka11y&related=aaardvarka11y)[Share on Reddit](https://www.reddit.com/submit?url=https%3A%2F%2Faaardvarkaccessibility.com%2Fwhat-does-the-accessibility-audit-process-look-like%2F)[Share on Facebook](https://www.facebook.com/sharer/sharer.php?u=https%3A%2F%2Faaardvarkaccessibility.com%2Fwhat-does-the-accessibility-audit-process-look-like%2F)[Share on Email](https://aaardvarkaccessibility.com/cdn-cgi/l/email-protection#c2fda0ada6bbff8be7f0f2b0a7a3a6e7f0f2b6aaabb1e7f0f2b2adb1b6e7f0f2adace7f0f2838383b0a6b4a3b0a9e7f0f2a3aca6e7f0f2b5a3acb6a7a6e7f0f2b6ade7f0f2b1aaa3b0a7e7f0f2abb6e7f0f2b5abb6aae7f0f2bbadb7ece7f0f28aa7b0a7e7f0f5b1e7f0f2b6aaa7e7f0f2aeabaca9e7f183e7f0f2aab6b6b2b1e7f183e7f084e7f084a3a3a3b0a6b4a3b0a9a3a1a1a7b1b1aba0abaeabb6bbeca1adafe7f084b5aaa3b6efa6ada7b1efb6aaa7efa3a1a1a7b1b1aba0abaeabb6bbefa3b7a6abb6efb2b0ada1a7b1b1efaeadada9efaeaba9a7e7f084e4e1f2f1faf9b1b7a0a8a7a1b6ff81aaa7a1a9e7f0f28db7b6e7f0f296aaabb1e7f0f2838383b0a6b4a3b0a9e7f0f283a1a1a7b1b1aba0abaeabb6bbe7f0f280aeada5e7f0f3e7f0f295aaa3b6e7f0f286ada7b1e7f0f296aaa7e7f0f283a1a1a7b1b1aba0abaeabb6bbe7f0f283b7a6abb6e7f0f292b0ada1a7b1b1e7f0f28eadada9e7f0f28eaba9a7e7f184)

![AAArdvark Accessibility Podcast](https://aaardvarkaccessibility.com/wp-content/uploads/2025/01/AAA-A11y-Podcast-Ep-7-150x150.png)

						AAArdvark Accessibility Podcast					
What Does The Accessibility Audit Process Look Like?

Play Episode

Pause Episode

![Loading](https://aaardvarkaccessibility.com/wp-content/plugins/seriously-simple-podcasting/assets/css/images/player/images/icon-loader.svg)

Mute/Unmute Episode

Rewind 10 Seconds

1x

Fast Forward 10 seconds

00:00
/

00:26:27

Join Natalie and Natalie for the seventh episode of the AAArdvark Accessibility Podcast, where they discuss the accessibility auditing process in detail.

Natalie Garza: Hello, everybody, and welcome to the seventh episode of the AAArdvark Accessibility Podcast. In this week’s video, we’re going to go over the auditing process and what that looks like in more detail. I’m your host, Natalie G. I’m an accessibility novice learning things along the way. Here with me today is…

Natalie MacLees: Natalie MacLees, accessibility expert.

Natalie Garza: Yes, thank you for joining me, Natalie. In today’s episode, we’re going to start off with: What does a typical auditing process look like? Would you care to share with us?

Natalie MacLees: All right. So, we sit down, and you’re going to audit a website. Usually, the first thing that you do is run automated tests. Those are only going to catch about 30 percent of the issues, but that’s 30 percent of the issues you don’t have to find manually, so it can be really helpful.

There are all different kinds of automated scanners out there. WebAIM makes WAVE, there’s an AXE browser add-on from Deque, and of course, there’s AAArdvark, which will do the automated scanning for you and find automatic issues.

Once you’ve gone through and run the automated tests, usually there are some things that you have to check because robots can’t always say for sure if it’s an issue or not. Most automated scanners will flag some things to say, “Oh, this needs to be checked manually. I’m not really sure if it’s an issue yet or not.” Then you can decide, yes, this is an issue, or no, it’s not.

Once you’ve done that, then you start the manual testing process, which is where most of the time goes for an audit. You just start manually using the website and looking for places where there are accessibility issues.

You want to try using the website with just the keyboard. So, you put your mouse on the other side of the room and see if you can navigate through the site. Can you do everything that’s available with just a keyboard?

Then you’d also want to test with at least one screen reader as well, making sure that you can get through the page with a screen reader. Usually, upfront, you would define what different platforms you’re going to test on with your client. So, you would say upfront, “I’m going to test with Safari and VoiceOver on a Mac,” or, “I’m going to test with TalkBack on an Android phone.”

Because you have to think about mobile devices and tablets as well, you would work out ahead of time with your client what technologies you’re actually going to test with. Then, you just start working through the page and finding all the different kinds of issues that way.

Natalie Garza: Can we backtrack a little bit?

Natalie MacLees: Yes, of course.

Natalie Garza: You said that the automated scans only bring up 30 percent of the issues. What is the reason behind that?

Natalie MacLees: Not all of them are easily recognized by technology at this point. Some of them require an actual human to do the test. We’ll see what happens with AI in the next few years. So far, I haven’t seen any amazing, stellar AI solutions for accessibility, but for now, there are things that a human has to look at.

A good example: A robot can tell pretty easily if an image has alternative text on it or not. That’s easy to check—is there a string there or isn’t there? But what a robot can’t really tell is: Is that alternative text correct? Is it complete? Is it comprehensive? Does it describe the image correctly? Does it describe the context of the image correctly? A robot can’t really decide that. So, somebody has to look at that right now to decide that.

Natalie Garza: Gotcha. Then for manual testing, you have to go into the webpage and actually use it?

Natalie MacLees: Yeah.

Natalie Garza: In my head, I thought you had, like, a WCAG checklist, and you kind of went through each rule. Is that not how it works at all?

Natalie MacLees: You can definitely use a checklist as guidance to make sure that you don’t forget to test for something. But it can be a little bit difficult to check for just one rule at a time as you’re going through.

If you have a checklist of 50 things, you’re going through the webpage 50 times to check for every one of those issues. Some of them would be pretty simple and quick to check for.

For example, if it’s a page with one video on it, it’s pretty easy to check if the video has captions or not. If it’s a page with 50 videos, that’s going to take a lot more time. You probably just want to be doing multiple checks kind of at the same time.

On each pass through the site, you would want to be checking multiple things. But yeah, there is definitely a checklist you work from, like, “Oh, I have to remember to check if there’s alt text. I need to remember to check color contrast. I need to remember to check if it works with a keyboard,” and so on.

But you kind of do multiple tests at the same time, if that makes sense.

Natalie Garza: I see. So when do the WCAG guidelines or success criteria come into play as you’re testing?

Natalie MacLees: Pretty much the whole time.

I’d be pretty surprised if anybody sat down with just a list of the WCAG success criteria and tried to use that as their checklist. I think a lot of accessibility professionals have developed their own checklists to make sure they’re hitting all of those diverse success criteria.

Some of them it makes sense to test together because some are very closely related, and other ones make sense to test separately. Usually, there’s a separate list that somebody has made, or maybe they’re using one that’s in the public domain, that would walk you through making sure that you are hitting all of those success criteria in your testing.

But like I said, you’re probably working on multiple items on the checklist at the same time on each pass through the page.

Natalie Garza: Mm-hmm. And when an auditor is going through the testing on the page, the skills come in when they’re like, “Oh, I’m testing this video. It has to be one of these that we’re failing.”

Natalie MacLees: Yeah, you have to know what the rules are. For example, if I’m testing a form, I have to know that for a form field, it has to have a label. It has to be correctly marked up for what type of input it is.

If it’s a required field, that has to be marked programmatically in some way. You can’t just put an asterisk in the label; you actually have to programmatically mark that field as required.

I have to test if there’s some kind of error that can happen. If it’s a required field and I leave it empty, or if it’s a phone number field and I type letters in it, there could be some kind of error.

Now I have to test: Do the error messages show up, number one? Number two, are they actually helpful? Do they tell me what’s wrong and how to fix it? Because I’m sure we’ve all had that experience where something went wrong, and you have no idea what it is or what the problem is.

The error messages have to be helpful. They have to say, “Oh, your phone number can’t contain letters,” for example.

Then they also have to be programmatically associated with the form field. So, you have to know that those are all the things to check, and you have to know which success criteria those map to—like, which one is it failing if any one of those things is missing.

Natalie Garza: Right. So a lot of practice. A lot of repetition.

Natalie MacLees: Yes, exactly.

Natalie Garza: Okay, so now I kind of get why just getting your certification is not going to be enough.

Natalie MacLees: Yeah. There is a lot of practice to actually digging through a page and finding all the issues. It’s easy to miss some that are a little bit more subtle.

Natalie Garza: Right. And so manual testing, most of it is just manual testing, like you going through the page and manually checking everything.

Natalie MacLees: Yeah, using every little thing on the page—every button, every link, every little interactive thing. You’re using it just like a user would and seeing what barriers you run into.

Natalie Garza: And you mentioned keyboard navigation and screen readers. Is there any other perspective of testing that you have to involve too?

Natalie MacLees: Most of the time, if you can cover screen reader and keyboard, that covers almost every use case. But if you have the budget, it’s always a good idea to actually hire users with disabilities to also test the site.

If you are not a disabled user yourself, there are a lot of accessibility professionals who are disabled.

Of course, every person with disabilities is unique. So, everybody is different. It’s not like you can hire one person and say, “Oh, well, this person could use the site, so it must work for everybody.” There’s a whole spectrum of different challenges that people might run into using a website.

Ideally, you’d want to hire a few different people and have them work through the site to see what different kinds of barriers they might run into while using it.

Natalie Garza: In a previous episode, you mentioned a lot of accessibility professionals for larger sites usually get hired on retainer. Do users with disabilities also get hired on retainer? Is that a thing?

Natalie MacLees: It would be really nice if it was, but not to my knowledge.

I think there are a handful of organizations that we’ll probably talk about in a future episode—businesses and nonprofit organizations that will coordinate with you to help you hire people to do testing. But it’s usually just on a one-off basis.

Before the pandemic, a lot of times, they were actually going into an office to test. They would schedule things so that they’d have somebody come in and test four different websites in one morning, for example.

I think now a lot of it is done remotely, which is even better because, of course, there are people with mobility issues where going into an office wouldn’t be the most convenient.

Being able to do that remotely is really helpful. But yeah, you can work with one of those organizations to hire somebody just on a one-off basis. They handle the recruiting, the recording of the test, helping you get the test set up—all of that.

Natalie Garza: I see. So there are streamlined ways. You don’t just have to go on a marketplace.

Natalie MacLees: Sure. Right. Yes. And also, the other thing that’s helpful is that it’s testers who are trained in how to test a website, not just random user testing.

But random user testing can be helpful too because sometimes, if you’re using only users who have been trained, they’re really tech-savvy, and they don’t really represent your average user on your site.

Now we’re kind of getting into more of user testing and user experience, but that’s where it starts to overlap with accessibility.

Natalie Garza: Gotcha. Then also, for manual testing, a lot of success criteria seem to affect tablet and mobile views. Is that also part of the auditing process?

Natalie MacLees: Yeah. So, you would want to work that out. If you’re hiring somebody to do an audit, or if you’re the one being hired to do an audit, before you get started, you would want to work out what devices you’re going to use, which browsers you’re going to use.

Of course, the more, the better, but that impacts the budget and the timeline for the project. So, you have to find a good balance between what a client can afford to do and perfection—which would be testing every single browser, every single screen reader, every single device.

It’s not very practical or pragmatic to do that. But you could figure out a small sample of maybe two or three different devices and screen reader pairs that are going to find most of the issues and uncover the most things for an affordable and realistic budget.

Natalie Garza: Okay. What do you think are the most commonly used combinations then?

Natalie MacLees: For screen readers, Safari pairs best with VoiceOver. Each one has its own browser that works best with it. NVDA works best with Firefox, and the JAWS screen reader works best with Microsoft Edge.

On mobile devices, the screen readers are built in. So, on iOS devices, you have VoiceOver, which is the same one that’s built into Mac desktops and tablets—it’s all the same thing. Android devices have a screen reader called TalkBack that works very similarly and is built right into the OS.

So, you would want to test with as many different variations as you can within those combinations.

Natalie Garza: I see. Do you guys use something like Google Analytics to determine, “Okay, most of your traffic is on Chrome, so we’re going to have to prioritize this one”?

Natalie MacLees: Yeah, using analytics data like that can definitely be helpful for figuring out what most of the users to the site are using. Also, which content most users are visiting.

You probably don’t want to spend a lot of time doing an audit on a page that only gets a tiny percentage of traffic, especially when you have other pages that get lots and lots of traffic.

Natalie Garza: Yeah, so that’s another question—do you prioritize the pages?

Natalie MacLees: Yeah, I would definitely always look at the most important pages of the site. Those would always include the homepage, and then other important pages depend on what kind of site it is.

If it’s a site to hire services—like a web design agency, for example—the contact page would be another important page because you want to make sure people can get in touch with you.

On an e-commerce site, all the cart pages would be important pages because you want to make sure that if people are interested enough to put something in the cart, they can go through and check out successfully.

So, you would look at the most important pages, the highest traffic pages, and then also the pages most likely to be problematic—pages with forms, pages with interactive elements, and things like that. Those are probably where you’d want to start.

Natalie Garza: Gotcha. I know a lot of sites use templates. For example, on an e-commerce site, if you go through one product page, do you have to go through all of the product pages?

Natalie MacLees: No, especially if there are, like, 10,000 product pages. You don’t want to go through all of those! That would make an audit take a really long time and be really expensive.

So, you would want to pick a random sample of products to go through. If you have different types of products—for example, if I had a store that sold t-shirts and books—I would want to make sure my random sample included a t-shirt and a book.

If I’m buying a t-shirt, I’ll have color and size choices. Those controls won’t show up on a book. If I’m buying a book, I might have a choice of hardcover, paperback, or eBook, which won’t show up on a t-shirt.

You want to think about all the different conditional things that might show up on different products and make sure your sample covers as many of those as possible.

Natalie Garza: Mm-hmm. And probably just give the client a checklist so they don’t accidentally break something within those templates, right?

Natalie MacLees: Yeah. You need to be really careful when you’re editing a template that’s going to impact 10,000 products across the site. If you introduce an accessibility issue, now you have 10,000 accessibility issues.

Natalie Garza: Like the individual pages, too. If you’re using a CMS and just putting content into those templates, you can still break guidelines.

Natalie MacLees: Yeah, you could put in an image and not add alt text. You could use bad link text. There are all kinds of things you could do, just with the content alone.

Natalie Garza: Right. So, a checklist, and you only have to check the template.

Natalie MacLees: Yeah.

Natalie Garza: Alright, what kind of issues come up during manual testing?

Natalie MacLees: Like the most common issues?

Natalie Garza: Yeah, give us a little taster—a sample platter—to give the audience an idea of the type of stuff you look for during the audit.

Natalie MacLees: Sure. We’ve already mentioned a few things, like alternative text on non-text content, which includes images, videos, and audio. Making sure there’s alt text on images, captions on videos, and text transcriptions for audio files is key.

Another really common issue is color contrast. You can’t put white text on a pale blue background because that’s not enough contrast. It’s a super common issue where text and background colors are too similar—light text on light backgrounds or dark text on dark backgrounds.

Heading structure is another big one—getting the headings in the correct order. For example, skipping from an H1 to an H5 or using all H1s on a page instead of a proper hierarchy. Also, using headings just for styling because you want the text to be large, rather than marking something that’s actually a heading.

Keyboard navigation is another issue that pops up a lot. Many websites don’t work properly with just a keyboard. That’s why testing keyboard accessibility is so important. You should be able to navigate a website, fill out forms, and complete tasks—like checking out on an e-commerce site—entirely with a keyboard.

Screen reader compatibility is another area where issues often occur. Every interactive element—buttons, links, form fields—needs to have an accessible name that gets read out. For example, a screen reader shouldn’t just say “button.” It should say, “Submit form button” or “Show image button.” The same goes for form fields—users need to know if they’re entering their name, email, phone number, or anything else.

Those are some of the most common things you find across the internet.

Natalie Garza: And lastly, how do you write down an issue? What information is included?

Natalie MacLees: You want to include where you found the issue so that when someone comes back to fix it, they know where to find it. You also want to describe the issue itself—like which WCAG rule it’s violating, how it’s violating that rule, and what’s wrong.

You’ll want to include a recommended fix—how they could resolve the issue. And if there are multiple solutions, you might say, “This would be the best fix, but if that’s not possible, you could do this or that instead.”

Documenting everything clearly is important so that when someone comes back to remediate the issues, they can easily understand where the issue is, what the issue is, and how to fix it.

Natalie Garza: If there are multiple instances of the same issue on a page, how do you differentiate them?

Natalie MacLees: You have to get specific. For example, if there are multiple places on the page with color contrast issues, you might say, “It’s the link in the section titled ‘Contact Us.’ The third link doesn’t have enough contrast.”

Or, you could use a tool like AAArdvark, which lets you record issues directly on the page. You just click on an element, say, “This element has an accessibility issue,” describe the issue, and it gets documented. When someone comes back to remediate, they can see exactly where the issue is on the page—it’s marked right on the element.

Natalie Garza: So traditionally, it does take a long time to…

Natalie MacLees: It can definitely be time-consuming to document everything line by line for every single issue.

Natalie Garza: But there’s a solution to that, isn’t there?

Natalie MacLees: Yes! AAArdvark is really helpful for that. When I was doing manual issue recording, I kept thinking, “This is bananas. This is so difficult, and so many people are doing this all over the world.”

That was the inspiration for building AAArdvark. I felt like there had to be a faster and easier way to do it. With AAArdvark, you just click on an element, say, “It’s missing alt text,” and it automatically tells you, “Oh, that’s WCAG 1.1.1.” It also provides recommended solutions, so you can choose one, add extra notes if needed, and click submit.

That’s it. Everything gets filled in for you—accurately and quickly.

Natalie Garza: Yes, you don’t have to go into your spreadsheet: “Row 5, Column B, link in Section Heading…”

Natalie MacLees: Exactly. And you don’t have to deal with a developer saying, “I’m confused. Where is this issue? I don’t see it.” Now, they can see exactly where the issue is on the page.

Natalie Garza: And so, with that, we invite you all…

Natalie MacLees: To try AAArdvark! You can go to aaardvarkaccessibility.com, add your homepage for free, and get access to all of our tools. Run the automated scan, try recording a manual issue, and give it a try!

Natalie Garza: Yes! And with that, that’s the end of episode six—no, seven!

Natalie MacLees: Seven.

Natalie Garza: I messed up the intro, then.

Natalie MacLees: No, you said seven.

Natalie Garza: I did?

Natalie MacLees: You did.

Natalie Garza: Okay. Episode seven of the AAArdvark Accessibility Podcast. Thank you for joining us today!

Share the Post: 

[Share on LinkedIn](https://www.linkedin.com/shareArticle?mini=1&url=https%3A%2F%2Faaardvarkaccessibility.com%2Fwhat-does-the-accessibility-audit-process-look-like%2F&title=What%20Does%20The%20Accessibility%20Audit%20Process%20Look%20Like%3F&source=https%3A%2F%2Faaardvarkaccessibility.com)[Share on X (Twitter)](https://twitter.com/intent/tweet?text=What%20Does%20The%20Accessibility%20Audit%20Process%20Look%20Like%3F&url=https%3A%2F%2Faaardvarkaccessibility.com%2Fwhat-does-the-accessibility-audit-process-look-like%2F&via=aaardvarka11y&related=aaardvarka11y)[Share on Reddit](https://www.reddit.com/submit?url=https%3A%2F%2Faaardvarkaccessibility.com%2Fwhat-does-the-accessibility-audit-process-look-like%2F)[Share on Facebook](https://www.facebook.com/sharer/sharer.php?u=https%3A%2F%2Faaardvarkaccessibility.com%2Fwhat-does-the-accessibility-audit-process-look-like%2F)[Share on Email](https://aaardvarkaccessibility.com/cdn-cgi/l/email-protection#af90cdc0cbd692e68a9d9fddcacecb8a9d9fdbc7c6dc8a9d9fdfc0dcdb8a9d9fc0c18a9d9feeeeeeddcbd9ceddc48a9d9fcec1cb8a9d9fd8cec1dbcacb8a9d9fdbc08a9d9fdcc7ceddca8a9d9fc6db8a9d9fd8c6dbc78a9d9fd6c0da818a9d9fe7caddca8a9d98dc8a9d9fdbc7ca8a9d9fc3c6c1c48a9cee8a9d9fc7dbdbdfdc8a9cee8a9de98a9de9cececeddcbd9ceddc4cecccccadcdcc6cdc6c3c6dbd681ccc0c28a9de9d8c7cedb82cbc0cadc82dbc7ca82cecccccadcdcc6cdc6c3c6dbd682cedacbc6db82dfddc0cccadcdc82c3c0c0c482c3c6c4ca8a9de9898c9f9c9794dcdacdc5caccdb92ecc7caccc48a9d9fe0dadb8a9d9ffbc7c6dc8a9d9feeeeeeddcbd9ceddc48a9d9feecccccadcdcc6cdc6c3c6dbd68a9d9fedc3c0c88a9d9e8a9d9ff8c7cedb8a9d9febc0cadc8a9d9ffbc7ca8a9d9feecccccadcdcc6cdc6c3c6dbd68a9d9feedacbc6db8a9d9fffddc0cccadcdc8a9d9fe3c0c0c48a9d9fe3c6c4ca8a9ce9)

