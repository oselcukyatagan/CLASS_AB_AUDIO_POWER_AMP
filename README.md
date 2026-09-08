# CLASS_AB_AUDIO_POWER_AMP

This is the repository for the developing of the class AB audio power amplifier device. 

The repository contains the LTspice and KiCad files along with screenshots of the schematics and simulation results.


Used the technique of making a non polarized cap from 2 polarized electrolytic capacitors. to get the same capacitance, use 2 capacitors thats double the capacitance.

Vbe multiplier and the output stage transistors should be on the same heatsink for thermal considerations.

Ensured the isolated clean ground and dirty ground paths only intersect at a single point at the main power supply socket to prevent ground loops.

Adjust the vbe multiplier trimpot before initial power-on to prevent thermal runaway. calibrated quiescent current only after letting the amplifier idle to reach operating temperature.
