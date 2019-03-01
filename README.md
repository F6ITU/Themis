# Themis

A simple directional coupler

This coupler is based on a "tandem match" design with input compensation capacitor.
 
It should be able to fit any kind of amplifier, from 10 to 150 W

The pcb itself  supports the 2 main toroids of the transformer, input and output coax connectors 
and two coupled outputs.

These outputs are followed by a dual detector located on each branch of the coupler. The detected voltage 
is buffered by a dual rail to rail op amp. The output of the operational amplifier is then 
lowered by a resistive divider that keeps each output below the maximum input voltage of Angelia's ADC 

A optional "raw" FWD output is dedicated to the predistorsion -aka pure signal- feedback

3 different versions have been designed so far : V 1.0 was operational but the design and routing were absolutely ugly, with a crazy stripe-line trace.
V2.0 was a real enhancement of the general design (straight microstrip, simpler shielding). V2.1 offers now some small cleaning of the general design
(pure signal output located on the bottom layer, transformer junction also fixed on the bottom layer, thus enhancing the general insulation and 
offering a slightly better directivity. The attenuator of the P.S. output has a better access, thus simplifying the modification of it's value. 

V2.1 is the master branch since March 1st, 2019, and will stay "as is" as long as a new design is pushed. 


