---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Indranil Halder is a Research Associate at the Harvard John A. Paulson School of Engineering and Applied Sciences in the Machine Learning Foundations Group. He is currently working with [Cengiz Pehlevan](https://seas.harvard.edu/about-us/directory?search=%22Cengiz%20Pehlevan%22). Previously, Indranil was the Harvard Quantum Initiative Fellow at the Center for the Fundamental Laws of Nature with [Daniel Jafferis](https://www.physics.harvard.edu/people/facpages/jafferis).

## Research

**Theoretical machine learning**

Indranil is a theoretical machine learning researcher specializing in generative AI, with core interests in the interpretability of knowledge representations and the safety, robustness, and optimization of deep learning systems. His recent work focuses on inference-time sampling algorithms and reinforcement learning.

Motivated by recent empirical successes of large language models that reallocate substantial computation from training to inference, Indranil studies the foundations of inference-time scaling. He has introduced an analytically tractable model based on Bayesian linear regression with a reward-weighted sampler and analyzed the generalization error when training data are drawn from a teacher model. This framework establishes the existence of an optimal temperature for the reward process, an optimal number of inference-time samples, and an optimal reward that can differ from the teacher. His analysis further characterizes the regimes in which scaling inference-time computation is provably preferable to collecting additional data, and shows how this advantage deteriorates as task difficulty increases.

Indranil’s work on reinforcement learning addresses both optimization and safety challenges. Hyperparameter optimization in reinforcement learning is notoriously difficult, with state-of-the-art methods often relying on evolutionary strategies. In contrast, his on-going research studies a theoretically grounded and predictable prescription for hyperparameter transfer as the language model scales, derived from a stochastic differential equation description of the underlying learning dynamics. He also investigates the interaction between reinforcement learning and model calibration: while algorithms such as Group Relative Policy Optimization improve reasoning capabilities, they can degrade semantic calibration relative to the pre-trained model. Indranil is actively developing new algorithms that preserve or enhance calibration without sacrificing reasoning performance.

In the past, he has defined and studied an analytically tractable one-step diffusion model In the context of higher-dimensional statistics, using the method of deterministic equivalence, he has proved a theorem that presents an explicit formula for the Kullback-Leibler divergence between the generated and sampling distribution, taken to be isotropic Gaussian, showing the effect of finite diffusion time and noise scale. It shows that the monotonic fall phase of Kullback-Leibler divergence begins when the training dataset size reaches the dimension of the data points. 

**Theoretical physics**

Before transitioning to machine learning, Indranil made notable contributions to theoretical physics.

During his early days at Harvard University, Indranil established a new strong-weak duality closely related to ER=EPR - the fascinating connection between entanglement and geometry. Using the duality, he has made distinct progress on the long-standing issue of thermal microstate counting of blackholes. He has also proposed a framework to evaluate the supersymmetric index in disordered systems in terms of bi-local fields closely related to wormhole-like physics.

During his graduate studies, Indranil worked extensively on theoretical developments of topological quantum computation, more precisely on Chern-Simons gauge theory coupled to matter. He discovered a condensed phase and pointed out an exact non-commutative structure in the presence of a background magnetic field. 
