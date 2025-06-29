# What Are Accessibility Overlays and Why Are They Bad? - AAArdvark

# What Are Accessibility Overlays and Why Are They Bad?

 

## (Episode 9)

 

![](https://aaardvarkaccessibility.com/wp-content/uploads/2024/10/AAA-A11y-Podcast-Ep-9.png)

Share the Post: 

[Share on LinkedIn](https://www.linkedin.com/shareArticle?mini=1&url=https%3A%2F%2Faaardvarkaccessibility.com%2Fwhat-are-accessibility-overlays-and-why-are-they-bad%2F&title=What%20Are%20Accessibility%20Overlays%20and%20Why%20Are%20They%20Bad%3F&source=https%3A%2F%2Faaardvarkaccessibility.com)[Share on X (Twitter)](https://twitter.com/intent/tweet?text=What%20Are%20Accessibility%20Overlays%20and%20Why%20Are%20They%20Bad%3F&url=https%3A%2F%2Faaardvarkaccessibility.com%2Fwhat-are-accessibility-overlays-and-why-are-they-bad%2F&via=aaardvarka11y&related=aaardvarka11y)[Share on Reddit](https://www.reddit.com/submit?url=https%3A%2F%2Faaardvarkaccessibility.com%2Fwhat-are-accessibility-overlays-and-why-are-they-bad%2F)[Share on Facebook](https://www.facebook.com/sharer/sharer.php?u=https%3A%2F%2Faaardvarkaccessibility.com%2Fwhat-are-accessibility-overlays-and-why-are-they-bad%2F)[Share on Email](https://aaardvarkaccessibility.com/cdn-cgi/l/email-protection#16297479726f2b5f33242664737772332426627e7f6533242666796562332426797833242657575764726077647d3324267778723324266177786273723324266279332426657e7764733324267f62332426617f627e3324266f7963383324265e73647333242165332426627e733324267a7f787d3325573324267e6262666533255733245033245077777764726077647d7775757365657f747f7a7f626f3875797b332450617e77623b7764733b7775757365657f747f7a7f626f3b796073647a776f653b7778723b617e6f3b7764733b627e736f3b747772332450303526252e2d6563747c7375622b557e73757d332426596362332426427e7f6533242657575764726077647d3324265775757365657f747f7a7f626f332426547a7971332427332426417e77623324265764733324265775757365657f747f7a7f626f332426596073647a776f65332426777872332426417e6f332426576473332426427e736f332426547772332550)

![AAArdvark Accessibility Podcast](https://aaardvarkaccessibility.com/wp-content/uploads/2025/01/AAA-A11y-Podcast-Ep-9-150x150.png)

						AAArdvark Accessibility Podcast					
What Are Accessibility Overlays and Why Are They Bad?

Play Episode

Pause Episode

![Loading](https://aaardvarkaccessibility.com/wp-content/plugins/seriously-simple-podcasting/assets/css/images/player/images/icon-loader.svg)

Mute/Unmute Episode

Rewind 10 Seconds

1x

Fast Forward 10 seconds

00:00
/

00:22:48

Join Natalie and Natalie for the ninth episode of the AAArdvark Accessibility Podcast, where they discuss the hot topic of website accessibility overlays and what makes them bad for users and professionals in the accessibility space.

Natalie G: Hello everyone, and welcome to the AAArdvark Accessibility Podcast. This is Natalie G, and I’m an accessibility novice, and with us today is…

Natalie M: Natalie MacLees, accessibility expert.

Natalie G: Thank you. And in today’s episode, we’re going to go over site overlays—what they are, what makes them so bad and hated across the accessibility community, and what you can do instead of using overlays. So Natalie, do you want to kick us off? What are overlays for sites?

Natalie M: Yeah. So I wanted to get started by clarifying that there’s actually two types of overlays, and one of them is actually fine. By ones that are fine, I mean, things like Joe Dolson’s WP Accessibility plugin for WordPress sites. All it does is add a couple of little buttons on the side, although I think you can configure it, but they let you switch to like a dark or high contrast mode, and they let you adjust the font size, and that’s all it does—just add those couple of little tools.

So that kind of overlay, like if you want to call that an overlay, is perfectly fine if you want to use something like that. When we’re talking about the overlays that everybody loves to hate, we’re talking about the ones that make a lot of claims about using AI to magically fix all of the accessibility issues on your website. So if you see that kind of claim happening, that’s the kind of overlay that we’re talking about. And they advertise as though, “Hey, you don’t even have to worry about accessibility anymore. You just drop this little line of JavaScript onto your site, and it’s magically completely accessible. No accessibility issues left on the site at all. It’s just that easy.”

Natalie G: The ones that make the claims, do they also offer little accessibility tools like changing contrasts and stuff like that?

Natalie M: Yeah, they often have a whole pile of tools for all kinds of stuff. Yes, and it makes them look very fancy and very attractive.

Natalie G: Right, but it’s the simple ones you’re looking for, right? Like changing the font size?

Natalie M: Yeah, and we’re also looking for one that’s not making any claims about fixing accessibility issues, right? Like one that’s just saying, “Hey, you can add a couple of these nice little accessibility tools to your site.” That’s fine, but the ones that are saying, “We’re actually going to correct accessibility issues that are on your site”—that’s where we start to get into the danger zone.

Natalie G: Okay. So, talking about the danger zone, do you want to dive into why that’s a danger zone?

Natalie M: Yeah, sure.

Natalie G: Why are they so bad?

Natalie M: So, AI is not good enough at this point to actually fix accessibility issues. So we’ve talked before about how trying to come back to something that’s already built and fix accessibility after the fact is like trying to put the chocolate chips in the cookie after it’s baked, right?

But these overlays are trying to have a robot put the chocolate chips in the cookie after it’s baked, which is gonna be even more of a disaster because the robot doesn’t even know what chocolate chips are, and it can’t eat the cookies, so it just doesn’t care.

So it does not fix all of the accessibility issues on your site. It just cannot. That cannot happen. It’s just impossible. So you can’t believe anything that’s making those claims. They’re not an all-in-one solution. They are going to leave a whole bunch of accessibility issues on your site. It is true—they may fix a few very simple things, but for the most part, they are going to leave all of your accessibility issues there or actually make them worse than they were before you were using the overlay.

Natalie G: Do any of them actually edit the markup on your pages? Like, “Oh, this is missing a label, let me add one”?

Natalie M: So it can’t actually write to files because it’s just JavaScript. So it will modify the markup, yes, it will make changes to the HTML, but dynamically on the front end. It’s not actually changing, you know, your underlying files that are making up your website.

Natalie G: And that still poses an issue for users.

Natalie M: It can cause a lot of issues for users. And another thing that these overlays tend to do that’s extremely deceptive is they interact with accessibility scanning tools.

So if you’re using one of the popular browser add-ons, for example, to scan your website for accessibility issues—like AXE or WAVE—you could do a little experiment where you scan your page and it says, “Oh, you have 50 accessibility issues.” And then you install an overlay, and it says, “Oh, now you only have 10,” and you think, “Oh, well, great. The overlay fixed 40 issues,” but it didn’t actually because those scanning tools are just using JavaScript too. And so the overlay is actually interfering with the scanner script to prevent it from finding those issues. They’re not gone. It just stopped the scanner from finding them.

Natalie G: Oh, I see. So, it’s not even just for website owners. It’s like even for accessibility professionals—it interferes with their own work.

Natalie M: It definitely can. And if you look around, you’ll find all kinds of browser add-ons for disabling these overlays because in addition to being deceptive, they actually kind of get in the way and make websites harder to use for people with disabilities. So people who are using assistive technology actually have a harder time using your website when you’re using one of these overlays than if you weren’t using it at all, which is the opposite of what your intention is, right? You want to make it easier, but you’re making it more difficult. You’re actually putting up more barriers, and people just aren’t aware that they’re doing that. And it’s really unfortunate.

Natalie G: Yeah, I guess that’s the worst part of it is that a lot of people who use those tools, they’re not even aware of what they’re doing. They feel like they’re doing a good thing.

Natalie M: Yeah. Yeah, absolutely. I’ve definitely talked to a lot of web developers who, after seeing me give a talk, they’ll say like, “Oh no, I just told all of my clients to just install one of these. And now I have to go back to them all and tell them, no, I’m so embarrassed.”

Natalie G: Oh my goodness.

Natalie M: Yeah, I was actually on a call with a client who I’m doing some accessibility testing work for, and they’re having the original developer who built the site do the remediation work for the issues that we’re uncovering. And on the call, the person who runs this agency said, “Well, why don’t we just install one of these overlays instead of doing all this work?”

I had to explain to her why and to please stop telling her clients to do that.

Natalie G: Oh brother. I almost feel like people try to see accessibility as like a layer on their site, but it’s really not. It’s like, “Install a security plugin,” like, “Oh, that fixes a lot of your security issues. It adds a little layer of security.” But accessibility is not a layer—like, it’s not something you can just apply over your site.

Natalie M: No. Yeah. It has to be built in, and you can’t just layer that on later.

Natalie G: Yeah, maybe security you can layer on later, or caching.

Natalie M: Yeah. I’m not a security expert, but it does seem to at least work a little bit.

Natalie G: Do you want to go over or paraphrase some of the statements that we found on some of these overlay websites just to give the audience a taste of the statements?

Natalie M: Yeah. Yeah. So, “Oh, you can leverage the power of our AI-powered accessibility widget.” That should just be red flags all over. AI is like, hmm, that’s like an intern on their first day of work. It’s not that good. You have to check its work. It can’t completely fix accessibility issues. So anybody who’s claiming that they’re using AI to fix accessibility issues, that should be a big red flag.

We have one saying, “Over 50 innovative accessibility features.” I don’t even know what that means. What are 50 accessibility features? I think it might be those tools to change color, contrast, and font size, but like there are 50 of them?

Natalie G: Yeah, what are they doing? There’s font-size, contrast changes..

Natalie M: It could do text-to-speech, but I actually don’t think they even do that. That I’ve seen, but maybe they do. But still, we’re at three tools, and we’re running out of ideas.

Natalie G: Oh, I’ve seen some do like, changing the font to that dyslexic-friendly one.

Natalie M: Oh, sure. They do try to add alt text. I don’t know if they’re counting that as an accessibility tool.

Natalie M: Which, I’m not sure that would be bad, but it definitely has to be reviewed, for sure.

Natalie M: Oh yeah. You can’t just let an AI bot run free on your website and not follow up and see what it’s doing. You definitely need to check on it. And, you know, maybe in 10 or 20 or 50 years, AI will be able to fix things like that. But right now, it just cannot.

Natalie G: Mm-hmm. Yeah. The way it’s built right now is like, literally a layer over your site.

Natalie M: Yeah.

Natalie G: To edit the files of your site to make any difference.

Natalie M: And it can’t do that. It doesn’t, you know, it doesn’t have file access. So it’s all stuff that it’s trying to do as a JavaScript on top of your existing website, and it just can’t. Even if I, as somebody who’s worked in accessibility for a long time, were to try to sit down in front of a website, and you said to me, “The only tool you can use to fix this site and remediate it is to add a JavaScript file to the site,” I wouldn’t be able to fix all of the accessibility issues. Even really carefully thinking through things and understanding the context of things, right? I couldn’t fix all of the accessibility issues by just adding a JavaScript, and a robot certainly can’t do it either.

Natalie G: I mean, that’s even true for a lot of the work that we do. We troubleshoot on people’s websites. Like, there’s a lot of things we can’t figure out and help you with unless you let us log in, at the minimum.

Natalie M: Yeah. Yeah, it’s really difficult.

Natalie G: Do you want to go over the next paraphrased one that we were giggling about a lot earlier?

Natalie M: Oh, “Simplify web accessibility with advanced AI and computer vision.”

Natalie G: Computer vision?

Natalie M: What is computer vision? I don’t even know what that is. They’re just making up words now. And then, the very dangerous and misleading, “Streamlines the process of achieving compliance.” You are definitely not achieving compliance with one of these tools, but people think they are. I have, over the years, talked to very many clients who said, “I don’t understand why I got this letter about a lawsuit for accessibility on my website. I have this overlay.” And they’re very frustrated because they have this feeling, right? Like, “I did what I was supposed to do. I put this thing on here, and it said it would fix it all, but now people are saying that my website’s inaccessible. I don’t understand.”

Natalie G: Yeah, speaking about how it doesn’t achieve compliance, do you want to go over the lawsuits and these people who are completely unaware but get sued anyway?

Natalie M: Yeah. Yeah. There have been quite a few cases where people had these overlays installed and they still got lawsuits, which is fair enough because their site isn’t accessible. Somebody tried to come to their website and wasn’t able to use it. And in fact, the overlay may have made it even more difficult for them to get to the content of the website than if they had not done anything at all. So that’s fair enough.

There tends to be a lot of wording in the advertising of these overlays saying that they will protect you from lawsuits, and they just don’t. That’s completely inaccurate.

Natalie G: I’ve seen a lot on their websites where they’re like, “Oh, we’ll cover all the legal fees…”

Natalie M: Oh yes, I know what you mean. They even say they’re so confident that they’re going to protect you from lawsuits that they have wording on their website like, “We’ve got your back.” Basically, if somebody does try to sue you, they’ll help you out. I don’t know exactly what they claim there—if they’re going to pay your legal costs, or what they’re claiming they’ll do—but the customers I’ve spoken to who have gotten sued or received demand letters have not gotten any help from these overlay companies.

Natalie G: Yeah, I’d be interested to see if someone reached out to them, like, “Hey, I’m getting sued, I need some compensation for these legal fees,” and they just… nothing. No reply.

Natalie M: Yeah. The unfortunate thing is that these companies tend to have a lot of money to throw around because they get funding and investment from venture capitalists. And they could make a lot of strides by investing that money into their product and making it better.

What they’re trying to do isn’t completely impossible. There are some accessibility issues that they could help fix or help people identify. They could probably work on expanding that capability. But instead, they’re investing all that money into misleading advertising campaigns.

And they’re also, unfortunately, suing accessibility professionals who speak up and say, “Hey, these tools are doing something misleading,” which is really, really unfortunate. And just the worst use of those funds, I think. If you have the money, why wouldn’t you just make your product better?

Natalie G: Mhm. And one of the bigger overlay tools right now is getting some backlash, right?

Natalie M: Yeah, the FTC here in the United States has imposed a fine on one of the overlay companies of $1 million, which is a tiny fraction of their revenue and profits, but it’s something. If you’re interested in participating in that, as of this recording through February 5th, 2025, that ruling is open for public comment. So it’s open for 30 days, and then they’ll make a final decision on whether or not to impose the fine.

If you believe, like I do, that they should definitely get that fine, you can go and leave your comment on the FTC’s ruling. We’ll put the link in the show notes or comments below.

Natalie G: Yeah. Now the only hope is that they do something about that after they get fined.

Natalie M: Yeah. Hopefully that $1 million is enough to deter them from continuing down this path, and maybe they’ll shift directions.

Natalie G: Mhm. I guess the hard thing is that advertising an all-in-one solution is so much flashier.

Natalie M: I get that. It’s a lot harder to market a tool that says, “Hey, it can fix a few accessibility issues.”

Natalie G: Mhm.

Natalie M: It’s a lot harder. But it would be more honest, and I think it would give people a much better picture of what the tool actually does and what they can expect after they install it.

It’s fine if they want to add tools for changing font sizes or colors. There are people who would find that useful, and it’s not hurting anything. It’s just the claims that AI is going to fix everything. And the way it interferes with assistive technology, accessibility checkers, and just blocks people from using the website is really unfortunate.

Natalie G: For people getting sued, is there a particular type of website, or is it really just any website on the internet?

Natalie M: It’s really just any website on the internet. And we tend to see these lawsuits go in batches. Like, a year or two ago, a whole bunch of wineries in upstate New York suddenly got hit with lawsuits.

Some less-than-honest lawyers will open a website, run an accessibility scanning tool, and if it finds issues, they have a group of clients they use to file lawsuits. Then they send out a bunch of demand letters.

That’s a topic for another episode—the downside of having a law where the only enforcement is through lawsuits.

Natalie G: Yeah. Because wouldn’t it be nicer if they just reached out and said, “Hey, I can’t use your website”?

Natalie M: Yeah. But that would require the company who owns the website to respond nicely and say, “Oh my gosh, absolutely, we’ll fix those issues.” But that often doesn’t happen, either. So there’s a whole chain of dominoes falling here. Hopefully, one day we’ll fix it.

Natalie G: Little by little, if everyone does their part. What should website owners do instead of using overlays?

Natalie M: They should figure out how to actually fix accessibility issues on their websites. If they’re building a new website, find someone who can make it accessible from the start.

If they already have a website and aren’t planning to redesign or relaunch it soon, they can use accessibility scanners like AAArdvark to identify issues and start fixing them little by little. Doing something is better than doing nothing.

Natalie G: Yes. To end the show, do you have any last notes?

Natalie M: If you’d like to learn more about overlays and how they work—or don’t—there’s a website called overlayfactsheet.com. You can read about overlays from a neutral source who’s an accessibility expert, and you can sign a petition saying that no one should use these tools.

Natalie G: And I also have one more note.

Natalie M: Okay.

Natalie G: If you’re interested in seeing how to find manual issues and how to fix them in real-time, we’re going to start live streaming this process. Right, Natalie?

Natalie M: Yes, we are.

Natalie G: So later today, Natalie will have her first stream.

Natalie M: Yeah. I don’t know if anyone will hear this podcast in time, but it won’t be my only stream. Just keep an eye on our YouTube channel and LinkedIn page for future streams.

Natalie G: Alright, everybody, that’s the podcast. I don’t know what episode we’re on anymore. Episode 9?

Natalie M: I think it’s Episode 9.

Natalie G: Okay, Episode 9 of the AAArdvark Accessibility Podcast. Thank you so much for joining us today.

Share the Post: 

[Share on LinkedIn](https://www.linkedin.com/shareArticle?mini=1&url=https%3A%2F%2Faaardvarkaccessibility.com%2Fwhat-are-accessibility-overlays-and-why-are-they-bad%2F&title=What%20Are%20Accessibility%20Overlays%20and%20Why%20Are%20They%20Bad%3F&source=https%3A%2F%2Faaardvarkaccessibility.com)[Share on X (Twitter)](https://twitter.com/intent/tweet?text=What%20Are%20Accessibility%20Overlays%20and%20Why%20Are%20They%20Bad%3F&url=https%3A%2F%2Faaardvarkaccessibility.com%2Fwhat-are-accessibility-overlays-and-why-are-they-bad%2F&via=aaardvarka11y&related=aaardvarka11y)[Share on Reddit](https://www.reddit.com/submit?url=https%3A%2F%2Faaardvarkaccessibility.com%2Fwhat-are-accessibility-overlays-and-why-are-they-bad%2F)[Share on Facebook](https://www.facebook.com/sharer/sharer.php?u=https%3A%2F%2Faaardvarkaccessibility.com%2Fwhat-are-accessibility-overlays-and-why-are-they-bad%2F)[Share on Email](https://aaardvarkaccessibility.com/cdn-cgi/l/email-protection#2f104d404b5612660a1d1f5d4a4e4b0a1d1f5b47465c0a1d1f5f405c5b0a1d1f40410a1d1f6e6e6e5d4b594e5d440a1d1f4e414b0a1d1f584e415b4a4b0a1d1f5b400a1d1f5c474e5d4a0a1d1f465b0a1d1f58465b470a1d1f56405a010a1d1f674a5d4a0a1d185c0a1d1f5b474a0a1d1f434641440a1c6e0a1d1f475b5b5f5c0a1c6e0a1d690a1d694e4e4e5d4b594e5d444e4c4c4a5c5c464d4643465b56014c40420a1d6958474e5b024e5d4a024e4c4c4a5c5c464d4643465b560240594a5d434e565c024e414b02584756024e5d4a025b474a56024d4e4b0a1d69090c1f1c17145c5a4d454a4c5b126c474a4c440a1d1f605a5b0a1d1f7b47465c0a1d1f6e6e6e5d4b594e5d440a1d1f6e4c4c4a5c5c464d4643465b560a1d1f6d4340480a1d1e0a1d1f78474e5b0a1d1f6e5d4a0a1d1f6e4c4c4a5c5c464d4643465b560a1d1f60594a5d434e565c0a1d1f4e414b0a1d1f7847560a1d1f6e5d4a0a1d1f7b474a560a1d1f6d4e4b0a1c69)

