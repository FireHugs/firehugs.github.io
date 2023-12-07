---
layout: post
title: Make Reversible Decisions Quickly
cover-img: ["/assets/img/posts/miami-squirrels.jpeg" : "The squirrels in Miami are weird and loud, 2022"]
# subtitle: There's lots to learn!
# gh-repo: daattali/beautiful-jekyll
# gh-badge: [star, fork, follow]
# tags: [test]
# comments: true
---
<br><br>

I don't watch TV nearly as much as I used to. Between hobbies, friends and family, there just isn't as much room for it in my life anymore. But, once in a blue moon, I'll be too tired to socialize or do something active, and too restless to go to sleep.

So I'll fire up a streaming service, and start scrolling through. I'll watch some trailers, look at average episode run times, online reviews. I'll start filling out the mental stack ranking in my head. Pressure increases with every passing minute of perusal to be the Bestest Show Chooser in the history of couch potato-ing.

Before I know it, I've run down the clock on my evening leisure time. I shut the TV off, grumble dejectedly as I climb into bed, and lie there thinking: "I make important decisions for a living. How did I beef it so hard on something so simple?"

Jeff Bezos popularized a great decision-making tip: 

*<center>Make reversible decisions quickly</center>*

 If I'd taken a second to think of the stakes of the decision, I'd have quickly realized I should have picked the first sensible choice I came across with a short run time and decent reviews. If it didn't grab me, I could just bail and use that very experience to inform what I was actually looking for that night.

I'm going to assume Mr. Bezos was more concerned with making good technology decisions than helping me get into Tiger King, though. So let's pivot to how this can useful to engineering leaders.

## Hello teacher, tell me, what's my lesson?

The key insight is that the amount of time spent agonizing over a choice should be proportional to its stakes. The lower the cost of making the wrong choice, the faster you should just pick the most sensible one based on limited information and move on to execution. 

This is especially salient in engineering for a few reasons:
* Engineers are trained problem solvers, so they're very good at uncovering new trade-offs the longer they think about a problem
* Emphasis on agility in software stems from the inherent uncertainty of our work. We often don't fully understand the problem we're trying to solve at the outset. We try stuff, we learn from what works and what doesn't, and we iterate

Both these factors make us incredibly effective at inducing analysis paralysis when important decisions arise.

This wasn't much of an issue as a front-line manager, since a lot of my focus was on helping my team move fast, keep them unblocked. Whenever necessary, I'd pull them out of rabbit holes and help them puzzle out contentious choices. The stakes of making a wrong call were small (slipping a sprint by a few days), and I was close enough to the day-to-day technical work to hold the entire problem space in my head.

But being a manager of managers is a completely different ballgame. You'll dealing with lots of complexity all the time, and you can't afford to shoot from the hip, as an especially bad call can derail a release. Also, you rely on your subject matter experts more and more for technical context as your duties pull you away from the day-to-day of building the software. What do you do then?

## Rising to the occasion

When you're routinely debating longer-term investments in a technology strategy to make your systems more expressive, extensible, or sustainable to maintain down the line, you can't just think of them in terms of "Do I do them or not?". They're no longer binary choices because time investments at this scale have a significant opportunity cost. There are other things you could be doing with that time that might be equally or more valuable when compared through a particular lens.

So you start trying to understand your product strategy more deeply, and maybe you read a few books on product management. Your empathy with user personas outside your own grows, and you prioritize work more aggressively in terms of perceived value according to customer interviews and market analysis.

And if you're working in an organization of the scale where they need to be very deliberate about this kind of thing and work involves collaboration between a bunch of different teams with their own roadmaps, maybe you learn about technical program management along the way. You keep those communication lines open and you connect roadmaps together at their key deliverables. Maybe you've even got program managers on staff, and they tell you about formal risk management.

So you start reading about that too, and you start thinking about all the potential risks that lie in any given path, and your job becomes a little bit clearer. Find the technical risks no-one else is thinking about, and find ways to mitigate them.

You feel pretty good about all this. You acclimate to managing complexity and collect a bevy of decision-making tools for whenever something comes up.

But somewhere along the way, low-hanging fruit decisions become a nightmare to litigate. You're no longer as nimble with the easy wins as you once were, and you're worried you're alienating your experts in the process.

What happened?

## How it goes all wrong

The trap is running every technical decision through the same gauntlet irrespective of the stakes. "Make reversible decisions quickly" tells us we need to tune our opportunity cost efforts according to the problem at hand. Otherwise, being deliberate and risk-aware turns into being indecisive and risk-*averse*.

There are plenty examples of ways in which the groundwork we've laid can undermine our choices
* We shy away from things with longer timelines because of all the factors that can shut it down. This is healthy when incremental value is possible, but unfairly discards opportunities to solve valuable problems for users that are just plain hard
* We're overly protective of the product critical path, discounting the fact that even the product strategy is a living document subject to iteration
* We don't want to gum up the works for dependent teams, so we shy away from work that exacerbates dependencies

Before you know it, you've become incredibly skilled at talking yourself out of committing to potentially valuable ideas that don't fit cleanly inside your decision framework.

## Keep simple problems simple

If you're going to be deliberate, start by being deliberate about the stakes. How would you rate the reversibility of the decision? What's the worst-case scenario if you went down the wrong path? How much are you willing to invest in gathering more information before making a call?

In this quest for data, pay attention to your bias to discount the options you understand less. And if you're going to invest time in discussions and debate, keep these exercises short and goal-oriented. If you can't get all the information you need in the room, favour allocating short spikes of experimentation over more theory-crafting. You'll usually learn a lot more that way! And if the work continues, you'll already have some initial momentum.

If someone comes to you with something they want to try where the stakes can be kept low, avoid defaulting to making them prove its value through elaborate estimation exercises, technical reports and the like. Even if you personally think it's the wrong choice, consider giving them the opportunity to try it anyway if they feel strongly about it. Maybe they'll surprise you! Proofs of concept have a way of teaching us a lot more than documents. And even if you're right in the end, at least they'll naturally arrive at the same conclusion as you with a first-hand lesson and greater trust.

## Know what would make you change your mind

In situations where you think technical due diligence is absolutely necessary, don't ask people to jump through hoops unless you can clearly articulate how your decision will be affected by it. If you want an estimate, make sure you already have an answer for how much is too much. If you want a technical report, make sure you are specific about the concerns they can address. 

I've seen situations where leaders use these asks as a deferral tactic, whether they realize it or not. They're secretly hoping it will sort itself out on its own, but a big part of our jobs as leaders is to wade into the complexity and make the hard calls to keep things moving. Don't create busywork for folks.

Bezos also had another nugget that might be useful if you're unsure whether you've gone deep enough into the rabbit hole: "Most decisions should probably be made with somewhere around 70% of the information you wish you had". Any more than that, and you'll probably gett diminishing returns. Always keep in mind that spending time trying to make a decision has an opportunity cost too!

<br>
And if, at the end of a gruelling work day, you're feeling restless because you still don't know which call to make, at least you should have an easier time picking a friggin' TV show to watch to wind down.