---
layout: post
title:  "Efficient Sampling with Discrete Diffusion Models: Sharp and Adaptive Guarantees"
date:   2026-02-18 15:43:00 +00:00
image: /images/dontpanic_viz3.png
categories: research
author: "Daniil Dmitriev"
subtitle: "preprint"
authors: "<strong>DD</strong>*, Zhihan Huang*, Yuting Wei"
venue: "preprint"
arxiv: https://arxiv.org/abs/2602.15008
---

We analyze two noising processes for score-based discrete diffusion models: uniform and absorbing. 
For the uniform noising process, we prove an upper bound for the number of sampling steps scaling linearly with
the ambient dimension and logarithmically with the vocabulary size. 
This is achieved with a tau-leaping sampler, for which we show a matching lower bound.
<br>For the absorbing noising process, we show an upper bound that scales (up to logarithmic factors) with the <it>effective total correlation</it>
of the distribution, which potentially can be sublinear in the ambient dimension, or even constant for certain structured distributions.


[arXiv link](https://arxiv.org/abs/2602.15008){:target="_blank"}
