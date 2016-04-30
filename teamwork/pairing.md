---
layout: page
title: Pairing
permalink: /teamwork/pairing/
category: teamwork
slug: Why won't the team pair up? Should they even?
author: michael
---

Does Pairing Actually Work?
--------------------------------------------------------------------------------

As you know, **pair programming** or **pairing** has been around since the beginning of XP. Advocates say when engineers work together, side by side on the same glass, they will produce higher quality code (possibly) more quickly than working individually. From a craftsmanship perspective, pairing makes a lot of sense for sharing knowledge and elevating the craft of writing code.

But does it actually work?

In December 2015, a boutique Ruby shop decided to run an experiment.(1) They formed two teams; each were to work on their own project with the same story point backlog. One teamed paired. The other didn't. There's a lot to read about the metrics they tracked and studied in the experiment progressed, and you should read them. Here are some of their findings:

1. Pairing seem to produce **higher quality code**, and the pairing team was able to burn about the same number of story points as the team who used individual engineers.
2. Pairing seemed to **boost motivation, communication, and organizational skills** among team members, which shouldn't be too surprising.
2. Pairing was most effective when the team members were neither close friends nor adversarial.
3. **Pairing was better for challenging, difficult tasks** instead of simple ones.
4. Never force pairing, but you might need to **strongly** encourage it (see below for more) or do a lot more than you think to get the pairing to actually happen.

If It Works, Then Why Do Engineers Not Pair?
--------------------------------------------------------------------------------

Despite pairing's reputation and (anecdotal) proof of pairing's ability to deliver higher quality code and better team dynamics, few development teams routinely pair up. In an April 2016 article,(2) Linda Cook offers some possible reasons why.

**Logistics:** A very practical, nuts and bolts hurdle to pairing may be simple to solve. To pair, you simply need enough physical space, big enough monitors, chairs, white boards with markers that actually work, and shareable keyboards and mice.

**Management**: harder problems come up when we consider the organization, however. Managers, especially in organizations that haven't fully embraced agile or may have missed the whole XP-thing, just assume they're going to get half the output. This is probably false (see above), but those managers are also overlooking the other benefits discussed above -- better teamwork, more motivation, higher quality teams. That's not too hard to overcome, but might take some explanation to senior leaders or the non-technical business side of the house.

**Incentives**: Another organizational hurdle cited by Cook is more insidious. If the organization values individual developer heroics and capabilities more than teamwork and mentoring, then high performing individual engineers have no incentive to pair and share their capabilities. This particular hurdle may not be solvable by a sole engineering manager and may need to be addressed higher up in the engineering organization.

**Safety**: Safety factors within the team may be the most insidious block to effective pairing. Software engineers are famously, and generally speaking, insecure about their code, even among their closest coworkers. So as a lead engineer or engineering manager, you need to increase the amount of safety your team feels within the team. This means it needs to be safe for the engineers to make mistakes, reveal their code without unnecessary judgment or ridicule, make mistakes, or fail from time to time. I know this was an issue for me personally. Of course, increasing the amount of safety on the team has huge benefits beyond just pairing -- but it seems to a necessary condition to pairing.

In summary, pairing seems to work, but you've got to the get some organizational and team stuff right before you're going to get anything out of it.

When You Can't Solve the Organizational, Management, and Safety Issues
--------------------------------------------------------------------------------
Even if you can't get all the management, organizational, or safety issues right you might make a lot of progress if you encourage the engineers to pair up on the hardest problems. With hard engineering problems, some of the management, organizational, and safety issues either solve themselves naturally or get suspended temporarily. And you might get some of the quality, communication benefits in the process.

I'll be trying this myself on a few projects where I can't control all the variables I want to, so stay tuned.

**References**:

1. [The Pair Programming Experiment](http://blog.elpassion.com/pair-programming-experiment/)
2. [Why Won't They Pair?](http://infoq.com/articles/why-wont-pair)
