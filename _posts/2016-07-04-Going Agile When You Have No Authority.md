---
layout: post
date: 2016-07-04 17:57:44 -0700
title: Going Agile When You Have No Authority
---

Your current process is a mess. You talk about it with your fellow developers. Everyone has ideas. They also have horror stories about teams that tried to "do agile." Any effort to make changes is messy. Ideas are met with exhausting debate that doesn't go anywhere. Everyone is skeptical. You have read about agile methodologies; they're paradoxically both wildly theoretical and overly specific. Your know things need to change, but how? You may not have any authority, but you strongly suspect that some version of "agile" might be good for your team.

First, it doesn't matter exactly what process management approach you're using. The purpose of any methodology is to *solve problems.* You should not adopt an agile methodology expecting problems to disappear. Any change in process should make it harder to ignore the problems your team is facing. But it's still your job to solve them.

Learn to be a critical thinker before you worry about getting an agile certification. Don't seek to be an official ~~Scrumbag~~ Scrum Master; learn to solve problems. *[Think Like a Freak](https://amzn.com/0062218344)* is a great read if you are trying to develop this skill set. Levitt and Dubner lay out some useful problem-solving approaches. At the very least, it's a better use of time than memorizing the Pillars of Scrum. Whatever processes you use, you should make sure you focus on problem-solving. Here are a few ways to ensure you're focusing on the right things:

 1. Ask the right questions
 2. Lead your team instead of managing them
 3. Make the process work for you, not the other way around
 
## Problems, Not Preferences

Can we retire the term "[bikeshedding](https://en.wikipedia.org/wiki/Law_of_triviality)"? It has become synonymous with, "any discussion in any meeting when someone other than myself is talking" (or worse, "any time I'm bored or just don't want to be in a meeting"). Meetings can, in fact, be constructive. Boring meetings that last too long can, in fact, be better than no meeting at all. People say "bikeshedding" to imply that the primary problem is that the wrong people have a voice. Engineers love the term because they want to believe managers are useless or stupid. But engineering can't solve everything.

