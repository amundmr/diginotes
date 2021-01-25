# Contents:
- Charge
- Electrostatic force
- Electrical work
- Capacitance
- Current
- Conductance and resistance
- DC, AC voltage, current and impedance

# Electrical charge
- Physical property of matter 
- Equal charge repels
- Opposite charge attracts
- Quantized in elemental charge $e$.
- 1$e$ = $1.602\times10^{-19}$
- Symbol of charge: q, unit: C (Coulomb)
- Electron charge: -$e$, proton: $e$, Neutron: 0
- Force between charges: $F = \frac{k_e q_1 q_1}{r^2} = \frac{q_1 q_2}{4 \pi \epsilon_0 r^2}$
- $k_e$ = electrical constant, which for vacuum =$\frac{1}{4\pi \epsilon_0}$
- $\epsilon_0$ = dielectric constant (tabular value)
- Net charge seeks to external boundaries(surfaces, interfaces)
- Interior(bulk) phases remain electronneutral
- *Electroneutrality:* Sum of negative and positive charges balance (cancel) each other

## Electrical field
- $X = \frac{F}{Q_{test}}$
- Spherical field - inverse square law
- $F = \frac{q_1 q_2}{4 \pi \epsilon_0 r^2}$, $X = \frac{q_1}{4 \pi \epsilon_0 r^2}$
- Fields run from positive to negative (arrows of field towards negative) and shows in what direction a positive charge feels the force.
- **Planar field**
- Charge density of plates $q$(C/m$^2$)
- Force is independent of distance ($l$)
- Total field strength: $X = \frac{q}{\epsilon}$

## Electrical work
- Work is force times distance
- W = $F\times[-\delta R] = -QX\delta r$
- Travel $\delta r$ is there negative and the work we do is positive.
- **Electric Potential**
	- Difference in potential between two sites (constant field):
	- $U = \phi_B - \phi_A = \frac{W_{A->B}}{Q} = -X\delta r$
	- 1V = 1J/C (one unit work per unit charge)
	- Potential over variable field(Spherical symmetry):
	- ![[Pasted image 20210112132625.png]]
- *Poisson equation* explains how potential varies in space from a net charge.
	- Planar case: areal charge densities $q_0$ and $q_L$
	- $\frac{d^2\phi}{dx^2} = \frac{-\rho(x)}{\epsilon}$

## Conductance and capacitance
- Conductors: long range transport
- Dielectrics(capacitance) only short range transport
	- Insulators
- Conductors
	- Electronic conductords
		- Metals, semiconds(CB electrons, VB holes)
	- Ionic conductors
		- Anionic, cationic
		- Crystalline: Defects, vacancy, interstitial, intercalation??

- Capacitance:
- Stored charge $Q = \frac{-A\epsilon}{L}\Delta E
- Capacitance $C = \frac{-Q}{\Delta E} = \frac{\epsilon A}{L}
	- Unit: F = C/V
	- $\epsilon = \epsilon_r \epsilon_0$ Relative*vacuum permitivity.
- Current:
- I = Q/t, 1A = 1C/s
- Current density: i (A/m$^2$) = I/A (current devided by arial)

- Conductivity $\sigma$ or $\kappa$ (S/m)=i/X (Ohms Lov)
- Conductance G
- Resistitivity $\rho$(ohm m)
- Resistance R (ohm)

## Mobility
- Mechanical mobility B expresses how easy it is to move a species of drift velocity $v$ by a force F
	- $v = BF$
- Current density is obtained by multiplication with concentration and charge
	- $i = zecv = zecBF$ (z = # charges, e = elem charge)
- Charge mobility (or just mobility) is defined as $u = zeB$
	- i = zecBF = ucF
- In electrical field: F = zeX
	- i = ucF=zeucX
- *Conductivity is charge times charge mobility time concentration*: $\sigma = zeuc$
- $i = \sigma X$ (Ohms law)

# Exercises
A)

 Phenomena | Symbol | Unit 
 ---- | ---- | ---- 
 Charge | q | Coulomb 
 Force | F | Newton
 Potential | $\phi$ | Volt (Joules/Coulomb)
 Voltage | U | Volt (Joules/Coulomb)
 Current | I | Ampere (Coulombs/second)
 Capacitance | C | Farad (Coulombs/Volt)
 Resistance | R | $\Omega$ (Ohms)
 Resistivity | $\rho$ | $\Omega$ m (Ohm-meter)
 Conductance | G | Siemens
 Conductivity | $\sigma$ | 1/$\rho$


