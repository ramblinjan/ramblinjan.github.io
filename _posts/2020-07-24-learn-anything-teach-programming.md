---
layout: post
date: 2020-07-24
category: development
tags: 'teaching, leadership, team'
author: Jan Jorgensen
title: How to Learn Anything and Teach JavaScript
preview: true
---

_This post is based on a talk I gave at Little Rock Tech Fest, LibertyJS, and at a couple meetups. I'm passionate about helping teams become better at mentorship, teaching, and growth. If you'd like me to give this talk to your team via Zoom for free, please send me an email at [jan@ramblinjan.com](mailto:jan@ramblinjan.com?subject=Learn%20Anything%20and%20Teach%20JavaScript)_

I figured out what an expert looks like when I broke down on the side of the road just outside Prescott, AZ. My fiance, my dog, and I spent about two years living in an RV and traveling around the country. The RV -- named Sonny after my late grandpa who drove a semi truck back when you had to warm up the diesel engine with charcoal in the winter -- was a 36-foot 1999 Winnebago Chieftan with a Cummins Turbodiesel engine. When it ran well, it drove like a dream. Unfortunately, a 20-year-old RV doesn't always run well.

We'd occasionally had a problem where a "low water" light came on intermittently ("water" meaning coolant). It had been in for service recently, but they didn't catch the issue and we were topping off the tank crossing our fingers we could make it to a Freightliner service center before the problem got worse. Unfortunately, the engine started overheating on a two-lane highway outside Prescott, AZ and we had to stop and call for a tow truck. The nearest tow that could handle over 10 tons was Phoenix. It would be a few hours. So, I did what anyone would do: I turned the generator on so we could kick on the A/C, disconnected the Jeep we towed behind the RV, and went for a beer run so we could make our own Corona commercial.

Eventually, Pops arrived. Before he drove a tow truck, Pops was a long-haul trucker with more than a million career miles driven. Later, when I was riding in the cab with him as he towed Sonny, he would give me really important life and love advice like, "When you argue with your wife, always have the last word. That word should be 'sorry.'" When he arrived on the site, he asked what went wrong and walked around the RV. As he got to the front passenger side he leaned over, sniffed his nose, and said, "You've got a leaky heater core."

He was right. He knew by the syrupy smell that it was a coolant leak and based on the location of the smell he knew what was leaking. You've probably experienced something like this. You're working on some impossible-feeling bug that you just can't figure out. Then someone else comes over and it seems like they just sniff and say, "Promise.all takes an array." It feels like magic. But it's expertise.

## What is Expertise?

Expertise isn't just about experience or the amount of knowledge someone has been exposed to. You can't develop it only by reading a bunch of books or watching a bunch of videos, because it's not just about what you know but how you organize that knowledge inside your head and leverage it.

### Inside an Expert's Brain

If you have an understanding of data structures and algorithms, here's one way you might understand expertise:

> An expert is someone who can find the root cause of a problem in O(log(n)) time.

O(log(n)) is the time it takes to find an element in a balanced binary tree:

[picture] caption

An expert has not only been exposed to a ton of information, they can quickly figure out what parts of their experience are relevant by bisecting problems. This is as much about knowing what does not apply to a given problem as it is knowing what does apply.

If your car won't start and you don't really know anything about cars, you might try random things until you get lucky or give up and call a mechanic. That's because this is what the problem looks like to you:
[car picture]

It's not just about knowing likely causes either. Many "car guys" facing a car problem will very confidently just tell you it's whatever was wrong with their car the last time they fixed it. This isn't expertise -- it's availability bias. In the repair manual for my motorcycle (a 1980 Honda CB650), the troubleshooting guide for when the engine won't start doesn't begin with the most likely root cause. It begins with the _easiest to test_ causes. If those tests don't identify the problem, it moves to harder to test issues starting with the most likely ones. For an expert, problems and approaches look a lot like a troubleshooting flow chart:
[flowchart picture]

This is how an expert does something that looks like magic -- often without even realize the massive amount of knowledge they're navigating because of the simple picture they hold in their head. The way you organize and picture information as well as the metaphors you use to process and communicate that information are called _mental models_. The formation of these mental models are the superpower that allow us to reason about large pieces of a system and bypass the limitations of short-term memory.

### Mental Models and The Learning Process

The learning process and the path to expertise are primarily about the formation, testing, and refining of mental models. One way to think about this process is this:
[build knowledge, form mental models, form and test hypotheses]

Let's look at a simple code snippet and think about how we might understand it during each stage of the learning process:
[code snippet]

#### Building Knowledge

When starting out as a programmer, we tend to read through code pretty slowly and literally and think of it only in its individual pieces. Syntax and semantics are hard to separate, and it's difficult to reason about large chunks of the code as a time. This is how we might think about the code snippet:

1. For loop
2. With i starting at zero
3. Keep going as long as i is less than arr.length
4. Add one to i each loop
5. Add arr[i] to end of result array
6. Add the value at that place to the sum

For a beginner writing code, this is also how they'll organize it: in declarative individual pieces that are meant to be read one at a time, top to bottom. We will continue to think and write this way until we've done enough repetition that parts of this _mean something_ to us and we can focus instead on pieces.

#### Forming Mental Models

As we start to form mental models, we zoom out a bit and start thinking of code in larger chunks rather than individual statements. We might now think of the code like this:

1. Iterate over an array
2. Copy it to a new array
3. Get a sum of the numbers

The real magic happens when we further refine our mental models. We can focus on the chunks that matter to us and ignore the chunks that don't. So instead, can recognize the familiar context of a for loop:
['iterate over an array']

Then, we can think of the meaning of the code within that context without still thinking about the context (the for loop) itself.
[second part]

An expert-level programmer will mentally zoom in and out of functions as well as files. This is why modular and well-organized code becomes vital as expertise increases: so the code follows patterns that match up with effective mental models. On a team, best practices and "design patterns" in code organization should be about forming and adhering to _shared_ mental models. Abstractions are useful for the same reasons.

#### Forming and Testing Hypotheses

Mental models are continually refined and new mental models are formed through the process of _forming and testing hypotheses_. So we might look at the for loop above and think, "Couldn't I do this with map and reduce?"

I think this is part of the reason refactors and yak shaving are so tempting: not only do we want to make code match up with our newest mental model, but reapproaching a problem lets us refine those models because we get to try some new things. Remember, though, that you can do some of this just by going through the mental and planning work for a refactor without necessarily doing the refactor itself. There is still value in exploring how you think about the code and questioning your previous assumptions!

### Overcoming the Limits of Short-Term Memory by Finding Meaning

## How can we develop expertise for any skill?

### Stages of competence and learning

### Rapid Skill Acquisition

### Prep, Practice, Mental State

## How can we help someone else develop expertise in JavaScript?

Teaching requires moving between unconcious and concsious competence.
You must do the prep, create opportunities for practice, and support a healthy mental state.

### Prep

Forming objectives, breaking down into subskills, figuring out what practice will look like

### Practice

Let them write features, use pairing, reverence for your responsibilities, don't just throw books at them

### Mental State

### Agency

## Why it Matters

Happiness, satisfaction, etc.
