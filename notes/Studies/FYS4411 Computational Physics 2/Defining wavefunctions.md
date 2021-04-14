How to define a trial wavefunction?

Single particle problem:
# Hydrogen atom
Scrhodinger Equation (SE):
$(\frac{\hbar^2}{2m} \nabla^2 - \frac{Zke^2}{r})\psi(\vec{r}) = E\psi(\vec{r})$
$\psi(\vec{r}) = k(r)P_{me}(\theta_g \phi)$
$x,y,z -> r, \theta, \phi | r \in [0, \infty), \theta \in[0, \pi], \phi \in [0, 2\pi]$

**Local energy:**
$\hbar = 1, m = 1, ke^2 = 1$
(atomic units)
$\frac{1}{k(r)} (- \frac{d^2}{dr^2} - \frac{2}{r}\frac{d}{dr} -\frac{Z}{r})k(r)$
First two terms inside parenthesis is kinetic energy, Z/r is potential energy

**What could go wrong:**
- The derivatives $\frac{d^m}{dr}k(r)$ are finite for all r (else it would converge)
- k(r) is finite for all r
- lim r -> 0: Massive problem because of division by r.
	- Must ensure $(-\frac{Z}{r}\frac{d}{dr}r - \frac{Z/r}k) = 0$
	- $-\frac{Z}{k(r)r} \frac{d}{dr}r = \frac{Z}{r} \frac{k}{k}$