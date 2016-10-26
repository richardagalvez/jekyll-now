---
layout: post
title: Hankel functions, BBN, waterfall mechanisms in inflation and the NFL.
---

Today was a pretty busy day. Started out the morning by working with graduate students who I tutor 
biweekly on math methods. They have an exam coming up this Friday and are pretty nervous about it. 
I'm glad I somehow still remember all sort of random orthonormality conditions for obscure special functions..!

## Thoughts on BBN

After that had a million meetings as usual and discussed some pretty interesting approaches on resolving
the Lithium problem with my colleague Bob Scherrer here at Vanderbilt University. The Lithium Problem 
interests me greatly. It seems like a rather well-posed theoretical problem in a time when it seems theoretical physics
has gone well beyond experimental grasp in fundamental physics.
For those who aren't familiar, the current big bang theory on nucleosynthesis (BBN) describes, to remarkable 
precision, what light elements and what fraction of them should be produced in the early Universe. Bob and
I wrote a paper on it recently where we allowed for their to be an extra neutrino during the time of BBN and
we follow it's predictions. If you're interested in that paper, check out [Cosmology with Independently Varying Neutrino Temperature and Number](https://arxiv.org/abs/1609.06351) and the accompanying [GitHub repo](https://github.com/richardagalvez/BBN_varying_neutrino). 

BBN works amazingly well. It tells us exactly how much Helium 4, Hydrogen and Deuterium should be produced in the very early Universe (amongst many other light nuclear species). This is all based on nuclear physics, physics that is understood
extremely well understood that has been verified time and time again to amazing precision. By observing clouds of gas 
that are extremely far away, and of course back in time, we can the check the predictions of BBN. 

All seems to work alright when you check He-4 and deuterium, etc., but when you get to lithium you get a big problem. 
BBN predicts too much lithium, more than we see in low-metalicity stars, by about a factor of 3-5, depending who you ask 
(btw, you have to measure the lithium abundance in stars in our galaxy that have a low metal content, this tells you the 
chemical constrituents are still in their primordial form).

So we were talking about this problem and we were hypothesizing what are some clever possibilities that could 
resolve the issue. This is a pretty active area of my research. Before I move on from BBN though, I wonder if there 
are more elements that disagree highly with BBN predictions. Is it really *just* a lithium problem, or do we have a 
larger BBN problem at the lighter elements? The issue is that whatever processess help fix this issue may also affect 
chemical abundances of other elements.. and well, we have to cross-validate there as well. Can't just somehow fix 
lithium and mess other elements up (which is what most people end up doing when they try fixing the lithium problem).

In either case, I think taking a close look at the Lithium Problem should reveal some interesting new 
break throughs in physics. Anyway, that's why I've been focusing my attention so much on that lately. There must be major
breakthroughs to be made there in particle physics.

## Waterfall Mechanism in multifield inflation

I came across a paper today on primordial black holes and how they can be produced with the so-called *waterfall 
mechanism*. Effectively, this mechanism divides the 60 or so e-folds of inflation (how many times we need the 
universe to exponentially expand to solve the [horizon problem](https://en.wikipedia.org/wiki/Horizon_problem)) 
into two phases. In phase I the usual slow roll inflaton field dominates the expansion and then a second 
field takes over and drives the rest of inflation to an end (quantum instability ceases inflation). Both of these 
fields of course have very different dynamics which helps with non-gaussianities (this is the phenomena that contributes 
non-gaussian effects to the otherwise *pretty much* perfectly gaussian cosmic microwave background).

So of course there are tunable parameters in this inflationary potential, and the authors of this paper (which 
I'll just omit here) pick these parameters perfectly to get primordial black holes of just the right mass which would have 
evaded our best experimental efforts. I was asked to read and present this paper for a research group that does mostly 
galaxy simulations, and they wanted to know if it was something they should consider carefully. I'll have to go with a 
no on this one. The mechanism is more of a toy model to show how inflation could end, but to draw direct phenomenological
consequences from a simple matter of principle model seems a bit premature to me.

## NFL Analysis

I recently decided it might be interesting to attempt to use machine learning techniques to predict success at
the NFL level for American football. This was inspired by the movie *Movie Ball*, which is pretty great. See my 
github project [NFLAnalysis](https://github.com/richardagalvez/NFLAnalysis) for more info. Probowl voting is currently 
ongoing and I would love to have some predictions before we know for sure who is sent to the probowl! It's good fun in
either case to distract me a bit from serious science research. And in either case, I've actually had to learn a lot about
imbalanced datasets.

Today was a good day with this project in either case. I got an random forests classifier to predict 4 probowl quarterbacks! Confusion matrix below. It did guess 6 wrong however, but I think it's progress.

![](https://s13.postimg.org/up2dtc09x/image1.png)

