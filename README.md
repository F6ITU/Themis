# Themis

A simple directional coupler (V1, deprecated) 

This coupler is based on a "tandem match" design with an input compensation capacitor.
 
It should be able to fit any kind of amplifier, from 10 to 100 W

The pcb itself  supports the 2 main toroids of the transformer, input and output coax connectors 
and the two coupled outputs.

These output are followed by a detector located on each branch of the coupler. The detected voltage 
is amplified by a dual rail to rail op amp. The output of the operational amplifier is then 
lowered by a resistive devider that keeps the highest voltage below the maximum voltage of the 
Angelia's ADC 

On the right side of tne board, a relay, activated by the T/R signal (TX_RX_RLY), feed the 
receiver input with the RX signal comming from the filter (HPF out) when receiving, and the 
predistorsion signal (aka Pure Signal) from the coupler when transmitting

DO NOT USE THIS BRANCH 
the design is probably flawed (bad RL, bad directivity, too hard to set and adapt). Files are left on this repository for documentation purposes


