+++
title = "Using Gaussian processes to infer pseudotime and branching from single-cell data"
author = "Magnus Rattray"
subtitle = "Magnus Rattray"
date = "2019-10-09"
+++

I will describe some applications of Gaussian process models to single-cell data. We have developed a scalable implementation of the Gaussian process latent variable model (GPLVM) that can be used for pseudotime estimation when there is prior knowledge about pseudotime, e.g. from capture times available in single-cell time course data [1]. Other dimensions of the GPLVM latent space can then be used to model additional sources of variation, e.g. from branching of cells into different lineages. We have also developed a branching Gaussian process to explicitly model such branching and identify which genes are associated with cellular branching and whether they branch late or early [2]. To scale up inference in these applications we use sparse variational Bayesian inference algorithms to deal with large matrix inversions and intractable likelihood functions, implemented using the gpflow library.

##### References

[1] Ahmed, Sumon, Magnus Rattray, and Alexis Boukouvalas. "GrandPrix: scaling up the Bayesian GPLVM for single-cell data." Bioinformatics 35.1 (2018): 47-54.

[2] Boukouvalas, Alexis, James Hensman, and Magnus Rattray. "BGP: identifying gene-specific branching dynamics from single-cell data with a branching Gaussian process." Genome biology 19.1 (2018): 65.

