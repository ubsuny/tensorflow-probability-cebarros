# Problem 1

The purpose of this part of the homework was to generate random walk graphs so that we can plot $\dfrac{ \partial }{ \partial t} P(x,t)$ vs. $\dfrac{ \partial^{2} }{ \partial t^{2}} P(x,t)$, where $P(x,t)$ is a probability distriution function which for all practical purposes can be taken to be a Gaussian. The slope of this graph is proportional to the diffusion coefficient $D$, with the proportionality constant having to do with the dimensionality being considered. 

With all this in hand, we can calculate $D$ for all three dimensions. As it turns out, the diffusion coefficient is independent of dimensionality, and is equal to $1/2$. All graphs produced gave values for $D$ that were very close to the expected value, for both the numpy and Tensorflow implementations, though the latter gives different values everytime the notebook is run.

# Problem 2

This problem was considerably more challenging, and required the use of a few tutorials to complete. Our goal was to run a Metropolis algorithm and create a MCMC from two uneven Gaussian probability distributions. Although parts of this problem are still a bit unclear, the histogram given closely overlaps with their theoretical counterparts.






