---
layout: post
title: Statistical mechanics of learning networks
---

I haven't updated the research blog in sometime since I've been exceptionally busy, yet even more than usual, considering
I've been submitting applications for various fellowships and preparing for the Ted talk. I can't wait until November 17th;
my life may actually slow down considerably!

# Statistical Mechanics of Learning Networks

I've been reading more and more recently about neural networks and various machine learning techniques. Especially ever since
coming across directional graphs and [Boltzmann Machines](https://en.wikipedia.org/wiki/Boltzmann_machine), it has become 
rather clear that there exists a statistical field approach to, what I am now calling more generally, Learning Networks. The
realization has been coming slowly as I've been studying this field over the past year or so, and perhaps the biggest break
through was when I realized that the most common descriptions of neural networks I've come across seem to describe them as
two dimensional scalar lattice field theories with, what are called 'propagators' in the artificial network literature or, what
lattice field theorists usually call link matrices. The parallels are uncanny, it's truly fascinating.

The one question that has been really puzzling me however is that in lattice field theory, one minimizes the action to find the
classical vacuum. Quantum fields are then seen, effectively, as excitations about this vacuum. What's been bothering me
about learning networks is that there is no physical theory to learn, there is no 'classical vacuum.' The one thing the learning
networks have available to them is data from which they attempt to topologically adjust themselves to, until they accommodate 
the data sufficiently.

It occurred to me recently that this is in fact the missing link in my mind. While lattice field theories 'learn' the classical
vacuum by reducing the action, learning networks 'learn' the background geometry of their 'data space'. I'm not entirely sure 
about the details, but I'm rather sure this may be what's mathematically happening.

If this is true, it wouldn't just be a clever math trick, or a curious representation, it would mean
all of the machinery from statistical field theory would instantly translate over to learning (or neural) networks. Techniques 
like Feynmann diagrams, non-perturbative effects, renormalization flows, wilson loops, goldstone excitations, symmetry breaking
.. Really, it's quite exciting to think about.

I've joked with a few friends that I was going to write a 'postdoctoral thesis' and really, I meant it as a joke-- but now I'm
thinking about taking this on as a serious project before I'm done at Vanderbilt. Guess it's time to break out the statistical
field theory text books..

