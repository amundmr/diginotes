# Metropolis Algorithm
Simple Metropolis algo based on Markow chain theory
- Probability - $P_i(t)$
- Transition probabilty
	- $w(i\rightarrow j)$ (stochastic matrix or transition probability)
	- $\Sigma_j w_{ij} = 1$ Largest Eigenvalue $\lambda_{max} = 1$
	- Example (of stochastic matrix:): $w = [1/3 1 2/3][0 0 1/3][2/3 0 0]$
	- $\Sigma_i P_i(t) = 1$
- Markow Chain:
	- $P_i(t+\epsilon) = \Sigma_j w(j \rightarrow i) P_j(t)$
	- Know/Have a model:
		- $P_i(t + \epsilon) \rightarrow P_T(\vec{k}_j \alpha) = \frac{|\psi_T(\vec{k}_j \alpha)|^2}{\int d\vec{k} |\psi_T(\vec{k}_j \alpha)|^2}$
	- Metropolis test: we accept new move if $\omega \in [0,1]$, $\omega \leq \frac{P_T(\vec{k'};\vec{a})}{P_T(\vec{k};\vec{a})}$