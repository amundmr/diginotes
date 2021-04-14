# Quantum Mechanical - Prob dist func

- $P_T(\vec{k}; \vec{\alpha}) = \frac{|\psi_T (\vec{k}; \vec{\alpha})|^2}{\int d\vec{k}|\psi_T(\vec{k};\vec{\alpha})|^2}$
- $\vec{k}=\left\{\vec{c}_{1}, \vec{c}_{2}, \vec{c}_{3}, \ldots\vec{c}_{N}\right\}$
- 3 dimensions 100 particles is way too much
- Quantity $\Sigma_j W(j -> i) P_j^{(n)}$
	- W is a stochastic matric (unknown) represents all possible ways of moving to one state to another.
	- W with matrix elements $w_{ij}$
	- $\Sigma_{j=1} w_{ij} = 1$ (summing columns normalizes to one)
	- Example: k$^{3x3}$ , $W=\left[\begin{array}{ccc}\frac{1}{2} & 0 & 1 \\ 0 & 1 / 3 & 0 \\ 1 / 2 & 2 / 3 & 0\end{array}\right]$
	- $\lambda_{max} = 1$, if a Markov chain converges, it converges to the most likely state, that is the state with the largest eigenvalue $\lambda_{max} = 1$
	- Brute MC: Assume symmetry, transition matrix T is same from i->j and from j -> i.

Computational issue:
- $\frac{P_i}{P_j}$ =  $\frac{\left|\psi\left(\vec{k}_{i} ; \vec{\alpha}\right)\right|^{2}}{\left|\psi\left(\vec{k}_{j} ; \vec{\alpha}\right)\right|^{2}}$
- Many particles: $\vec{k}_{i}=\left\{\vec{c}_{1}^{(i)}, \vec{c}_{2}^{(i)}, \vec{c}_{3}^{(i)}, \ldots \vec{c}_{N}^{(i)}\right\}$
- Move of all particles pssible method:
	- $\psi_{T}\left(\vec{k}_{i}\right)=\varphi_{1}\left(c_{1}^{(i)}\right) \varphi_{2}\left(c_{2}^{(i)}\right) \ldots$

# Full metropolis algo(general case):

- $T(i \rightarrow j) \neq T(j \rightarrow i)$
- $\frac{P_{i}}{P_{j}}=\frac{T(j \rightarrow i) A\left(j \rightarrow i\right)}{T(i \rightarrow j) A(i\rightarrow j)}$
- We will develop a model for this (T-matrix ratio), no need for stepsize.
- Leads us to importance sampling:

## Importance sampling:
Methods:
- Fokker-planck eq.
- Langevin eq.