**B) Geometry. **
A tube with an electrolyte has inner diameter 2 cm and fully reversible electrodes covering the entire area, 10 cm apart. The electrolyte has a conductivity of 0.05 S/cm. What is its resistivity,conductance, and resistance? A voltage of 1.5 V is applied over the electrodes.What is the current and current density? If the charge carriers are singly charged (e.g. protons and chloride ions like in HCl(aq), what is the force they feel?)

*Answer:*
- Resistivity: 1/0.05 = 20$\Omega$ 
- Conductance: $G = \frac{\sigma \cdot A}{l} = \frac{0.05S/cm \cdot 2\pi 1^2 cm^2}{10cm} = 0.0314S$
- Resistance: $R = 1/G = 31.83 \Omega$
- Current: $U = RI, I = U/R = \frac{1.5V}{31.83 \Omega} \approx 41 mA$
- Current density: $J = I/A = \frac{41mA}{2\pi 1^2 cm^2} = 6.53 mA/cm^2$
- Force: Electric field E = U/d = 0.15V/cm(or N/C). F = Ee = $0.15N/C \cdot 1.60217662 \times 10^{-19} C = 0.024 attoNewton$
- 

**C. Electrostatic forces.**
i) Calculate the classical electrostatic force between a proton and an electron 1 Å away.ii) Calculate the electrostatic force between a K+ion and an O2\-ion 2.8Å away.iii) Calculate the electrostatic force between a H3O+ion and an OH\-ion 30Å awayin vacuum and in water.

*Answer:*
i) $F = \frac{k_e q_1 q_1}{r^2} = \frac{q_1 q_2}{4 \pi \epsilon_0 r^2} = \frac{1.6e-19*1.6e-19}{4*3.14*1*10^{-10}*10^{-10}}= 0.2038 aN$
ii) same, and iii same

**D. Field. **
i)What is the fieldstrength 1 nm away from an O2\-ion?
ii) We have two large plates 1 mm apart in vacuum. They have areal charge densities of 1 C/m2.What is the field strength between the plates?

*Answer:*
i) $X = \frac{q_1}{4 \pi \epsilon_0 r^2} = \frac{3.2e-19}{4*3.14*1*10e-9*10e-9} = 0.25mV/m$
ii) $X = q/ \epsilon$


**E. Capacitor.**
i) A capacitor has area 1 cm2 and a dielectric material of thickness 10 micrometer and a relative dielectric constant of 100. What is its capacitance?ii) A voltage of 10 V is applied over it. How much charge will that take (can that store)?iii) We discharge the capacitor over a loadwithout other losses.What is the energy dissipated?Is that the same energy as it took to charge it?If there were losses, what would be their causes?

**F. Conductivity**
i) A material has a conductivity of 0.01 S/cm.What is its resistivity?ii) A thin sample of the material 0.01 mm thick has an area of 10 cm2and is equipped with electrodes covering the whole area. What is the conductance and resistance of the component?iii) We apply a voltage of 1 V over the electrodes. What is the current? What is the current density?

**G. Mobility**
A solid electrolyte material has a concentration of mobile oxide ions (O2\-) of 1x1020/cm3and they have a charge mobility of 1x10\-4cm2/Vs.What is the ionic conductivity of the material?

**H. Electronic and ionic conductivity**
i) A material has an electronic conductivity of 0.001 S/cm and an ionic conductivity of 0.01 S/cm.What is the total conductivity?What is the ionic transport number?What is the electronic transport number?What is the total transport number?ii) If you consider that the material is also a dielectric (has a relative dielectric constant >1) discuss a possible circuit schematic for the material, and for the material connected to a voltage source, voltmeter, and amperemeter.