+++
title = "On the robustness of gradient-based MCMC algorithms"
author = "Sam Livingstone"
subtitle = "Sam Livingstone"
date = "2019-09-19"
+++

We analyse the tension between robustness and efficiency for Markov chain Monte Carlo (MCMC) sampling algorithms. In particular, we focus on robustness of MCMC algorithms with respect to heterogeneity in the target and their sensitivity to tuning, an issue of great practical relevance but still understudied theoretically. We show that the spectral gap of the Markov chains induced by classical gradient-based MCMC schemes (e.g. Langevin and Hamiltonian Monte Carlo) decays exponentially fast in the degree of mismatch between the scales of the proposal and target distributions, while for the random walk Metropolis (RWM) the decay is linear. This result provides theoretical support to the notion that gradient-based MCMC schemes are less robust to heterogeneity and more sensitive to tuning. Motivated by

these considerations, we propose a novel and simple to implement gradient-based MCMC algorithm, inspired by the classical Barker accept-reject rule, with improved robustness properties. Extensive theoretical results, dealing with robustness to heterogeneity, geometric ergodicity and scaling with dimensionality, show that the novel scheme combines the robustness of RWM with the efficiency of classical gradient-based schemes. We illustrate with simulation studies how this type of robustness is particularly beneficial in the context of adaptive MCMC, giving examples in which the new scheme gives orders of magnitude improvements in efficiency over state-of-the-art alternatives.

