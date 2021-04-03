---
title: Accelerated Rate Calorimetry
---
# Instrument Modes
- Heat-search mode: Initially, the heating elements in the adiabatic chamber heats the sample a little, stops, and let the sensors search for self-heatup. If the self-heatup is above a prespecified value, the cycle stops, and we go in to adiabatic mode.
- Adiabatic mode: The self-heatup is measured.
	- Events: Self-heatup initializing temp, Venting temp (for cells), accelerated heat output and uncontrolled heat output (thermal runway)
		- Separator meltdown: Endotherm reaction displayed by small lowering of heat generation.
- Usual specifics:
	- Instrument: EV+ARC from Thermal Hazard Technologies.
		- Videocamera, Window, two cable connections, pressure sensor, and gas release.
		- Chamber: 40cm diameter, 44cm depth. Sealed by Si-gasket and 40kg lid with magnet lock released at 1bar overpressure.
		- Program: ARC-ES v6.3.2
	- Heat rate: 
		- Heated to $60^\circ$C, thereafter $5^\circ$C steps in the searching phase. 
		- Wait time was 50 minutes, and search time is determined by software. 
		- With self-heat rate above$0.2^\circ$C/min, it eneters adiabatic mode.
		- Measured until $250^\circ$C or until heat rate is below $0.2^\circ$C/min

Source: M.Sc. degree of Torleif Lian (FFI)

# Sample holder
- Should be described in detail.
- Will absorb heat from the experiment: Lower temp rise than expected
- Heat lost by sample container can be explaied by the $\varphi$-factor:
	- $\varphi = 1 + \frac{m_b c_b}{m_s c_s}$
	- m = mass, c = heat cap, b = bomb, s = sample
	- Ideally: It should be close to that of a full lithium cell

# Analytics
- Lowered heat-rate may not be because of a break between two exotherms, but rather an endoterm. This can be indicated by pressure increase at the temperature where the endotherm is: Why would there be a pressure increase if there is no reaction?