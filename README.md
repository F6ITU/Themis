# Themis

A simple directional coupler

This coupler is based on a "tandem match" design with an input compensation capacitor.
 
It should be able to fit any kind of amplifier, from 10 to 50 W

The pcb itself  supports the 2 main toroids of the transformer, input and output coax connectors 
and two coupled outputs.

These output are followed by a detector located on each branch of the coupler. The detected voltage 
is amplified by a dual rail to rail op amp. The output of the operational amplifier is then 
lowered by a resistive devider that keeps the highest voltage below the maximum voltage of the 
Angelia's ADC 

A seconde "raw" FWD output is dedicated to the predistorsion -aka pure signal- feedback

3 different versions have been designed so far : V1 was operational but the design and routing were absolutely ugly, with a crazy stripe-line trace.
V2.0 was a real enhancement of the general design (straight microstrip, simpler shielding). V2.1 offers some small cleaning of the general design
(pure signal output located on the bottom layer, transformer junction also fixed on the bottom layer, thus enhancing the general insulation and 
offering a slightly better directivity. The attenuator of the P.S. output has a better access, thus simplifying the modification of it's value. 

V2.1 is the master branch till March 1st, 2019, and will stay like this as long as new design is pushed. 


