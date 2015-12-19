---
layout: post
category : PDM
tagline: "产品经理"
tags : [产品经理,沟通技巧]
title:  "How to Work with Engineers - A Cheat Sheet for Designers"
comments: true
---	

#How to Work with Engineers - A Cheat Sheet for Designers

**文章要点：**

- 认识到工程师是将想法转化成现实的转化器
- 只需要让一两位工程师相信你，你就可以将原本无用的想法变成现实
- 如果工程师能欣赏你的设计，那么一切都会变得很简单
- 了解计算机编程的极限
- 帮助工程师在任何时候了解最终的产品会变成什么样子
- 坐的离工程师近一点，再近一点
- 完善自己的产品，应该考虑到
	1. 产品是否国际化；
	2. 产品的错误提示，例如网络连接丢失，数据库出错等；
	3. 用户使用的一些极限情况；
	4. 考虑屏幕适配；

Once, a long time ago, I was a product manager. Then, I was an engineer. For the past seven years, I’ve been in design. Every single day, I work with people in all of these roles. Every single day, I find new ways to appreciate the responsibilities, challenges, and art behind each of these three pillars of product development. Engineers are the magicians[英伦魔法师] of the crew, who, with a few taps of their fingers, take the plans and the pixels and Voila! A working implementation. As a designer, how do you best keep up with their meme-savvy, self-deprecating[自贬的；自谦的], script-loving ways? Keep reading.

##Engineers are the translators of ideas into reality.

Engineers make every good proposal real, and this fact should never, ever be forgotten. Even if your company has five, or five hundred, or five thousand engineers, engineers are not a ‘resource’. They are the builders of the foundations, the keepers of everything that makes your product tick. They make it work. They make it work fast. They make it robust[强健的] and reliable and scale it to millions and billions of users. Generally, it’s the engineers who innovate[改革创新], who push technology forward with new algorithms, who make sense of the trillions of inputs available and turn those into some semblance[外表] of meaning.

All this is to say: engineers are the shit.

Which means…

##Want to make stuff[无用的想法] happen? All you need to do is just convince one or two engineers.

Really, that’s all it takes. Many a legendary product story starts this way: a couple friends, a weekend, a few cans of beer, some hacking. The PM comes later. Managers come later. Start with the basic building blocks—an idea, a design, and an implementation. That’s why it pays to have close ties with engineers.
Or, imagine this scenario[剧本]: some small part of your product irks[厌倦] you. Like reallyirks you, in an itch-in-an-inconvenient-place kind of way. Something about the design is just plain[纯粹的] wrong. What should you do?

A. Bring it up at your next team meeting where it’ll get put on a list to be prioritized by a team that triages those sorts of things so they can assign it to some future engineer after she’s joined and needs a couple ‘practice’ tasks to get through.

B. Be pretty tight with an engineer and walk over to her desk. Ask her to spend 5 minutes fixing the thing. Watch her submit the diff. (Possibly you may need to barter[物物交换] a t-shirt design for her 80s cover band or something, but you are a pro with Illustrator.)

Guess which version gets your thing fixed the fastest?

That said…

##Things go easier if the engineer you’re working with appreciates the value of good design.

It’s amazing when you’re working with an engineer who knows how to fill in the blanks on a mock without asking you about every little detail because even though you forgot to specify how many pixels are in the margins, she opened Photoshop and measured it herself. It’s incredible when she throws in a suggestion that makes the design even better. It’s stupendous[惊人的] when, after she’s done implementing the first pass, the implementation looks virtually indistinguishable[不能区别的] from the mock, that’s how precise and detailed she is.

How do you work with such engineers? Well, you can hire them. Lucky for you if you can, because awesome UI-oriented engineers are in high demand.

Or you can help every engineer you work with develop an appreciation for good design. How? Don’t just throw mocks over the fence—explain what you’re doing. Teach them about your values, and why you think the design you’re proposing is worth building. Help them learn how to tell if their implementation matches the mock exactly. Talk to them about what’s going on in your head when you say something looks bad.

