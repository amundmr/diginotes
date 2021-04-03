# Li-ion safety
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



# ARC VS DSC
DSC: Differential scanning calorimetry.
- Two small containers, one with sample, one empty
- Heated in a chamber (5$^\circ$C/min), if edo or exothermic reactions happen in the sample, there will be a heat flux difference from the reference container.
- Bad:
	- Not suitable for large samples, like a battery
	- Simultaneous pressure measurements not possible
	- less sensitive then ARC
	- Gives higher onset temps.

ARC:
- bad:
	- affected by sample/container weight ratio, which can comprise sensitivity