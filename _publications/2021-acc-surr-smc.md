---
title: "Accelerating sequential Monte Carlo with surrogate likelihoods"
collection: publications
permalink: /publication/2021-accelerating-surrogate-SMC
excerpt: 'Keywords: Bayesian statistics; Delayed-acceptance; Approximate likelihood; Whittle likelihood; MCMC'
date: 2021-08-18
venue: 'Statistics and Computing'
paperurl: 'https://doi.org/10.1007/s11222-021-10036-4'
citation: 'Bon, J.J., Lee, A. & Drovandi, C. (2021), Statistics and Computing, Volume 31, Issue 62.'
---

Delayed-acceptance is a technique for reducing computational effort for Bayesian models with expensive likelihoods. Using a delayed-acceptance kernel for Markov chain Monte Carlo can reduce the number of expensive likelihoods evaluations required to approximate a posterior expectation. Delayed-acceptance uses a surrogate, or approximate, likelihood to avoid evaluation of the expensive likelihood when possible. Within the sequential Monte Carlo framework, we utilise the history of the sampler to adaptively tune the surrogate likelihood to yield better approximations of the expensive likelihood and use a surrogate first annealing schedule to further increase computational efficiency. Moreover, we propose a framework for optimising computation time whilst avoiding particle degeneracy, which encapsulates existing strategies in the literature. Overall, we develop a novel algorithm for computationally efficient SMC with expensive likelihood functions. The method is applied to static Bayesian models, which we demonstrate on toy and real examples.
* DOI: 10.1007/s11222-021-10036-4
* [Journal](https://doi.org/10.1007/s11222-021-10036-4)
* [ArXiv](https://arxiv.org/abs/2009.03699)
