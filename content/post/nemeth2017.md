+++
title = "Pseudo extended MCMC"
author = "Chris Nemeth"
subtitle = "Chris Nemeth"
date = "2017-11-29"
+++

MCMC algorithms are a class of exact methods used for sampling from target distributions. If the target is multimodal, MCMC algorithms often struggle to explore all of the modes of the target within a reasonable number of iterations. This issue can become even more pronounced when using efficient gradient-based samplers, such as HMC, which tend to tend to become trapped local modes.

In this talk, I'll outline how the pseudo-extended target, based on pseudo-marginal MCMC, can be used to improve the mixing of the HMC sampler by tempering the target distribution.

This is joint work with Fredrick Lindsten, Maurizio Filippone and James Hensman. 
