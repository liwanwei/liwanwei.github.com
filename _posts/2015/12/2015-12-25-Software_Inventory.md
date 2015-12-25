---
layout: post
category : PDM
tagline: "产品经理"
tags : [产品经理,Strategy]
title:  "Software Inventory"
comments: true
---	


#Software Inventory[软件清单]
by Joel Spolsky

**中文概要：**

1. 分类功能堆积清单；
2. 减少bugs记录进bugs数据库（而非bugs日志）；
3. 让未上线功能在更短的时间上线，做好管理规划，发现瓶颈，敏捷开发的思想；

Imagine, for a moment, that you came upon a bread factory for the first time. At first it just looks like a jumble[杂乱的一堆东西] of incomprehensible[不可思议的] machinery with a few people buzzing around. As your eyes adjust you start to see little piles of things that you do understand. Buckets[桶] of sesame[芝麻] seeds. Big vats of dough[生面团]. Little balls of dough. Baked loaves[大块烤过的食物] of bread.
[mothlee：看到的东西随着你对产品对市场的而理解而渐渐加深。看到的东西不再是分散的一件件东西，一个由一件件物品所堆积起来的一个个小模块。]

Those things are inventory. Inventory tends to pile up between machines. Next to the machine where sesame seeds are applied to hamburger buns, there’s a big vat of...sesame seeds. At the very end of the assembly line, there are boxes and boxes of bread, waiting for trucks to drive them off to customers.

Keeping inventory costs money. Suppose your bakery has six 50-ton silos[粮仓] to store flour. Whenever they empty out, you fill them up. That means on the average day you have 150 metric tons of wheat flour in stock. At today’s prices, you’ve tied up $73,000. Forever.

Inventory may have other costs too, like spoilage[损坏，糟蹋]. Flour lasts for months, but the minute bread comes out of the oven it starts dropping in value; after 24 hours it’s nearly worthless.

Why keep inventory at all? Because there are costs associated with running out of things, too. If sesame seeds take two days to order, and you run out of sesame seeds, you are out of the hamburger bun business for two days. Inventory provides a buffer that prevents any part of the process from stalling[使…熄火]. There are modern algorithms to optimize how much buffer you need at every point (read up on Toyota’s lean production system and the Theory of Constraints to get started).

Why do I care about any of this? The software production process has several major “inventory” accumulation points, itself. Stuff accumulates at those points and ends up wasting a lot of time and money.

“What? How is software like a factory?” you ask.

Think of product ideas as the raw material. Depending on your process, product ideas may go through several assembly line points before they are delivered as finished features to the customer:

1. A decision-making process (should we implement this feature?)
2. A design process (specs, whiteboards, mockups, etc)
3. An implementation process (writing code)
4. A testing process (finding bugs)
5. A debugging process (fixing bugs)
6. A deployment process (sending code to customers, putting it on web server, etc)

(PS No, this is not “waterfall.” No it isn’t. Is not. Shut up.)

1. 决策过程中（我们要实现此功能？）
2. 设计过程（规格，电子白板，实物模型等）
3. 一个执行过程（编写代码）
4. 测试过程（发现错误）
5. 在调试过程中（修复bug）
6. 一个部署过程（发送代码到用户，把它的Web服务器上，等等）

In between each of these stages, inventory can pile up. For example, when a programmer finishes implementing their code (stage 3) they give it to a tester to check (stage 4). At any given time, there is a certain amount of code waiting to be tested. That code is inventory.

The “cost” of code inventory is huge. It might add up to six or twelve months of work that is stuck in the assembly line and not yet in customers’ hands. This could be the difference between having a cutting-edge product (iPhone) or constantly playing catchup (Windows Phone). It’s nearly impossible to get people to buy Windows Phones, even if the iPhone is only six months better. A lot of markets have network effects, and being first has winner-take-all implications. So getting rid of inventory in the development process can make or break a product.

Let’s go over the three places most inventory accumulates.

##Feature backlogs. 

Every product attracts new feature ideas, and you can’t implement ideas as fast as you can think them up, so you write them down, and this list is called the feature backlog. A lot of the ideas on the backlog are bad ideas, and you merely wrote them down to avoid hurting the feelings of the people who thought them up. Backlogs make everyone feel good.

The trouble is that 90% of the things in the feature backlog will never get implemented, ever. So every minute you spent writing down, designing, thinking about, or discussing features that are never going to get implemented is just time wasted. **When I hear about product teams that regularly have “backlog grooming” sessions, in which they carefully waste a tiny amount of time and mental energy every day or every week thinking about every single feature which will never be implemented, I want to poke my eyes out.**[mothlee：这样子做实在是浪费时间]

- Suggestion: Do not allow more than a month or two of work to get into the feature backlog list. Once the backlog is full, do not allow new items to be added unless you remove an item. Do not spend any time speccing, designing, or talking about backlog items: the backlog, in fact, should be seen as a list of things you are not allowed to talk about or work on.[超过一两个月工作量的功能点就不要记录在功能积压列表。一旦列表满了，不要再往里面增加新的功能，除非你剔除掉一些。不要花时间speccin，设计或者谈论功能挤压表上的物品。事实上，功能挤压清单应该被视为是你不能谈论或工作的事情的清单。]