The relationship building matters here. People shift their values and priorities based on conversations with other people. It’s an old-school but effective way to do things. (“[Slow Ideas](http://www.newyorker.com/magazine/2013/07/29/slow-ideas)” from the New Yorker is a thoughtful, excellent read about this strategy.)

Plenty of engineers don’t come to the table with an eye for design details, but most care about the user experience and want to make it better. I’m not saying every engineer will enjoy doing detailed UI work, but it always helps to expand on the why of a design.

Because the more excited an engineer is about a design—the more they understand its rationale and see its value—the quicker and better it’ll be implemented.

##Save yourself time; understand engineering constraints[限制] early.

As designers, it’s easy to get wrapped up in the world of what-ifs. What if we could read your mind here and know exactly what you wanted to see and showed it to you? What if when you tapped on this button, it explodes into a flurry of particle effects and fire?

Don’t go through the heartache of falling in love with a design that’s out of the question because you didn’t understand the technical or time constraints early enough. (And even if it is a design that’s worth going to bat for, your case is going to be much stronger if you do understand the constraints.) The worst thing that can happen is that you spend your time perfecting a design that has no chance of working out. Good designers are scarce enough as is, and there are enough big problems that we don’t need that kind of inefficiency.

So the next time a brilliant idea possesses you but you have a sneaking[机密的] suspicion[猜疑] that it might be hard to build, don’t wonder. Ask the engineer.
The inverse of this holds as well…

##Save the engineers time; help them understand how final the design is at any given stage.

If you give an engineer a design to build but you’re not confident how well it’ll work out until you get to play with the implementation, make sure you let them know that there’s a good chance things will change. Nothing is more annoying to engineers than staying up all night to finish an implementation only to get a memo in the morning that Whoops! The whole design has been transformed! And now they’ll have to throw away all that production-quality code they put painstaking attention into.

Of course, no engineer writes code that never gets thrown away. It’s part of the job, same as design. Good engineers understand that the product development process is messy[麻烦的], and we don’t always know what’ll work until it’s real. Stuff will get changed. Designs will get redesigned. But setting context on what pieces are still exploratory and what pieces are locked down helps engineers figure out how to architect code that is either faster to write or more flexible to modify later.

##The best way to ensure designs are implemented as intended is to work extremely closely with the engineer.

Like, sit right next to them when stuff is getting implemented. I can’t overemphasize how much easier it is to make sure everyone’s on the same page when folks are sitting in the same room. Issues surface and get dealt with much faster.

It’s easy to cast blame when the end product is not something that everyone’s proud of. Oh, my mock was great, but the engineer didn’t implement it correctly. That’s poisonous thinking right there. You, the designer, own the product that goes out to users, not the Photoshop mock on your computer. If something wasn’t implemented correctly, why didn’t you do something about it? Why didn’t you ask the engineer to show you the implementation right after she finished it so you guys could go over it in detail? Why didn’t you check in during the building phase to see if she had any questions about the design? Why didn’t you file a task for her to fix the bug after you saw it?

That’s right. Own it.

##The quickest way to an engineer’s heart is to be complete with your designs.

It’s kind of funny that the word ‘detail-oriented’ is thrown around to describe designers when in fact most design specs miss numerous cases that end up being identified by engineers who have to implement all the branching paths.

Want to be a design hero for engineering? Make sure your design solutions are complete and consider edge cases like:

1. Internationalization: what does this design look like in another language? Notably German with its layout-threatening long words?

2. Error states: what happens when network connectivity is lost; databases crash, etc?

3. User extremes: what does this page look like if the user using this has no information or activity? What about if the user has tons and tons of information or activity?

4. Transitions: what is the precise[精确，恰好] way that screen A becomes screen B? Good tools are mighty helpful here, as described in How to Survive in Design (and in a Zombie[行尸走肉] Apocalypse[世界毁灭；圣经新约之《启示录》；天启；大灾难]).

Not only does designing the above cases inspire confidence that you’ve actually thought through everything holistically, but they help engineers plan out how to architect the system, and give proper estimates[估计] for how long things will take. Not to mention, complete designs prevent last minute scrambles[混乱] to put together shoddy[劣质的] blank states because nobody caught them until it was too late to do something better.

So be a good citizen. Make sure your designs are complete. Don’t just design for some idealized use case. Get out of mock-fantasyland. As every engineer knows, what counts at the end of the day is what ships.

转自[@joulee](https://medium.com/the-year-of-the-looking-glass/how-to-work-with-engineers-a3163ff1eced#.ew8tr6g5y) 

