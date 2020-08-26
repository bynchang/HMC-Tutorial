This repo contains a teaching vignette that introduces the Hamiltonian Monte Carlo (HMC) Algorithm. It is a powerful MCMC algorithm that explores the parameter space of a target distribution more efficiently than the Metropolis-Hastings algorithm, and is used by many probabilistic programming languages such as Stan and Pyro. <br/>

The vignette is designed for people who have some knowledge in MCMC algorithms (i.e., knowing Metropolis-Hastings and Gibbs sampler), and is split into several parts: <br/>
• The setup of a Hamiltonian system <br/>
• The link between the target distribution and the Hamiltonian <br/>
• The HMC algorithm itself (also explaining the intuitions of each step in the HMC) <br/>
• An example of HMC for a standard normal <br/>
• A comparison between HMC and MH for a bivariate normal <br/>
• The effect of hyper-parameters of the HMC <br/>

View the vignette [here](https://nbviewer.jupyter.org/github/bynchang/HMC-Tutorial/blob/master/hmc_tutorial.html). <br/>
The hmc_sampler.ipynb file contains code that implemets the HMC sampler. <br/>
