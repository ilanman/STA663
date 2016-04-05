MCMC Using Hamiltonian Dynamics:
========================

Neal’s 2011 paper provided the foundation for what is now called Hamiltonian Monte Carlo. It improved the “simple random-walk” proposal of the Metropolis Algorithm, by ensuring that those proposals are in the direction of steepest ascent in the posterior distribution. It differs from the Metropolis-Hasting algorithm by reducing the correlation between successive sampled states by using Hamiltonian evolution between states, a concept derived from quantum mechanics. The property of “energy” or “volume” preservation within Hamiltonian dynamics will be extremely important in the derivation and implementation of this algorithm.

We plan to build a Hamiltonian Monte Carlo algorithm from scratch, giving us the opportunity to deeply understand its theoretical and practical aspects, specifically its underlying quantum mechanical foundations. We will implement the algorithm on very large data sets and compare its efficiency with other MCMC approaches, such as Gibbs Sampling, Metropolis-Hastings, Slice Sampling, and Reversible Jump (if applicable). We will compare efficiency, both in time and estimation.


