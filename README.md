# photodetectors	<br>
MUTC Photodetector Dataset	<br>
This dataset lists four performance metrics of 1755 MUTC photodetectors with 17 layers. 	<br>
The semiconductor types of these layers are fixed and they can be found in https://doi.org/10.1364/OE.27.003717	<br>

**Columns** 	<br>
phasenoise : true phasenoise of the photodetector (Unit: dBc/Hz)	<br>
phasenoise_15mA	: hypothetical phasenoise of the photodetector if the output current was equal to 15 mA (Unit: dBc/Hz)		<br>
current	: average current of the photodetector (Unit: mA)	<br>
IR_max	: maximum value of the impulse response of the photodetector 	<br>
decay_time: the time it takes for the impulse response to decay from its maximum value to 1% of that maximum value (Unit: ns) 	<br>
t1 ... t17 : thickness each layer (Unit: nm) 	<br>
d1 ... d17 : doping concentration of each layer (Unit: cm^-3) 	<br>

**Forward Problem:**	<br> 
Predicting Performance Metric From Design Parameters 	<br>
The four machine learning algorithms, linear regression, k-nearest neighbor, random forest, and an artificial neural network, are used to predict performance metrics (phasenoise, current, IR_Max, and decay_time) from the design parameters (thicknesses and doping concentrations)
