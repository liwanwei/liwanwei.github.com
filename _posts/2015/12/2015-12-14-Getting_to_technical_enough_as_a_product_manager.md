---
layout: post
category : PDM
tagline: "产品经理定位"
tags : [产品经理]
title:  "Getting to technical enough as a product manager"
comments: true
---	

#Getting to "technical enough" as a product manager

> "Why are you the product manager for search if you’re not technical?"

The question was posed with the blunt earnestness you come to expect of social interactions in the Valley. And it was a fair one, to the asker’s credit, though maybe not something I would have fired off within the first five minutes of meeting someone.

Conventional wisdom, and most job descriptions for product managers, say that candidates should have a “[BA/BS in Computer Science or related technical field, or equivalent practical experience.](https://www.google.com/about/careers/search#!t=jo&jid=42155&)” The latter usually means a side project you can point to and say “I built that.” There are notable exceptions to the rule, but being technical is still more of a must-have than a nice-to-have.

Recently, companies have started to reframe this requirement as “Product managers should be technical enough.” Note the language in these job descriptions (kinda fun to try to guess the company):

- [You are technical enough to ask engineers good questions about architecture and product decisions alike](https://stripe.com/jobs/positions/product-manager/).
- [Excellent communication, including the ability to converse at a technical level](https://asana.com/jobs/product-manager).
- [Deep analytical skills. A degree in computer science (or programming experience) is ideal, or a love of data, edge cases & analysis](https://clever.com/about/jobs#product-manager).


Though I'm a bit biased, I think this shift is generally a good thing, and will only accelerate as awareness of and demand for the role grows. Product management is as much art as it is science, psychology as it is statistics, big picture as it is the smallest of details. The day-to-day responsibilities, and technical bar, varies widely depending on the industry and size of the company, as well as the part of the product you work on. At the same time, the qualities that make someone a universally respected PM rarely have to do with technical expertise (“That’s a waste of a good engineer,” as some would say).

But the question remains—what does it mean exactly to be “technical enough”? How do you get there? And how do you build credibility with your team in the meantime?

When I transitioned from marketing to product management three months ago, I realized the internet had surprisingly little to offer on this subject. I want to share my experience trying to answer these questions while navigating the first 90 days as a PM at Pinterest, focused primarily on search. Hopefully it’s helpful to other product managers coming from a non-technical background, and kickstarts more conversation.

The rest of this post is broken out into two parts, reflecting my general onboarding approach:

1. Establish a baseline of technical understanding and invest more over time.
2. Build trust and credibility by figuring out how you can add immediate value.


###Establish a baseline of technical understanding and invest more over time

First, what does it mean to be “technical enough” as a PM? There will be many opinions here, but I think of it as the ability to do the following, in order of difficulty:

1. Trace a user issue (or set of issues) back to the underlying problem.
2. Estimate how long it will take to build A vs. B.
3. Anticipate implementation challenges with a particular proposal.
4. Brainstorm potential solutions to technical problems.
5. Identify opportunities that arise from new technologies.



The relative importance of these criteria will vary depending on your product—it might be more critical for a consumer app to stay on top of new technology, for instance, while B2B companies should be extra mindful of project scope to hit scheduled release dates—but it’s reasonable to expect a PM to be able to weigh in on all these issues.

With a better understanding of where we need to go, the next question becomes how do you get there? Some steps that I’ve found helpful, roughly in order of importance:

###Start from a place of curiosity

This is the only must-do on the list. A genuine curiosity about technical problems will take you a long way; without it, things are a non-starter. It’s possible to cultivate this curiosity to a certain extent, but I’d try and get signal here during the interview process. [Ellen Chisa](http://blog.ellenchisa.com/) has a great post on this topic if you’d like to read more.

###Appreciate the creativity inherent in engineering

This point flows directly from the one before. You don’t have to poke far below the surface to realize that, at its core, engineering is about creating something from nothing, and comes with all the messiness that’s part of any subjective process. Behind every effort to bring a feature to life, there’s an engineer making dozens of judgment calls, weighing subtle tradeoffs, and thinking through implementation details and edge cases. Failing to understand this dynamic deprives engineers of the autonomy and ownership needed to do their best work.

###Set aside time early on to pick an engineer’s brain

Read everything you can get your hands on in the first few days, keep a running list of questions, and then grab a whiteboard and time with an engineer to run through them. Get enough of a baseline understanding to ask intelligent questions, but don’t put off the last part for too long. There’s only so much you can absorb from staring at a screen, and the initial investment of a team member’s time will go a long way.

###Synthesize what you’ve learned into a shareable format

At this point you’re probably swimming in a sea of acronyms and scribbled diagrams[缩写和草图]. Synthesize[合成] all this new information by writing it up in a doc. Share it with new hires as an onboarding resource. Even better, find an opportunity to present the information to another team, e.g., give a Search 101 presentation to partner managers. This is a great way to test your understanding and highlight areas where you need to dig in more.

###Use feedback and bug reports to pattern match different issues

Returning to our definition of what it means to be “technical enough,” the first criteria is being able to trace a set of user issues back to the underlying problem. **One way to do this is by pattern matching feedback and bug reports.**
As a PM, you have the honor of being first responder for product feedback. On any given day you might field multiple reports about things that are confusing or broken. A coworker slacks you, “Including apostrophes in my search doesn’t return any suggestions.” Then your mom emails, “Tried searching for ‘williams-sonoma’. Can’t find it :(”

If you’re organized with your issue tracking, two things happen over time:

1. You pick up on the vocabulary that engineers use to discuss certain bugs.
2. You start to link issues together as symptoms of the same root problem.


So the reports from your coworker and mom would get rolled up under the parent issue: “Autocomplete normalization logic doesn’t handle punctuation.” Through this process you’ll also develop a sense for the relative magnitude and priority [相对大小和优先级] of different issues.

###Familiarize yourself with bits of the code base

No need to go crazy here; the goal is to be able to answer simple questions like where and how we’ve defined a particular variable, without having to bother an engineer.

###Focus on core concepts

Every field has a set of concepts[概念] that crop up[突然发生] again and again, e.g., recall vs. precision in search, cardinality in data modeling, etc. Identify what these are forcomputer science generally and your product area specifically, to help prioritize your learning.

###Develop a thick skin

Cunningham's Law states, "The best way to get the right answer on the Internet is not to ask a question, it's to post the wrong answer." In many ways this is the perfect metaphor[隐喻] for the role of a PM—it’s your job to come up with the initial spec or Google Drawings mock that everyone else then picks apart. The point isn’t that you proposed[提议] a crappy[没价值的] strawman[稻草人] (most first drafts are), but that this gets the conversation started.

###Build credibility by figuring out how you can add immediate value

Learning any new skill takes time, but when it’s happening on the job, you don’t have the luxury of being a full-time student. You have to identify areas where you can make an immediate impact and start contributing, while you’re ramping up. Hopefully this isn’t too difficult, as part of the reason you were hired in the first place is because of the complementary[互补的] skill set you bring to the table. Some things to consider:

###Dig into the data

There’s this idea that each function has a superpower; some quality that, when wielded, makes other people jump to work with you. For designers, it might be the ability to quickly produce a range of high fidelity explorations[高保真原型]. For engineers, maybe it’s the ability to hack together a prototype but also know when to invest in clean, extensible code.

**For product managers, I think the closest equivalent is data fluency.** Any time someone asks, “Do we know how many people use ABC feature?” and you can say, “Yeah, it’s roughly 123,” you build **credibility**. This is probably why product analyst positions have become one of the more common feeder roles into product management.

Practically speaking, being data fluent means knowing:

- Which frontend and backend events are logged, and how
- Where this data is stored
- How to query the data
- How to analyze experiment results
- Experiment design best practices


###Do the blocking and tackling work that keeps trains moving

Run efficient meetings. This usually means:

- The purpose of the meeting is clear to everyone invited.
- All necessary decision-makers are present.
- You’ve set the right level of context at the beginning of the meeting.
- There are clear action items and owners at the end of the meeting.
- You take notes and share them promptly[迅速地].

Err[犯错误] on the side of over-communicating and over-documenting. Know when email is the best communication channel and when it’s not. Keep track of common questions you get from other teams and centralize[集中] the answers in a self-serve resource.

Ask your engineers: What are you doing now that you’d rather not do? Anything you’re able to take off their plate—filing bugs, specifying logging requirements, pulling data, responding to requests from other teams—do.

###Lean into your experiences and strengths

Early on, I tried to avoid drawing attention to my marketing background because I didn’t want to remind people that I wasn’t technical. In retrospect[回顾] this was pretty silly, as my unique set of experiences was partly why I was hired. Whether it’s shipping an email campaign, running a quick survey, or setting up user interviews, build momentum by accumulating small wins.

###Provide a shared framework for decision-making

Remember the superpower metaphor from before? This one’s a close second to knowing your data. Good PMs bring clarity to every conversation they’re involved in. They have a knack for asking incisive[一针见血地;敏锐的] questions. They can tell you what problem we’re solving and why, how we measure success, and the order of operations to get from here to there. More importantly, everyone on their team can apply this shared framework to make the best call even when the PM isn’t there.

###Take the time to give your team broader context

As a product manager, you’re often the only representative from your team sitting in on a certain meeting or cc’d on an email exchange. Keep everyone updated on these interactions with other parts of the company. There’s often no immediate benefit to doing so, but the cumulative[累积的] context makes it easier to discuss controversial decisions down the road. Over time, your team will start to proactively come to you with questions and concerns.
_______________________________________________________

转自[lulucheng的个人博客](http://www.lulucheng.com/2015/11/28/getting-to-technical-enough-as-a-product-manager/)