## The bug database

The bug database is obviously a great thing to have. Bug reports should be complete, accurate, and actionable[可控告的]. But I have noticed that in many real-world companies, the desire never to miss any bug report leads to bug bankrupcy[破产], where you wake up one day and discover that there are 3000 open bugs in the database, some of which are so old they may not apply any more, some of which can never be reproduced, and most of which are not even worth fixing because they’re so tiny. When you look closely you realize that months or years of work has gone into preparing those bug reports, and you ask yourself, how could we have 3000 bugs in the database while our product is delightful and customers love it and use it every day?[时间花在了没有效益增进的地方] At some point you realize that you’ve put too much work into the bug database and not quite enough work into the product.

- Suggestion: use a triage[分类] system to decide if a bug is even worth recording.
- Do not allow more than two weeks (in fix time) of bugs to get into the bug database.
- If you have more than that, stop and fix bugs until you feel like you’re fixing stupid bugs. Then close as “won’t fix” everything left in the bug database. Don’t worry, the severe bugs will come back.


- - - 

- 建议：用分类制度，以决定是否一个错误，甚至值得记录。
- 不要让两周以上的bugs（以固定时间）进入bug数据库。
- 如果bugs更甚于两周，停止你手上的工作并修bugs，直到你觉得你修复的bugs是低级的bugs。接下来将它们以接近“不会解决”的状态留在了bug数据库。别担心，严重的bug会回来的。

##Undeployed features

There are still a lot of teams doing quarterly or annual releases, usually because their deployment process is expensive. Operating systems, or anything where software has to be installed by every user, is usually batched up.

This is one of the most expensive forms of inventory: unshipped feature inventory. It could be earning you money, but it’s sitting on the shipping dock of your factory, while the guy down the street already has a product that does that exact same thing.

Sometimes, perniciously[有害地], you don’t even feel the pain, because everyone on your team has been dogfooding the new version for months. I’m sure everyone at Microsoft has been happily using Windows 8 for a year now, so they don’t really feel, on a day to day basis, the pain of OEMs[原始设备制造商（Original Equipment Manufacturers）] trying to sell Windows 7 in a Mac OS X Lion world.

- Suggestion: Don’t let completed features pile up in ways that don’t make you money. Work on your deployment process so that you can get customers features in months rather than years. If you’re already shipping monthly, figure out how to ship weekly. Keep pushing the bar on more and more frequent deployment of smaller and smaller changes.
- - - -

- 建议：不要让已完成的功能以不挣钱的方式堆积在一次上线。在部署过程中的工作，让你可以在几个月而不是几年内把握客户的特点。如果你已经实现每月上线，弄清楚如何每周上线新的功能。接着继续细化，越来越小的变化以及越来越频繁的部署。[mothlee：敏捷开发？]

So, where am I going with this? We’ve had all three kinds of inventory at Fog Creek: **crazy long backlogs, overambitious[野心太大的] bug databases, and features which got stuck for a year waiting for the next release to go out.** All of these snuck up on us. I realized that we needed a system to constrain inventory so it doesn’t build up. 

My original idea was to make a product called Five Things. It was going to be a project manager where everybody was allowed to have five things assigned to them: two things they were actively doing, one thing that was “up next”, and a couple more that they were planning. That exact design idea didn’t go anywhere (but if you want to build it, go for it), but it did evolve into [Trello](http://trello.com/).
![trello](http://7xkqbu.com1.z0.glb.clouddn.com/09trelloOnTrello-thumbnail.png)

Trello works great for a reasonable amount of inventory, but it intentionally[有意地] starts to get klunky[残旧的] if you have too many cards in one list. And that’s exactly the point: it makes inventory visible so that you know when it’s starting to pile up. (Click on the image at the right to see the Trello team’s own development board).

**Every day you look at your Trello board and see that there are seventeen completed features that are totally ready to ship but which haven’t shipped for some reason, and you go find the bottleneck[瓶颈；障碍物] and eliminate[消除；排除] it.**

**Every time somebody suggests a crazy feature idea, you look at the Feature Backlog and realize it’s just too long, so you don’t waste any time documenting or designing that crazy idea.**
[mothlee：Trello类工具可以这样子用]
And hopefully, you’ll spend less effort working on things that never see the light of day. “Backlog grooming.” Sheeeesh.


Want to know more? You’re reading [Joel on Software](http://www.joelonsoftware.com/), stuffed with years and years of completely raving mad articles about software development, managing software teams, designing user interfaces, running successful software companies, and rubber duckies. 

About the author. I’m Joel Spolsky, co-founder of Trello and Fog Creek Software, and CEO of Stack Exchange. More about me.

转自[Joel Spolsky](http://www.joelonsoftware.com/items/2012/07/09.html)