Process is more of a design problem than an engineering one. *[Articulating Design Decisions](https://amzn.com/1491921560)* by Tom Greever is a must-read for anyone working on software (or so I suggest [in my review of it](https://www.amazon.com/review/RAIU0K4YRSI4T/ref=cm_cr_rdp_perm?ie=UTF8&amp;ASIN=1491921560)). Greever says that there are three things that every design needs to be successful. It solves a problem, it's easy for users, and it's supported by everyone. Greever also mentions three questions that every designer should consider when thinking about design. At risk of literally taking a page out of his book, I've adapted his questions for process management, but the point remains the same. For every decision you're making about your team's processes, you should answer three questions.

### 1. What problem does this solve?

This is the most important question. It's also the hardest. You'll hear some of the same things over and over again when you talk about adopting new processes:

- "We've tried sprints before and it didn't go very well"
- "Ugh, Scrum? Didn't you hear that Scrum is dead?"
- "Oh, let's do Scrum. Didn't you hear that Scrum is magic?"
- "Agile is great in theory, but it's just so hard to get it right"
- "I'm just worried that it will add too much overhead"

![](https://s3.amazonaws.com/clearvoice-media/asg_lKbrpyCMVFtSKxf0%2Frevision-%2F1467679036609-Say-Agile-One-More-Time-Meme-small.jpg)

The first step is not to suggest a solution. It's important to identify problems and keep the discussion focused on those problems. You may have a knack for this. You may need to do some brainstorming with your team. Either way, get in the habit of talking about the problems they are facing. This is super hard for engineers because our day-to-day work is more solution-oriented than problem-oriented. Many of our habits come from challenges that (supposedly) tend to be deterministic, atomic, and immediately testable.

That said, there is a particular software engineering skill that is translatable. A good programmer does not generally code through trial-and-error. A good programmer identifies root causes and *then* solves them. I tell junior developers to constantly form hypotheses while debugging. Resist the temptation to suggest solutions at random and then debate their merits. You'll end up discussing them without context. Solutions come last. First, identify symptoms and dig for problems.

#### Example: Surprise Missed Deadlines

It happens all the time. Everyone is reporting that they are on-schedule. Then, right before the deadline, everything has fallen apart. It turns out someone was struggling the whole time. He or she even admits, "I should have gotten help sooner."

 - Tempting Solution: Developers should ask more questions
 - Observable Symptom: Developers don't mention delays until the last minute and miss deadlines
 - Root Problem: The team doesn't know how to catch problems early or they are afraid to speak up

#### Example: Communication of Priorities

Low-priority features get finished while bugs build up. Yak shaving runs rampant. Instead of just doing a small style change, someone writes a form component library. A release that the development team is proud of just annoys stakeholders because the wrong issues got fixed.

 - Tempting Solution: We have more meetings, communicate more (whatever that means), and/or hire a project manager
 - Observable Symptom: Developers are working on things in the wrong order or spending too long on tasks that need to be finished quickly
 - Root Problem: Developers don't know what order they should be working on things

### 2. Does this make things easier for the team?

After isolating problems, debate solutions in context.  Shift the dialog from what people "like" in the abstract to what *works* by staying concrete. Discuss the way a change will affect the team. Will the new process make it easier for team members to catch problems early? Does it put undue overhead on them to do so? Will it make it obvious to the team what the priorities are? When people voice vague skepticism, refocus. Keep the discussion grounded in reality and focused on your actual team.

### 3. Why is it better than the alternative?

Inertia is powerful. Fear of a new failure trumps the honest acknowledgement of a current problem. Again, don't frame a new process in terms of personal preference. Compare it with the way things are currently done.

Don't forget that "the way things are currently done" might be to do nothing. A word of warning: these are the problems managers are blind to. This isn't isolated to incompetent managers or jerks. It's hard for the best managers to stay fully in-tune with their teams. Many of your team's daily struggles will be invisible.

![](https://s3.amazonaws.com/clearvoice-media/asg_lKbrpyCMVFtSKxf0%2Frevision-%2F1467679494710-tumblr_inline_nf8ucvxIsH1rp8xbw.png)

For instance, a manager may not think everyone should attend a planning meeting. They are weighing "losing 12 person-hours of dev time per week" vs "everything running quietly without a boring meeting." They don't see your team struggle every time you plan interdependent work. Silent failures are more palatable than noisy ones, even if they are less useful. Make sure current failures don't remain swept under the rug.

## Leadership, not Management

Someone on your team has to be responsible for all this. If you're reading this, you are probably that person. Don't wait to get promoted. Don't assume everything is your manager's job. In early episodes of [Andy Stanley's leadership podcast](https://itunes.apple.com/us/podcast/andy-stanley-leadership-podcast/id290055666?mt=2), he says leadership is about influence. It isn't about a title. Learn to be a leader.

### Know Yourself

In *[Credibility: How Leaders Gain and Lose It, Why People Demand It](https://amzn.com/0470651717)*, Kouzes and Posner lay out the core disciplines of leadership. The first is "Discover Yourself." Know your core competencies, but also know your weaknesses. Not everyone is well-suited to leadership. To be brutally honest, you may not be equipped drive this change on your team by yourself. If you aren't, get help from another team member and contribute in a way that plays to your strengths.

Bad news: at first, you'll be responsible for most of the clerical tasks. You'll have to do the boring maintenance. Know your limits and be careful not to overextend yourself. If you're not a visual person, [maybe you should avoid an approach that requires that skill set](http://www.girlsguidetopm.com/2016/06/comparing-agile-methods-scrum-kanban-and-scrumban/). If you become too fatigued by support tasks, your day to day work is going to suffer. Even if you help your team, if your normal role suffers, your manager may axe the new process (or worse, you may find yourself [irreparably viewed as incompetent](http://sites.insead.edu/facultyresearch/research/doc.cfm?did=46698)).

### Know Your Team

The second discipline Kouzes and Posner mention is "Appreciating Constituents." That means listening to them, soliciting feedback, and building trust. If you're not a manager, you may actually have a bit of an edge here. You're forced to earn trust and build buy-in instead of relying on the power to just make a decision. Decisions made without knowing the team are doomed to fail. If you're leading with influence instead of power, you won't get far enough to make that mistake.

Before moving to a new process, pay attention to the way your team currently behaves. Make anecdotal, story-like notes about specific people. Those personal stories will help you stay focused on your real-life, human team members.

#### Note Success Enabled by Current Process

Don't throw out the baby with the bathwater. Save what you can, even if it doesn't fit neatly into a new methodology. In theory, a team of generalists is the best fit for Scrum. If specialization works well for your team, don't try to disrupt your team's culture. If one person on your team is good at fixing bugs and actually enjoys it, don't rush to share bugs because a blog post insists that you should.

#### Hunt for Success that Happens in Spite of Current Process

Here's where you'll find out what your team is really good at. When process gets in the way, good team members will work around it or ignore it entirely. If they work well, try to make these workarounds a part of your official process. If nothing else, make sure new things don't make these workarounds *harder.* If you officially use Pivotal Tracker to track all issues, but people occasionally open GitHub issues for discussions, don't try to squash that behavior. If your team does TDD in spite of a weekly timeline that is too aggressive for it, seek to enable those good habits.

#### Pay Attention to Habits

Habits that don't officially violate your current practices can be hard to notice. Is your team better at ad-hoc meetings to work out problems or do they take ownership of decisions on an individual level? How does information flow when there are no rules? Once again, don't get in the way of your team just because you're excited to adopt a new process. Play to their strengths.

### Focus on a Vision

According to Max De Pree, "The first job of a leader is to define reality." You're not just implementing a methodology. You're casting a vision. Creating a vision is an early step of Kotter's 8-step model for change management. It is motivating. It is energizing. It will prevent you from getting too distracted by individual details. Instead of making a decision, "because that's how Scrum works," go back to your vision. As an example, my vision for my current team is, "Everyone always knows what they're doing next and why."

## Make the process work for your team, not the other way around

> "No one can serve two masters, for either he will hate the one and love the other, or he will be devoted to the one and despise the other..." Matthew 6:24

I resent the term "servant-leadership" because if you aren't serving, you aren't leading. It is impossible for you to serve your team if you are slave to a process. The better you know your team, the easier it will be to serve them. There are also some guard rails you can establish to make sure you're "serving the right master."

### More like Guidelines, Really

![](https://s3.amazonaws.com/clearvoice-media/asg_lKbrpyCMVFtSKxf0%2Fart_WUubUOp9wdTsZ5WK%2F1467566510677-tumblr_lzwm2hkmgx1qhkwbs-1.gif)

Whenever you're looking to a methodology, you should be looking at it as a *framework*. You may hear Scrum referred to as an [implementation of an agile framework](http://www.c-sharpcorner.com/article/agile-framework-a-kickstart-to-scrum/). Scrum itself should also viewed as a framework. An agile coach once told me, "There's a difference between *doing* agile and *being* agile." Be ready to adapt, even when there isn't a definitive answer to your particular question. Agility *(ahem)* is more important than having a handbook. [Don't get bogged down in practices without understanding the principles behind them](https://dzone.com/articles/10-common-scrum-mistakes-and-how-to-avoid-them).

Exercise skepticism when someone suggests that there is *one way* to approach a particular problem within a methodology. Faisal Ansari takes a good approach in [this post on splitting user stories](http://www.agileadvice.com/2016/06/03/scrumxplean/splitting-user-stories/). Ansari starts by presenting a *model for* testing user stories and ends with a *list of methods*.

### Expect people to break the rules. Let them.

In *Credibility*, Kouzes and Posner say "threat, power, position, and money do not earn commitment; they earn compliance. And compliance produces adequacy, not greatness." Don't be so focused on following an agile methodology to the letter that you lose sight of your vision.

![](https://s3.amazonaws.com/clearvoice-media/asg_lKbrpyCMVFtSKxf0%2Frevision-%2F1467679646969-If-You-Wanna-Rock-You-Gotta-Break-The-Rules-Animated-Picture.gif)

This is a lesson we can learn from usable security design. In "[Privacy and security: Usable security: how to get it](http://dl.acm.org/citation.cfm?id=1592773)," Lampson says, "If [a security measure is] hard or opaque, [users] will ignore it or work around it; given todays poor usability they are probably doing the right thing. If you force them, less useful work will get done." The same is true of your team. If your process is a pain, your team will ignore it or work around it. At most, they will do the bare minimum to follow the rules.  If you force them to follow the process to the letter, less useful work will get done. Following process is a support task. It shouldn't get in the way of their primary task: development.

Don't *police* process violations. Think critically about them. Sometimes, you will need to guide your team to get back on track. More often, you should just make sure you discuss these deviations in a retrospective. Adapt your process to your team, not the other way around.

### Don't change your tools...yet

Don't switch to JIIRA. Don't start a Trello board. Even if your current tools aren't adequate, try to use them. There are two reasons for this:

#### Learning One Thing at a Time

It's easier to learn one thing at a time. Your team will already have an increased cognitive load when changing processes. You are guiding their behaviors. As Sunstein and Thaler note in *[Nudge](https://amzn.com/014311526X)*, this is a serious responsibility. Make sure you're not overloading everyone's brain with irrelevant information.

[![ladders may be considered to be a special and perhaps degenerate case of stairs](https://s3.amazonaws.com/clearvoice-media/asg_lKbrpyCMVFtSKxf0%2Fart_WUubUOp9wdTsZ5WK%2F1467567538399-comic2-2390.png)](http://www.qwantz.com/index.php?comic=2379)

#### Forcing Yourself to be Flexible

Engineers love tools. It's part of the reason good engineers can be terrible managers. We are conditioned to believe that tools solve problems. One of the best ways to learn flexibility in a new process is to begin with imperfect tools. Even if you change tools later, at least you'll know how to focus on building good habits.

## Next Steps: Forgiveness vs. Permission

After a few years of consulting, I believe in asking for forgiveness instead of permission. Doing research, planning, and delivering will often work better than waiting around for someone to give you the go-ahead. If you're lucky, a manager will take note. Even better, they may be publicly supportive and save their concerns for private conversation.

I hate false dichotomies. I'm not suggesting that your choices are either beg a manager for help or ignore their existence. There is a middle ground, too. Start scheduling meetings; people show up when you send them calendar invites. You can do your first sprint planning without actually calling it a sprint planning. When you step up and just start doing stuff people go along with it. Bold leadership, according to Andy Stanley, is "clarity around an unreasonable commitment to what should be." People will respond to boldness.

You know what happens when you poll people and make decisions by committee. Everyone wants to exhaust negative possibilities and make their concerns heard. Your job is to move past the fear of failure instead of feeding it. Ask the right questions. Know your team well enough to lead them. Make your process work for you. Your team will naturally cling to every moment that makes them feel successful. Or you'll fail, which won't be nearly as bad as it sounds.
