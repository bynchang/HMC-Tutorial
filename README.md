This repo contains a teaching vignette that introduces the Hamiltonian Monte Carlo (HMC) Algorithm. It is a powerful MCMC algorithm that explores the parameter space of a target distribution more efficiently than the Metropolis-Hastings algorithm, and is used by many probabilistic programming languages such as Stan and Pyro.
The vignette is designed for people who have some knowledge in MCMC algorithms (i.e., knowing Metropolis-Hastings and Gibbs sampler), and is split into several parts:
• The setup of a Hamiltonian system
• The link between the target distribution and the Hamiltonian
• The HMC algorithm itself (also explaining the intuitions of each step in the HMC)
• An example of HMC for a standard normal
• A comparison between HMC and MH for a bivariate normal
• The effect of hyper-parameters of the HMC

View the hmc_tutorial.ipynb file or download the hmc_tutorial.html for the vignette.
The hmc_sampler.ipynb file contains code that implemets the HMC sampler.