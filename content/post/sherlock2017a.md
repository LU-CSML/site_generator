+++
title = "Delayed-acceptance MCMC with examples: advantages and pitfalls and how to avoid the latter"
author = "Chris Sherlock"
subtitle = "Chris Sherlock"
date = "2017-01-26"
+++

When conducting MCMC using the Metropolis-Hastings algorithm the posterior distribution must be evaluated at the proposed point at every iteration; in many situations, however, the posterior is computationally expensive to evaluate. When a computationally cheap approximation to the posterior is also available, the delayed acceptance algorithm (aka surrogate transition method) can be used to increase the efficiency of the MCMC whilst still targeting the correct posterior. In the first part of this talk I will explain and justify the algorithm itself and overview a number of examples of its (successful) application. It has recently come to light, however, that the delayed-acceptance procedure can sometimes "break" the MCMC algorithm in a sense I will describe. In the second half of this talk, through simple examples, I will describe intuitively why sometimes the DA procedure breaks the Metropolis Hastings algorithm and sometimes it does not, and will give (provably correct) guidelines on how to ensure the latter.