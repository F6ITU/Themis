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


