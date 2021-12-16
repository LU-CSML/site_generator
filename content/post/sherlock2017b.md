+++
title = "Asymptotic variance and geometric convergence of MCMC: variational representations"
author = "Chris Sherlock"
subtitle = "Chris Sherlock"
date = "2017-05-18"
+++


An MCMC algorithm is geometrically ergodic if it converges to the intended posterior geometrically in the number of iterations. A number of useful properties follow from geometric ergodicity, including that the practical efficiency measure of "effective sample size" is meaningful for any sensible function of interest. The standard method for proving geometric ergodicity for a particular algorithm involves a "drift condition" and a "small set", and can be time consuming, both in the proof itself and in understanding why the drift condition and small set are helpful.

A variational representation can provide a direct insight into a quantity of interest and a potentially powerful tool. As a simple (and relevant) example, each eigenvalue, lambda, of a symmetric matrix, M, has a corresponding eigenvector, x, such that x' M = lambda x'. To find the largest eigenvalue one may feel it necessary to find all of the solutions to the above equation and then find the largest. Alternatively, the largest eigenvalue is also \sup x' M x, where the supremum is over all x with \norm{x}=1.

I would like to:

1. Introduce the Dirichlet form, which can be thought of as a generalisation of expected squared jumping distance, and show that the spectral gap has a variational representation over Dirichlet forms.  
2. Introduce the asymptotic variance of a Markov chain, which is the theoretical equivalent of the practical measure of 1/effective sample size, and provide a variational representation of this. Amongst other results this leads to a trivial proof of the Peskun ordering.
3. Introduce the conductance of a Markov kernel; if this is strictly positive then all sensible asymptotic variances are finite.

I have found these  variational representations particularly useful when comparing two kernels. It is especially helpful to represent the reversible MCMC kernel as a self-adjoint operator on the Hilbert space of functions that are square integrable with respect to \pi. However, I understand that, like me a few years ago, most of the audience may be unfamiliar with this, so I will take care to introduce the key ideas by analogy with finite matrices. 
