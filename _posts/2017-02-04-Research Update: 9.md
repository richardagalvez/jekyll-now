---
layout: post
mathjax: true
title: Predicting discoveries part 1
---

I've been working on a problem recently that I think is a rather interesting application of machine learning. Unfortunately I cannot give too many specifics as the algorithm I've developed is currently being used in two papers that are about to be submitted for publication. When they are submitted though, I will most definitely give a well describe tutorial here!

Here is the research problem though: Suppose that you have a very large dataset, say of visitors to your website (not my website, cause no one comes here!). Let's say that you would like to know how many of your total visitors are runners and you only for certain that 10% of them have voluntarily come forward and shared that information with you, such that your dataset has this structure: 

<img align="center" hspace="50px" src="https://raw.githubusercontent.com/richardagalvez/richardagalvez.github.io/master/images/posts/Figure1.png" style="width: 300px;"/>

Question then is *is it possible to recover which members of the unknown group are also runners?* I've been think about this problem deeply recently and I think I have finally figured out an algorithm to do this. Unfortunately I can't describe the solution in much detail here again due to the paper about to be submitted. I am thinking now though, what kind of machine learning algorithm is it? What should it be called? It's basically a supervised machine learning algorithm that reveals which members of the unknown set are most likely to be like the set you do have the answer for. I suppose **it is** a supervised machine learning discovery algorithm, but that seems rather long-- maybe just supervised discovery algorithm. 

