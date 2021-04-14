Algo for performing Monte Carlo:
- Initialization: Fix the number of MC steps, Choose initial $R$ and variational parameters $\alpha$ and calculate $|\psi_T^\alpha (R)|^2$.
- Initialise the energy and the variance and start the MC calc.
	- Calc a trail pos $R_p = R + r \cdot step$ wehere $r$ is a random var $r \in [0,1].
	- Metropolis algo to accept or reject this move $w = P(R_p)/P(R)$
	- If the step is accepted, then we set $R = R_p$
	- Update averages
- Finish and compute final averages

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