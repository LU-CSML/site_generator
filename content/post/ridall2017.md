+++
title = "Sequential Bayesian estimation and model selection"
author = "Gareth Riddal"
subtitle = "Gareth Riddal"
date = "2017-12-20"
+++

Work done in collaboration with Tony Pettitt from QUT Brisbane.

I would like to:

1. Introduce the Dirichlet form, which can be thought of as a generalisation of expected squared jumping distance, and show that the spectral gap has a variational representation over Dirichlet forms.  
2. Introduce the asymptotic variance of a Markov chain, which is the theoretical equivalent of the practical measure of 1/effective sample size, and provide a variational representation of this. Amongst other results this leads to a trivial proof of the Peskun ordering.
3. Introduce the conductance of a Markov kernel; if this is strictly positive then all sensible asymptotic variances are finite.

Over the last 40 years, Bayesian estimation and model selection has been implemented to address a large variety of complex real-world problems through the use of sophisticated sampling schemes. However, for each stochastic method, there is a computational cost.  For our application, the cost of using stochastic techniques is so high that we explore the use of an alternative deterministic method.  Through the use of a proposal mechanism we assemble potential models sequentially and in parallel, truncating those with insufficient cumulative evidence. Our model shows big improvements in speed over RJMCMC and also is able to accommodate parameter drift. This was not modelled satisfactorily in the paper of Ridall et al., 2006.
