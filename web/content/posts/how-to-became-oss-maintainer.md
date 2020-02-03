---
authors:
- name: "Bartek Płotka"
date: 2020-02-05
linktitle: "How to Become an OSS Project Maintainer, Survive, And Have Fun on The Way!"
type:
- post 
- posts
title: "How to Become an OSS Project Maintainer, Survive, And Have Fun on The Way!"
weight: 1
categories:
- opensource
---

In this post, I would like to share what, in my honest opinion, a **"perfect"** maintainer of the open source software should do.
Yes, no one ever will be perfect: We all have limited time, we all make mistakes and have some skills to learn.
However, there is nothing bad in defining what we should aim for. (: 

Some quick glossary I use in this (too long) post:

* *Maintainer*: Person responsible for the open source project development and community. The one having full write access to the software repository. Sometimes called "committer".
* *Contributor*: Person, usually user of the project (not necessarily developer) who contributes to the project in any form:
docs and code fixes, reporting issues, helping others on forums, issues, slack.
* *PR/Pull request*: Code changeset, proposing a certain change to the project.

### Top 6 of practices to do to become a better maintainer:

* [Be Polite and Friendly.](#be-polite-and-friendly)
* [Improve Your English.](#improve-your-english)
* [Review Issues and Code Carefully; Be Strict.](#review-issues-and-code-carefully-be-strict)
* [Be Proactive and Intelligently Lazy.](#be-proactive-and-intelligently-lazy)
* [Want More help? Give Back, Help Others.](#want-more-help-give-back-help-others) 
* [Stay Healthy; Have Fun!](#stay-healthy-have-fun)

### You don't have to be maintainer at all to follow those suggestions.

If you want to just become maintainer of some project you contribute to, by following those pieces of advices you might increase
your chances significantly. Chances that someone will trust you to do solid project maintenance. Or let me put me it this way: 
if you do the opposite, most likely, no one will want you as the maintainer. (:

### I am far from being perfect, but I try to folllow those rules. 

All of those I learned by practice while maintaining [Thanos](https://thanos.io), [Prometheus](https://prometheus.io) and other projects.
However mainly **I found those by *observing* amazing examples of good maintainer behavior**, as well as seeing anti-patterns.

Don't get me wrong: I am personally far from being perfect, but I try to follow those good patterns and improve every day.

Last but not least the following practices are purely soft skills related. I won't touch in this post how you should design your system, 
or write your code. If you did not already notice, probably most of your work as the maintainer will be communication with the people.

Also, let's assume you use GitHub Issues for bugs/feature requests and PRs for proposing changes, but it does it matter where 
as long as there is some place for it.

So... Let's go!

## Be Polite and Friendly.

I hope I don't need to say this, but no one will ever consider you as a good maintainer if you are not: inclusive, approachable and polite.
No one says you have to be everywhere, talk to everyone, always smile and like everyone. No. But you have to be professional.
**Never swear.** Be tolerant. Use "her" instead of "his" more often. Avoid offensive jokes. Accept that everyone makes mistakes.

### Either respond politely or don't respond at all. 

Never go into meaningless argues especially on Twitter (: Report sketchy interactions,
escalate but never fight back with trolls or aggressive people. 

### Don't try to sell your open source project too hard, in a pushy way.
 
It's always easy to say `"This other product X is shit, and our software is better"`. However, in this way you are in some way offending
others while maybe they might just have different trade-offs or different use cases etc.
If you think your software is better, then keep up the good work, and see how users will adapt and enjoy using your product.
They will do that when they see factual benefits, not just dry words.

### Saying "No" without offending others.

This one of the most difficult skills you need to learn as a maintainer. Some feature was proposed, code was written and it
does not fit the project's goal and vision. Then the contributor gets frustrated: 

```
"Merge it please! How difficult is?? It's just one click of the button for you!!!!" 
```

This happens a lot and you need to learn how to be patient. Always try to respond explaining why the decision is to reject.
Try to propose an alternative that will work for the users. Usually, there is some other project that helps, or tooling, or API 
that your contributor can integrate with your project instead! [See example "No" in Thanos project](https://github.com/thanos-io/thanos/issues/2014#issuecomment-579824888)

Users sometimes don't understand your project. Some of them don't see complexities and they miss what maintenance burden means.
However, some contributors give amazing ideas and golden improvements so that's a trade-off of having the project in open source. (:

Show friendliness and gratefulness for all the contributions, even for the code that was not eventually merged. Still,
contributor spends time and effort. Probably she/he learned on the way, so nothing is a total waste!

**Important: Never compromise the quality of the project just to be `friendly`!**

### Try to be nice if you are suggesting changes on a PR. 

This is maybe obvious, but when you review dozens PRs a day, you can lose patience. Still, always try to explain the reasoning, especially if someone is new to the community.

For example instead of saying: 

```
`"Lol, that's wrong, it should be ThisNiceName() not ThatWrongName()"
```

Maybe you could say:
 
```
"This is great overall, thanks! But I think we can still improve the name of this method.
The reason is that [consistency, more verbose, less complex, style guide linked here, etc]"
```

It's really worth it! Contributors will love to contribute because they are learning, and they feel more supported.

### Be proactive and clear.

You can't escape awkward situations. Sometimes you can have two contributors yelling each other in the PR in their
language that someone has the right to implement a certain feature. Another time you want to quickly fix the issue, while there is already
not perfect PR by some contributor, waiting for a rebase. Or maybe you have the contributor who tries to "triage" issues by just
commenting on every issue `ping @bwplotka` several times (like I am not getting spam in inbox already...).

Try to consider other people's feelings. What helps in ALL those cases is to ask the contributor to join Slack
and discuss the matter directly. in 99% the situation gets resolved because the person feels supported, she or he knows you care
and you can fully explain why and what, etc. 

Also, keep in mind that you can provide feedback to the person **directly** on the private channel.
Sometimes people just don't know they are rude or doing something wrong. It's ok to say the truth and be honest about the problem,
as long as it is delivered in a nice, positive way (!).

### Have fun!

Open Source is fun place. If you spent some of your work or free time at forums, GitHub Issues and working with the community, it's
always worth to fill this place with positive energy! Laugh, jokes, funny situations, memes, emojis. Everything is allowed!
It helps to maintain a healthy atmosphere and break some ice on the way! Your slack forum or Github Issues don't need to be
always a sad place full of reported OOMs or race conditions! (: 

As an example, I recently was amused by contributors from Russia that clearly where having some extra (%%%) help when
making [this PR's comment](https://github.com/thanos-io/thanos/pull/1789#issuecomment-559025685). =D Met them at
[FOSDEM](https://fosdem.org/) and they are nice guys in real life as well. (: 

**Overall:** be nice where you can e.g in communication in issues, PRs, slack or Twitter.
This also includes private communication, because nothing leaves the internet these days. (:  

## Improve Your English.

This is a must-have. Language details matter. Making basic grammar mistakes is not just ugly, they can seriously obfuscate
the communication. It makes the person you write to (in e.g issue):

* In the best case: Waste their time trying to understand exactly what you mean, asking follow-up questions, etc.
* Worse: They will just ignore your message, not respond at all.
* The worst: They will do opposite action to what you just recommend, waste even more time, and get frustrated.

### It saves time. 

It's quite funny but to save time overall you have to sometimes spend a bit more time. For example, on your messaging:

* Write full sentences. 
* Avoid "this" "those" "that" words. 
* Try to explain as many details as you can. 
* Link to other communication as well.
* Install [Grammarly](https://www.grammarly.com/) web plugin.
* Look in Google translate if you are unsure about some wording.
* Avoid abbreviations and shortenings. For example, this sentence makes sense but it's probably unreadable for most of you: 
  
  ```
    "FTW should we introduce ASAP CRDs in PO if used on OCP by SWE from CS and GSoC? LMK"
  ```
   
* Avoid saying "never" or "always". See why here (:

All those relate to the project public communication (slack, forums, PRs) but also to documentation, flag descriptions, code comments, etc.

I agree that it is brutal and unfair, especially for non-native speakers like me. However, you have to learn some tiny
details of English to be more effective as the maintainer or, more effective as a contributor who might be maintainer someday.

## Review Issues and Code Carefully; Be Strict.

We are all busy. There are times when I am so tired and someone reports an issue that looks similar to a certain common issue.
In same cases, my brain automatically assumes it's a duplicate. Only then I see that I did not read it carefully, and I was mistaken and
the real reason was different.

So yes: Don't rush out too much, and **read things carefully**.

### When reviewing PR: As maintainers, we need to be extra careful.
 
Software these days can be complex. Go language improves readability enormously, I would even say it's the most simple
and readable programming language out there. However, still some software I work on ([Thanos](https://thanos.io))
is at the end a distributed system that involves concurrency, tricky optimizations like [mmaping](https://github.com/thanos-io/thanos/blob/56a1fb6c084f11638f6f7b6532adc07dd05824b6/pkg/block/indexheader/binary_reader.go#L457)
and [bespoke binary formats](https://github.com/thanos-io/thanos/blob/56a1fb6c084f11638f6f7b6532adc07dd05824b6/docs/components/store.md#format-version-1).

This means that every detail might matter. And yes, we are guarded against mistakes with unit/integration/e2e tests, cross-building
tests and static analysis on each commit, but the coverage is always too low and it's easy to miss stuff.
 
And every mistake cost: sometimes just time, sometimes reputation, sometimes actual money when you (or any of users of your project)
have a major incident (e.g data loss, unavailability).

### It is really bad if the maintainer approves the PR with very visible mistakes.

To me it means that she/he did not even scroll the proposed change until the end ): 
There might be different reasons behind such a mistake. Maybe the maintainer was too tired, maybe simply did not see that
bug. Maybe she/he wanted to be nice and not block contributions? Maybe the author did amazing PRs before so maintainer trusted the
author, so `"why would I need to review it carefully?"`. Unfortunately, there can be sometimes even more selfish reasoning: 
They approved just to show they are active, even though they don't have time to maintain the project full time. Don't be
like this. It is pretty obvious!

### As the external contributor you can also review pull requests!

In fact e.g according to our review process policy, a contributor's code review (if done by the contributor whom we trust and
she/he knows a codebase) can be enough to merge some less impactful PRs. I think this is great because it allows a contributor
to do reviews in a safe environment, with other maintainers to guide them and step in if some comment is not particularly
correct. It's also a very good sign that the contributor is ready to become the maintainer!

### Rules for every PR I try to follow.

As the maintainer, please:

* Never approve the PR if you are not sure if it makes sense OR if you don't have enough time to review it properly.
It is totally fine to postpone a review or review only part of the PR and say that you can't review all right now.
**That's critical and please take it seriously**: Green is a green. PR is approved (green) if you would be ok to deploy this in production.
This is at least what we follow in the Thanos project.
* Don't trust anyone. Everyone does mistakes. Some more often, some less but still. Ask questions, challenge the code.
Anyone means also yourself! Review your own code. Trust me this works! If you change your mindset into reviewer's one and try to look through
your own diff before others, you can save some time for everyone ((:  
* Make use of [the boy scout rule](https://www.oreilly.com/library/view/97-things-every/9780596809515/ch08.html), but carefully. Ask the author
to fix places around the areas they are contributing to unless it'a difficult or wide change.
* Follow the suggestions I had in previous sections: be friendly and use proper English.

### Literally refuse to review and merge huge (1k+) PRs.

Only a few are capable to review such an amount of code in detail. Additionally, it's really difficult to find 3h of the
continuous focus to review that properly. All ends with delayed reviews, merging not fully reviewed code and increasing chances of
unnecessary complexity or bugs. 

One exception: replace-like (e.g `sed`) changes across many packages as long as the author also presents the script/command that was used to perform rename.
Just make sure you don't mix changes made by the script with manual changes! 

### Strict vs Fast.

That's my opinion there are two types of maintainers. 
In one group, maintainers are more happy to merge maybe not yet ready code, because you can always improve it later and
you can move quickly. MVP is done in no time, the demo is ready. But then what? Who will refactor the code? Who will make it
consistent? Who will "productionise" it? And when? The answer is: **Probably no one, never** (:

That's why I am more in favor of the other group of people: Those who aim for quality vs short term velocity. Design
first vs quick MVP. We do that while maintaining both Thanos and Prometheus projects. I strongly believe that is the
best practice for long term projects like that. (: 

Remember: Some contributors will not like you because you are strict on details and refuse to add the feature they
implemented. **But more people will hate you if the project will be causing incidents, because of YOLO code,
unnecessary complexity or unmaintainable features. (:**

### Don't go to extremes.
 
It's probably fine if some variable name is not perfect or if some comment is missing, but I think you get my point. (: 

## Be Proactive and Intelligently Lazy.

There are certain rules that you can stick to if you want to be a more efficient maintainer and simply have more time to focus on what matters.

### Prefer asynchronous communication, but sync one as well. 

First of all, define the project's means of communication. Keeping GitHub issues for feature requests, bugs reports and feedback makes
sense. It is asynchronous, easily searchable and easy to back to follow up. But these days it might be not enough. First of all,
potential users are sometimes too shy to put an issue with maybe basic questions due to e.g missing piece of the documentation.
Setting some asynchronous channels like Slack (we use that in Thanos project) or IRC (Prometheus) is exactly for this purpose.
This allows building some relationship with community, contributors, and maintainers.

If you want to resolve a problem, quickly discuss some matter or design, it is much better to schedule some discussion on slack,
than just slow comment by comment conversation on Github Issue or PR that takes weeks. With such, more direct communication
**Users and contributors gain more trust in the project.** At some point you will find that community helps each other to answer questions and last but not
least: you can find new friends! (:     

### If some process takes more than 1 minute and you repeat it more than 3 times: Automate. 

You would be surprised at how innovative people are in order to avoid work. All those small repetitions can add up to weeks of time
during your whole lifetime, so they matter. In Thanos project we try to apply it to everything:

* We were spending too much time during a review process to ensure proper commentaries. (Started with capital letters and finished with a period). We
were super strict about it. But sometimes instead of focusing on the essence of the PR I was spending time commenting wrong comments. That's why we created
[this CI script](https://github.com/thanos-io/thanos/blob/55cb8ca38b3539381dc6a781e637df15c694e50a/scripts/build-check-comments.sh#L85) that verifies this for us on the CI.
Similar with [wrong whitespaces](https://github.com/thanos-io/thanos/blob/25f5b0b9290fa1620647f00dd8df954380efc530/Makefile#L176) as well as
[Copyright file headers](https://github.com/thanos-io/thanos/blob/55cb8ca38b3539381dc6a781e637df15c694e50a/scripts/copyright/copyright.go#L23).
Last but not the lease, we [lint](https://github.com/thanos-io/thanos/blob/25f5b0b9290fa1620647f00dd8df954380efc530/Makefile#L292) our code heavily.
**All of this to make sure maintainers do not have to!**
* We autogenerate our documentation from flags and [configuration](https://github.com/thanos-io/thanos/blob/55cb8ca38b3539381dc6a781e637df15c694e50a/scripts/cfggen/main.go#L41).
This saves the effort of maintaining documentation, it is harder for it to get obsolete. We check if links work with amazing [liche tool.](https://github.com/thanos-io/thanos/blob/25f5b0b9290fa1620647f00dd8df954380efc530/Makefile#L185)
* Every commit build our website hosted in the same repository and prepared preview thanks to [netlify.](https://www.netlify.com/)
* Every time someone adds an object storage client we ensure it works as expected by running [e2e acceptance test.](https://github.com/thanos-io/thanos/blob/55cb8ca38b3539381dc6a781e637df15c694e50a/pkg/objstore/objtesting/acceptance_e2e_test.go#L21)

Does some repetition frustrate you? Handle this with automation! e.g [the recent frustration.](https://github.com/thanos-io/thanos/issues/2102)

### Try to answer someones else question.. with a new section in your documentation!

This is easy to say, but not as easy to incorporate. However, it is worth it. You will see, it either reduce the number of repeated questions
or other contributors will be able to respond to each other in e.g slack room. 

In fact, I wrote this blog post because someone asked for feedback on how he can become a maintainer! (: 

Of course, it escalated a bit...

## Want more help? Give back, help others.

This is again, in my opinion very important rule: **How to build community? By helping the community out!**

You can't be selfish. First of all, you created / maintain the project in the open source in the first place, so you are already helping out the people.
But at some point you feel stressed, exhausted, alone or helpless. This is where the community helps enormously. You want more users, because (tiny)
percentage of those users actually will give back and help out. Some of them became maintainers next to you **or even friends.**

So how to achieve that? Just ask around that you need help? Well not really.

### Contribute; Reuse.

The answer is easy. Help others. Instead of building a project from the scratch out of nowhere **build it on shoulders of giants**.
First of all, make sure someone needs it except you. Thanks to extending project, you already have data what is a main painpoint.
Secondly, you have helpful community to start with. Thirdly, you can (and you probably should) reuse some pieces of the code from your "mother" project.

Reuse ensures that: 

* You [LEARN!](https://twitter.com/bwplotka/status/1216693249055887360)
* You immediately hook into the ecosystem (e.g by sharing API).
* Multiple parties are maintaining certain components. The piece of code has more users, thus is more tested and mature. Your project is then safer as a result.
* You help multiple projects, so you will get help from them if needed! (e.g review something on your project, help with design questions, etc)

This is what we did with [Fabian](https://github.com/fabxc) with [Thanos](http://thanos.io/) project. Instead of building all from scratch we reused exactly
the same storage format as Prometheus, as well as many other components that we directly import from Prometheus codebase.
At some point, because I was maintaining those dependencies as they were critical to the Thanos project, I became the
maintainer of Prometheus itself (: And at the end, I am helping with much more than just parts that
Thanos relates to. I give out more because, in my opinion, kindness always returns with double!

As a result of reusing some code, API and storage format we are super easy to work with. This makes it convenient
for Prometheus community to jump in and start using Thanos. Especially when they can install all gradually and the same integrations and tools
work for both projects.

This is partially why we have many users and amazing contributors that trusted our work.

### Mentor; Enable others.

Every one needs experienced, motivated and high skilled people to work with. But they don't just hang on trees. People don't get born like this.
In open source you meet a variety of contributors. Sometimes it will be crazy-ass ex-Googler, ex-Uber who wants to help and
gives you some amazing ideas, but sometimes, you will work with people who just started their journey with programming or infrastructure (in our case). 

There will be moments where you would do a change 10x times faster than getting back-and-forth on the same PR with the newbie. You 
will get angry that you are gaining almost nothing and instead you are free mentor; Git, Linux, Bash teacher; Security, Kubernetes guide or English teacher.

**But don't be frustrated, because you actually gain something: Potentially skilled contributor, a happy human that is very likely to start
amazing contributions and became another maintainer someday!** 

So.. be patient and enable others if you can. Additionally, be proactive here as well and participate in programs like [CommunityBridge](https://communitybridge.org/)
or [Google Summer of Code](https://summerofcode.withgoogle.com/). Those allow students to quickly ramp up into your
project (and get paid on the way). This is especially amazing as it allows minorities to be mentored and helped by maintainers
and maybe someday improve the diversity of your project's team or at your work.

### State project expectations from the beginning.

One way to avoid later frustration stress or just fuss is to make sure the project has explicitly stated the goals.
Tell users what to expect from the project. E.g Prometheus and Thanos are not designed to handle events. That's why it will be
never optimized for high cardinality data.

Something is not yet done, is in the experimental stage, you did not test that properly? **Explicitly** mention it. 
You don't want some huge customer to report that they lost millions because something in your project lost data etc. Obviously, it's their
legal responsibility - it's an open source project after all. But you want to make sure users know what are the best practises and where
to be very careful.

### Consider donating your project to trusted Open Source organization.

This has many benefits. The most important one is that you are not alone, but also (in theory) the project is independent. 
At some point when the project will be big enough (think: Prometheus), there will be many parties that want to influence it, because there is money there.

Organizations like [Apache.org](https://www.apache.org/), [Linux Foundation](https://www.linuxfoundation.org/) and [Cloud NativeComputing Foundation (CNCF)](https://www.cncf.io/)
help to maintain independence in terms of decision making. They help with operational functions like SWAG, organizing conferences and meetups,
3rd party paid resources (e.g cloud resources for testing), security audits and more.

### Stay organized

One way to get more productive is to start from your own personal organization skills. For that I really recommend the book 
[Getting Things Done by David Allen (available in the audiobook read by the author)](https://www.audible.co.uk/pd/Getting-Things-Done-Audiobook/B01B6WT3JY).
 
Spoiler alert! Focus on clearing your mind. If you have quick <3min task, just do it. For longer one try to note what's the next step
and do in some trusted way. Visit this place everyday morning. This will allow your mind to relax, clean and be innovative and
focused on what is now!

## Stay Healthy; Have Fun!

This is the last one but also the most important rule you will read here. **Don't overwork.** If you are tired or it does not make you happy, then first try to
rest (no computer allowed!), then just quit and find another thing to focus on. 

Open source is the opportunity to find best friends, have lots of fun and amazing job, however, it is also the place of endless requests, bug reports, and questions.

* There will be users which want help NOW, HERE because something they misconfigured is on fire.
* There will be people from different cultures, spamming you directly on email about their requests.
* There will be hard decision to make and all of them might be somehow wrong (that's called trade-off...)

And on top of that, you might be just a part-time maintainer like most of us are. Everyone has a job on top of it with less or more
time dedicated to open source. E.g At [Red Hat](http://redhat.com/) we design, develop and we are even on-call for our internal monitoring platform, where
we use some of the products we maintain. Moreover, probably no one knows about that. Everyone thinks it's your only focus and blame you of slow project movement... 

Which comes to another point: 

### Don't be afraid to make mistakes; No one actually blames you personally!

Naturally, your imagination will trick you that if someone puts and bug report or comments about your code it will definitely mean
she or he hates you and your work. Everyone has some insecurities, so it's totally fine to have such an impression.
That's why it's important to suggest things in a certain way as described [in the previous section](#try-to-be-nice-if-you-are-suggesting-changes_on-a-PR)

What helps? Growing the maintainer's team. Trust other contributors and give them a chance. What you win is feeling of shared
responsibility.

Additionally, it helps if you would assume by default that everyone is positive and professional. 99% people I met so far in tech open source world
are professional, nice, friendly and positive. They will not point your mistakes, they will not blame you for mistakes, unless
you do something malicious on purpose. Everyone makes mistakes so it's normal. So don't be shy and allow yourself to be more open! 

There is one way of learning this: making mistakes. How many times did I say something on the internet that was stupid?
How many typos I did? How many English grammar mistakes? (Thank God for Grammarly).
 
`Millions of times`. 

One time I said on public, recorded Prometheus Community Meeting that "I am Prometheus maintainer and I became just recently a Thanos maintainer"
and the truth was the opposite. I felt super shitty about this and embarrassed, my whole team was laughing. When I look on this now... it did not matter (:

It is what it is. I think it's a trade-off again and I can trade my *external perfect image of perfect person* (which you will maintain only by doing nothing)
for extremely meaningful conversations, things I learned on the way, relations I gained, public speaking that made the community more diverse and bigger, etc.
In open source, you can say `goodbye` to your perfect "external no-mistake image".

If you don't accept this you won't have fun in maintaining the public project, it will be simply unhealthy, so keep that in mind.

### Open Source Project Maintenance is not a sprint, it is a marathon.

This is what I heard from one friend when I was overworking and it is very true. Short periods of extreme programming, deciding about the project,
after-hours issue triaging and working during the weekend might look fine... but you won't be able to sustain that for a long time.

Set boundaries and maintain a healthy work life balance. You don't have to respond to issues immediately. Allow others to
investigate issue first for learning purposes, and only guide them through. Always take time for a high quality rest.
A rested and clear mind will solve problems 100x quicker. Don't sacrifice weekends, sleep 8 hours, do sports.

Depression and burnout are pretty serious stuff. At the moment of writing, I'm 27 years old and I already burnt out twice in my
career. I definitely don't recommend this! All of this because of high expectations, overworking, working on weekends, etc.   

## Summary 

This guide is something I am aiming for when interacting with the community and maintaining open source projects.
I definitely failed many times to follow those rules, especially around stay healthy part (: But I feel like those items
can guide you to achieve happiness and improve open source world!
 
We can sum those rules into 3 main points:

### Treat others like you would like to be treated

Be friendly, because you would like for someone to be friendly to you. Don't sell your project in everyone's users' faces,
as you also would like to not be spammed on your own project forum. **Help others, teach them how to program, use Linux, Git or 
make presentations as you would like to have help once others will ramp up.** 

### Do you want to become maintainer? Behave like maintainer!

Literally, almost everything maintainer do, you can do. You can respond to slack questions and GitHub Issues.
You can review the code. You can guide other users and contributors. You can tweet, speak at conferences about the project.
Try to mimic the good patterns from other maintainers and do the hard work. **You don't need a write permission to make decision
and act like maintainer of the project.**

### Be innovative; Challenge processes; Optimize! 

Always question processes. Are they good enough? If this repetitive thing can be automated? We had many innovative ideas
just because we were frustrated that we waste time on it. Try to optimize for quality and time. This will give you more time to
have time for pleasures (: 

And... that's it! I hope you will find this helpful.

PS: It's my first non-coding, non-system design blog post so... please give me feedback! If you don't agree with something or I missed important detail,
let me know! (: 

And I wish you a pleasant project maintenance ♥️.