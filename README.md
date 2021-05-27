# photodetectors
MUTC Photodetector Dataset
This dataset lists four performance metrics of MUTC photodetectors with 17 layers. 

* Columns: *
phasenoise : true phasenoise of the photodetector (Unit: dBc/Hz)	
phasenoise_15mA	: hypothetical phasenoise of the photodetector if the output current was equal to 15 mA (Unit: dBc/Hz)	
current	: average current of the photodetector (Unit: mA)
IR_max	: maximum value of the impulse response of the photodetector
decay_time: the time it takes for the impulse response to decay from its maximum value to 1% of that maximum value (Unit: ns)
t1 ... t17 : thickness each layer (Unit: nm)
d1 ... d17 : doping concentration of each layer (Unit: cm^-3)
