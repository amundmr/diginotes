# Scanning Tunneling Microscopy
![[STM.png]]
- 5-10Å is typical tip-to-sample distance

# Main components
- Atomically sharp tip (W, Au, PtIr)
- Scanner to raster the sample surface: Piezoelectric ceramics/motor (1mV-1kV step range of an fraction of Å to few $\mu$m)
- System to coarsley position your tip close to sample
- Vibration isolation from external vibrations(by several means)
- Feedback electronics (including computer system) to control tip-sample distance

# Functional principles
- Contrast: Change in DOS and topography
- Constant tunneling curent mote: x,y are varied, I and V is kept constant and z is measured(d) as a function of tip pos (assume constant DOS)

Contrast due to electron density: ![[STM_electron-dens.png]]
Contrast due to height change (topography): ![[STM_height.png]]

# Two operando modes
**Operando:** Probing the sample while doing chemical reactions(in-situ) while having another characterization technique to look at the chemical reaction in another way. IR, MS, gas chromatomagraphy(but this is slow)
1. Optimalized STM for high pressures (5-10 bar, but most only 1 bar, and up to 300$^\circ$C)
2. Optimalized for HT, up to 1000$^\circ$C but then in the milli-bar pressure range.

No method for high pressure and high temperature.

Difference of in-situ and operando. In-situ is without second measuring/probing/scanning technique.

# Gaps
- Pressure gap: possible pressure range of STM might deviate from the pressure you are using the material at
- Temperature gap: Possible temperature range of STM might deviate from the Temp you are using the material at
- Materials gap: Possible materials for use in STM

# Morie pattern
- when overlapping patterns (ex. two graphene sheets) overlap to create advanced pattern, which can show in STM

# Challenges with High Temp
- Picture drift because of thermal expansion/contraction (can be zeroed out, and is helped out by sping system)
- Piezoelectric motor cannot be used above its transition temp -> B must not become too hot, heat shielded by E.
![[STM_HT.png]]

You can **Grow graphene on Rh(111)** by having C-source (C$_2$H$_4$(g) - ethylene) which decomposes at high temp in the STM to 2C(s) + 2H$_2$(g)
The rightmost graph shows what substance is thermodynamically stable. Here, Graphene islands are most stable until dissolved carbon takes over.
![[STM-carbon-growth.png]]

**Fischer-Tropsch:** Actual chemical reactions is hard because the machine must withstand corrosive environments.
- Pressures above 1 bar: Create STM HP stage, only 0.5mL volume around tip and sample sealed off with O-ring.
Typical catalyst for this process is Cobalt, and helps create long hydrocarbons.

# substances in STM
TiO$_2$ at UHV, it is TiO$_{2-x}$, and this is actually a semiconductor unlike the insulating TiO$_2$, and since electron transport is needed for STM, this is possible.

Pt on Al$_2$O$_3$ substrate is hard because alumina is non conducting, It can be done by oxidizing NiAl-crystal (~10mbar pO$_2$) in the STM creating a 0.5nm layer of Alumina on top which can handle tunneling current. Nickel won't be oxidized because of reduction potential (consult ellingham diagrams). But is the properties of this thin alumina film the same as the catalysis scenario of Pt on Alumina? 
