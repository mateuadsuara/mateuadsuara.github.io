---
layout: post
title:  "Software craftsmanship [Book]"
date:   2015-03-19 15:30:00
categories: 8thlight books
---
I finished reading [Sotware Craftsmanship by Pete McBreen][sc]. Since it is a really big influence to the software industry, I though that would be a good idea to make a blog post with some quotes.

[sc]: http://books.google.co.uk/books?id=JqJQAAAAMAAA

The Gossamer Condor
===================

`quote from pages: 27`

In Paul MacCready's talk at OOPSLA 1998 he pointed out that his team perfected the Gossamer Condor -- the human-powered aircraft that won the Kramer Prize -- by flying it and crashing it. Parts that broke were strengthened; parts that didn't break were made lighter and weaker. Through a very rapid crash-and-fix cycle the team managed to make the Gossamer Condor light enough to fly, yet strong enough not to break while being flown.

One advantage of the Gossamer Condor over previous manpowered aircraft was the facility with wich it could be modified or repaired. After a crash, it could be returned to flying condition within twenty-four hours, enabling the aircraft to be tested extensively and easily modified.

MacCready's talk was inspirational for developers, because it pointed out that creating an evolvable design that can be tested is more effective than trying to create the perfect design on the drawing board.

Software Engineering is for big projects
========================================

`quote from pages: 111, 114, 115, 117`

The software engineering approach can produce near-perfect software but is very expensive. That expense is a natural consequence of the many detail reviews, inspections, and cross-checks. If you attempt to speed up the process drastically or cut back costs, you have stopped doing software engineering and are not very likely to produce near-perfect software.

Software Craftsmanship is a solution to the problem of delivering robust, high-quality applications to users in a relatively short time for reasonable cost. Software engineering is a solution to a different set of problems, involving life- or safety-critical systems, real-time and embedded systems, and systems engineering projects. In these types of problems, fast delivery and reasonable cost are not the driving factors on the project. Incremental development and evolutionary delivery are not feasible strategies.

In software engineering projects, developing the software sooner doesn't help if the hardware is still changing rapidly. Craftsmanship is focused on delivering applications on known hardware to known users.

Small software engineering projects generally tend to be more productive and less risky, than extremelly large projects, but to some extent that can be explained by the difficulty in communicating among large groups of people. The Agile Methodologies focus attention on the individuals in the software development team and the quality of their interactions with their customers and users.

Best practices hinder process innovation
========================================

`quote from pages: 125`

Organizations tend to adopt a process more for the purposes of oversight and control than with a view to improving the effectiveness of delivery. They attempt a "one size fits all" approach because it is easier to treat all projects in the same way. The strange result is that teams end up working off-process just to make progress. Sometimes these off-process projects accidentally stumble on a combination of software development practices that allows them to be spectacularly successful compared with the standardized process. 

The software developers deliver the system to a satisfied user community and are fired up and enthusiastic about spreading the word about how good their process is. If they are enthusiastic enough and create an appropiately catchy name, the new process may be adopted by the rest of the company or outside of the company in different projects. Converts to this new process then become enthusiastic and push to have this new process adopted as the "one size fits all" standard.

The originators of the new process are then places in an awkward position. They understand that they were successful because of the special circumstances of their project that allowed their new process to be successful, yet their converts make claims not backed up by project experience. In many cases, the unfortunate consequence is that the hype wins and the new process is adopted in projects for which it is not suitable.

University degrees do not prepare students for real projects
============================================================

`quote from pages: 95`

  University degrees do not prepare students for real projects. They emphasize the rigorous, technical aspects of software development but fail to cover the important "soft" skills: discuss requirements elicitation techniques or collaborative design.
  Bad teachers set up programming classes to prevent people from asking questions. For example, during a lesson on writing loops, if a student asks a deep question about conditional logic, a typical answer "We will cover that in the next lesson" or "We have already covered that". Neither response helps the student learn and both state that students should not ask questions.

Finding good developers
=======================

`quote from pages: 85`

The challenge is finding people who, although already good, have already adopted the tradition of continual learning. The real test, though, is whether the people who work with them have adopted a similar attitude toward learning and improvement.

Craftsman's reputation
======================

`quote from pages: 38, 42, 59, 142`

When one developer recommends another developer, he is putting his own reputation on the line. By making it personal, software craftsmanship guarantees that recommendations are never made lightly. This kind of peer recommendations means that everyone involved is constantly striving to improve and to become better developers.

It also gives users, customers, and managers better information. Rather than just being told that the person is a "certified Web developer" they will be told the real story -- how the person actually works and how his projects turn out.

Any developer could name a few people with whom they have worked in the past and with whom they would jump at the chance of working again. These are the names any developer can give you without any fear of reprisal.

You also don't want to ask other managers or customers to recommend someone. Their recommendations are worthless because they have no skin in the game. If the person they recommend doesn't work out, they may say "sorry", but that apology will not fix the problem. The people you want to ask are the craftsmen you want but cannot get. Ask them who they would personally recommend. You must be very careful not to push for an answer. If you do, they are no longer responsible for the project outcome because you have insisted on being given names regardless of how good they are.

You could call this the "Hollywood model" because it is close to the model used in the film industry. It works because the credentials of everyone in the industry are public. The long list of credits at the end of a film are there for everyone to see. In the software development world, only the Open Source community comes close in the terms of openness about taking credit for work. Many software developers have built a very public reputation based on their contributions to Open Source.

Developers must retain the right to claim authorship in all of the applications they create so that other customers can find out what they have worked on. With that comes the personal responsibility for that application -- both its current performance and its future extensibility. That way they learn from their mistakes. If not held accountable for their work nothing is stopping them from making the same mistakes on future projects, because they don't even know they made a mistake.

Becoming a Software Craftsman
=============================

`quote from pages: 80`

Craftsman taking a complete job from start to finish is the only way to be confident that the work created will meet the needs of their users and customers. Having the same people involved from the initial discussions through maintaining the released application reduces the possibility of misinterpretation. This allows developers to take personal responsibility for both the successes and failures of the system.

Where are all the great developers of yesteryear?
=================================================

`quote from pages: 74, 150`

Few of those great developers are still developing software. Most have moved on to other activities that provide greater rewards. They had to become managers, enterpreneurs, or researchers to advance. Some have joined the academic world. 

What incentive is there for someone to excel at sofware development if, by the time the person has learned to do it well, he must find an alternate career?

Estimates
=========

`quote from pages: 137`

Customers and managers do not want to believe the initial estimates. It is as if the "sticker shock" of seeing the initial estimate pushes people into negotiating mode. Despite the evidence that the estimate is an outcome of the project parameters.

Customers and managers seem to persist in believing that it is possible to negotiate for a lower estimate without changing the project parameters. You can negotiate for a lower estimate, but the new estimate will be inaccurate. It is lower, but the project will still take as long as the original estimate (or sometimes longer, because in hurrying the team make mistakes).

Craftsmen always have to negotiate on the project parameters and then report the effect that this has on the estimate. The strongest argument a craftsman has is her reputation for on-time delivery of robust, high-quality applications, and it is never worth blowing a reputation by shaving an estimate just to get a project.
