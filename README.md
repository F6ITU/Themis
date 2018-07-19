# Themis

A simple directional coupler (V1, deprecated) 

This coupler is based on a "tandem match" design with an input compensation capacitor.
 
It should be able to fit any kind of amplifier, from 10 to 100 W

The pcb itself  supports the 2 main toroids of the transformer, input and output coax connectors,
 a "raw" FWD output preceded by a 10 to 30 dB fixed attenuator, and
two FWD and REFL "internal" rails

These output are followed by a detector located on each branch of the coupler. The detected voltage 
is amplified by a dual rail to rail op amp. The output of the operational amplifier is then 
lowered by a resistive devider that keeps the highest voltage below the maximum voltage of the 
Angelia's ADC.
The main Molex kk connector is directly connected to J2 of Alexandrie control board

On the right side of the board, a relay, activated by the T/R signal (TX_RX_RLY), feed the 
receiver input with the RX signal comming from the filter (HPF out) when receiving, and the 
predistorsion signal (aka Pure Signal) from the coupler when transmitting

This relay is NOT needed anymore. The TX_RX_RLY switching is done on the TX_Coax_Out_RX board since V2.0

DO NOT USE THIS BRANCH unless you already have such a board. 
Themis V2 will change and replace this design. 


