---
layout: post
mathjax: true
title: So much data, so little time
---

Things have been good lately in the research front. Much progress on quite a few projects-- been multi-threading since I got to Vanderbilt in various fields. I'm pretty excited to see a few papers I've been working on well outside of my comfort zone almost complete. Never did I think two years ago that I would be working on exoplanet statistics, machine learning or struggling with pandas data frames (I hate you pandas).

Nor did I think I would be pretty involved in geology projects. As it turns out, I met a great person here who happens to be a geologist. I can't help but to take a look at the data she collects-- can you imagine actually going out to the 'field', yes an actual field, and collecting your own samples? And not only that, bring the stuff back with you, go through all kinds of struggles in customs explaining where you got it from, then go back home, crush up some dirt and get data---- ttheeeennnn after all that look at the data and run analysis? Sounds pretty fun actually.

So she's been working on arsenic concentrations in a particular region of the world, which I won't divulge since she's hoping to publish this stuff soon, and I decided to help her out and show her how to use pandas and matplotlib. This is actually one of the first times I have had to deal with such incredibly messy data. Different teams gathering samples from different sites, various units used, sometimes not even written! Putting it all together, I have never seen as many Nans as I've seen in the past two days, but hey, at least I'm learning something new too.

In either case, we've made some pretty nice looking plots, here's one of various mineral concentrations by sample site:

![alt text](https://richardagalvez.github.io/images/ars_cons.png)

Unfortunately for the people in these locations, they have no choice but to drink poisonous water filled with arsenic. Hopefully there will a cheap filtration system created soon, but just to give an idea, concentrations should not increase past $10 \mu g / L$ to be considered (somewhat) safe.

Besides helping her out, been pretty busy with other projects. In particular, I'm quite excited about a novel machine learning algorithm we developed to perform an unusual supervised learning task. Surely in the near future I will be giving a detailed explanation of this algorithm in a jupyter notebook, but for now I can at least describe the problem.

Suppose you have a data set where you know each row is of either type 1 or type 2. It so happens that you only have a very small subset where you know for sure that you have type 1's but a fairly large unknown group which could be either case. It seems we've developed an algorithm that learns to pick out the observations from the unknown set which *should* be type 1. This is quite helpful in the discovery process of general science, and I'm happy to be completing a paper regarding this method. So, very soon, we can discover type 1's in unknown data and finally have nice things again.


