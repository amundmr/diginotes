- Highest heat production and physical response is not correlated
- Safety assessment based purely on heat evolution and cathodechemistry can give false safeties.
- Safety is best assessed by a combination of mechanical stress, amount of electrical energy (energydensity, size and charge level) and chemical composition (How much heat can be generated)
- Measurements show that cathode and anode materials are most chemically unstable when the cell is at 100% SOC (p12)(
- Heatup initializing temperature usually occurs from SEI-reactions at the anode. (Usually between 75-124)$^\circ$C.
- Thermal runaway usually comes from cathodereactions and start between 140-240$^\circ$C.
- Thermal response to degradation mechanisms (NMC+LMO 1:1 tandem 18650 cell, Fleischhammer et al.):
	- Calendar aging: minimal change
	- High C-rate cycling: 8% lower heatup initialization temp
	- Low temp (-10$^\circ$C): 31/54$^\circ$C init temp in stead of 90/105$^\circ$C + more heat evolution in total.

![[Pasted image 20210125113149.png]]
Source: M.Sc. degree of Torleif Lian (FFI)

# ARC: Accelerated Rate Calorimetry
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
