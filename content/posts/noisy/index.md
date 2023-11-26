---
title: "Riding the Noisy Research Track"
date: 2021-07-28
authors:
    - Jitesh Jain
---

Alright, people! This article will share my experience and learnings during the last eight months as an undergrad researcher. For those reading one of my blogs for the first time, I am a CSE undergrad (about to enter 3rd year) and am working as a _Research Intern_ at [_SHI Lab @ UO_](https://www.humphreyshi.com/people) and [_Picsart_](https://picsart.com/).

Now, before we dive in, let me clear it out that I have probably had a more intense research experience for better or worse than some of the other undergrad people at IITR. So, don’t make any judgments about research based on the content in this post 😛. So, we got that sorted out. Let’s begin!

My research life is going soooooo good :3

> Disclaimer: If it wasn’t clear by now, this isn’t a post where I will tell you how to get a research intern. You will find a lot of those with a single google search.

The Promising Start
===================

Now, when you are just starting with research and working with a pro researcher, you can’t wait to take up a research project and get into the mix. That was the case with me, no exceptions, each cell in my body was excited to start _“my own”_ research project(s).

So, the journey begins!

!["despicable"](despicable-me-minions.jpg)

It all begins with a literature survey, reading tons of papers, getting to know the dreaded so-perfect _SOTA (state-of-the-art),_ coming up with the so-called _unique innovations,_ and then finding another paper with the innovations already implemented. That’s right. It isn’t as easy to find a new problem to work on amidst the immense ocean of existing works. It took me almost one month at the start of both my interns to find a project to work on!

So, don’t get all stressed and messed up if you don’t have anything to work on at the start; paper reading is the most underrated skill without which you can’t excel in research. Feed your mind with ideas from the others and create a new one with a mix-match 😉. That’s what research is: **_building on existing works and improvising_**! That brings me to the next section about building.

Let’s Build the Concept.
========================

> Great! You have a concept to work on, but can you build it?

Here, now you will have two ways to proceed:

1.  **First:** _Take up an open-source implementation (I am so grateful that these exist 🙈) and build on it_
2.  **Second:** _Start the implementation from scratch all by yourself_.

Here, **DON’T** let the craze of learning sway you towards the _second_ option. You learn much more building upon an existing implementation: the code architecture, good practices, and most importantly, how to put modules from different places together in a **bug-free** (more on this later) manner. On the other hand, doing all the implementation yourself will be a waste of time, effort, and, well, inherent smartness 😛. (To be clear, I **_didn’t_** make this mistake, but the thought did cross my mind once ¯\\\_(ツ)\_/¯)

Why is this important? Well, as the research community expands, more and more people are open-sourcing their code, and most of the time, you will use existing works as your baseline, and it is essential to **_get used to their setting and working_**, which brings me to the next section.

**This paper looks good.**
==========================

I often used to ask myself: **_What’s the significance of the many research conferences held around the globe?_** The papers are probably months old, outdated, and already read by the targeted audience by the time the conference is organized. Sure, you get to talk to the authors, participate in challenges & workshops, and what else?

It turns out conferences are like a **_quality-assurance mark_** (well, most of the time). If a work has been accepted to a reputed conference, it’s an excellent decision to take that as your baseline. If not, then well, you better do an autopsy on the claimed results.

As a fun fact, there was a work about 3–4 months back unpublished, just _floating out on the arxiv._ I took that as a baseline like any good kid would do. So, the work was fluked, the implementation and most probably the idea as well. And even more interesting, the primary author knew about the issues. That’s when I invented the rule:

> Never trust a paper blindly, ever!

Btw, I also decided this. It took a long time coming 🙈

Understand the DATA!
====================

> DL models are data-hungry!

It’s a common saying in the DL community, and for a good reason. Before diving into the network structure code, starting the experiments, and all that goes on during the sprint, it’s nice to prioritize understanding the dataset and checking its correctness. You might think most papers used this dataset, so let’s load the contents and start! That’s right, and at this point, we need to verify if the pre-processing steps work as expected and we didn’t tweak the input in the wrong way unknowingly.

It happened with me once, where I took the data processing script from one of the works and used it straight away only to find a week later that the inputs were wrong and not synced to my task 😕. So, _respect the data inputs. Without a correct input, you get senseless outputs!_

What is this?! Why didn’t I check the data inputs ?🤦

DO it YOUR Way!
===============

As an undergrad researcher, you generally have an advisor who is either a grad student or the prof himself might be the advisor. Either way, don’t expect your advisor to help you in the implementation process. During the meetings, often, they may advise you to change the pipeline in a certain way. Here, understand the logic and implement it in your way. Don’t just follow orders from the advisor. They have probably never looked at the codebase and so have no idea about its state. You created the codebase, so make changes to the code in your way.

Don’t worry if you make big fat bug blunders. That’s how you learn the art of debugging, and with time, the efficiency increases. So,

> Take the what, why, a little how from the advisor and answer the complete how yourself!

Having your recipe is more fun😛

The Crisis.
===========

Cool, so you have a concept, a credible baseline, and starting implementation. You are ready to start the experiments and then publish your work with a bang. Life is awesome!

Prank Alert, you just got research bombed 🙅. If your first set of experiments work well, then you are the luckiest person on the planet! Generally, **The Crisis** encompasses a few phases:

Oh, this doesn’t work; let’s try that idea instead!
---------------------------------------------------

One thing didn’t work. You tried changing a few hyperparameters, a few modules, the code is a total mess, and then you throw the current idea out and try a completely new one. That makes sense, but remember that when you are trying different things, be patient, don’t change more than one setting in any of your experiments. Track the effects of the changes and then make a decision.

PS: I have switched ideas a few times, so it isn’t a big deal, I suppose 🙈.

**The Never-Ending Trials.**
----------------------------

Your new idea doesn’t work either. You are already into 3–4 months of experiments. Here is where most people realize that research isn’t the right choice for them, so they opt out, I suppose.

At this time, one starts to develop something called the _Imposter Syndrome (btw, check_ [_this blog_](https://daleonai.com/my-take-imposter-syndrome-tech) _by_ [_Dale Markowitz_](https://daleonai.com/about) _about Imposter Syndrome in Software Engineering)_ if they didn’t earlier already. So here’s what I did to fight that:

*   Talking to a few senior researchers about their experience helped a lot.
*   Focusing on the learning and not on producing a paper. At least saying that to myself helped me keep the stress and anxiety to a low level. 😛
*   Experience is the primary thing I am here for. The undergrad years are bonus years for research.

Btw, I am still in this phase, so yeah, way to go!

Welcome to the world of research!

**The Sorted Phase.**

This is the phase where the experiments finally work, the paper rolls out, and it is time to move onto newer projects. I hope to experience it someday 🤞.

I’m Bored :(
============

Because I am a relatively young researcher and also a little impatient (at least that’s what I feel), I often have those moments when I want to scrap the ongoing project and take up something I find more interesting at that moment. There is no fixed step for this phase, and you might be better off sticking to the current project or starting a new one. It all depends on the project and scope, to be honest.

Research Finally Pays off :)
============================

I found many seniors telling me back in my first year that undergrad research generally doesn’t earn as much money as the other development-centric activities in India. This is true to an extent, but eventually, you will get a research intern where a development intern package won’t bug you anymore 😛. If you are wondering about me, SHI Lab is an unpaid one, and Picsart pays me.

Deep Learning Research is a lot of Engineering.
===============================================

I knew that implementing things in deep learning research isn’t an easy job. If you are one of those people who think that all that happens in research is thinking, and implementation is the simple part, then you are in for a bumpy ride!

Indeed, implementations in software development fields and DL research aren’t too different. In the end, all you have to do in both cases is develop/create the most optimal, efficient algorithm and write a script for executing that. We spend most of the time debugging the code, creating diagrams for the pipeline, and running toy experiments crucial to the research process. It’s a good habit to write the code and debug it in your mind as you go along, creating imagining the expected functionalities of the modules. If you are lucky and alert, you may find a big fluke in the pipeline while writing the code itself \\O/.

So, it’s not a bad idea to put your developer/engineer hat on at that time. 😛

Well, research is more engineering than what I used to think 🙈

TLDR?
=====

Alright, that turned out long. Let me provide you with a TLDR here:

*   _Carry out literature surveys_ before starting a project.
*   Choose the baseline carefully and go with an existing implementation if available.
*   Spend some time understanding the dataset.
*   Don’t fully listen to advisors about how to implement a pipeline 😛
*   Fight the crisis phase gallantly :)
*   Your engineering and research shall pay off!

Conclusion
==========

Right, so that’s it, guys! I tried to share a few learnings from my short research experience so far. In my opinion, what makes research different from other fields is the **_enormous need for perseverance_** while working. We have no idea if the problem even has a solution or not. We are wanderers, traversing the planes of experiments to find a positive answer, losing our way in the middle, getting back on track again, which makes it exciting tbh!

If you have any questions, opinions (appreciation included :P), or want to discuss your experience (non-research included), contact me!

I wrote another blog about research. Wow!

You can learn more about me on my  [_webpage_](https://praeclarumjj3.github.io/)_._

