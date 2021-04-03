---
title: Monte Carlo
---
Algo for performing Monte Carlo:
- Initialization: Fix the number of MC steps, Choose initial $R$ and variational parameters $\alpha$ and calculate $|\psi_T^\alpha (R)|^2$.
- Initialise the energy and the variance and start the MC calc.
	- Calc a trail pos $R_p = R + r \cdot step$ wehere $r$ is a random var $r \in [0,1].
	- Metropolis algo to accept or reject this move $w = P(R_p)/P(R)$
	- If the step is accepted, then we set $R = R_p$
	- Update averages
- Finish and compute final averages

# General MCMC
- We have ProbDist (possibly high dimensionality). Want to sample from it or find expected value of it. Analytical solution is implausible.
- MCMC:
	- Perform "random walk" through probdist favoring values with higher probs.
	- Starting point -> pick random nearby point -> evaluate its probability. If it has higher prob than start: move there, otherwise stay (or move to that point with low prob)
	- Then we are visiting every point in the probdist propotional to how probable that point is.

## Markov chain
- Can be said in two ways:
	- The next state is only dependent on the current state
	- The current state is only dependent on the previous state
- Requirement:
	- The chain has to be ergodic:
		- It must visit every point in the domain, and will visit tem a proportionate amount to their probability.
		- To be ergodic, the chain must be:
			- Irreducible - for every state there is a positive probability of moving to any other state
			- Aperiodic - the chain must not get trapped in cycles


# Variational Monte Carlo
- Can include functions from different sub-files
- Must have some initial variables: Seed, number of: particles, steps, dimensions
- How to choose step size(for Harmonic Oscillator):
	- SE from the ??
	- $k(r) = u(r)/r$
	- $r(0) = const$, $r(\infty) = 0$
	- $u(0) = 0$, $u(\infty) = 0$
	- Harmonic Oscill: $-\frac{\hbar^2}{2m} \frac{d^2}{dr^2}u(r) + 1/2 m \omega^2r^2u(r) = E u(r)$
	- Scale equations, make them dimensionless (to atomic units)
		- $\rho = \gamma r$ , $[r] = length$, $[\gamma] = length^{-1}$
		- $r = \rho/\gamma$
		- $-\frac{\hbar^2\gamma^2}{2m} \frac{d^2}{d\rho^2}u + 1/2 m \omega^2\rho^2/\gamma^2 u = E u$
		- Can choose and tune $\gamma$ as we want to remove all the constants. Done by setting all constants = 1 and solving for gamma.
		- Here: $\gamma = \sqrt{\hbar/m\omega}$
		- 