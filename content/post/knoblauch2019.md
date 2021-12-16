+++
title = "Generalized Variational Inference"
author = "Jeremias Knoblauch"
subtitle = "Jeremias Knoblauch"
date = "2019-11-07"
+++

In this talk, I introduce a generalized representation of Bayesian inference. It is derived axiomatically, recovering existing Bayesian methods as special cases. It is then used to prove that variational inference (VI) based on the Kullback-Leibler Divergence with a variational family Q produces the optimal Q-constrained approximation to the exact Bayesian inference problem. Surprisingly, this implies that standard VI dominates any other Q-constrained approximation to the exact Bayesian inference problem. This means that alternative Q-constrained approximations such as VI minimizing other divergences and Expectation Propagation can produce better posteriors than VI only by implicitly targeting more appropriate Bayesian inference problems. This inspires the introduction of Generalized Variational Inference (GVI), a modular approach for instead solving such alternative inference problems explicitly. Some applications of GVI are explored, including robustness and better marginals. To showcase its applicability, GVI is deployed on Bayesian Neural Networks and Deep Gaussian Processes, where it can comprehensively outperform competing methods.
