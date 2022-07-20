# Ohm's Law & Derivations
- State Ohm's law
	- The current through a conductor is proportional to the potential difference across it, given a constant temperature
- IV characteristics 
- Cases
	- metallic conductor
		- Draw IV graph
			- ![[Untitled-2.png|250]]
		- Account for the shape of the graph 
		- A metallic conductor is ohmic; the current is directly proportional to the potential difference. 
	- filament lamp 
		- draw IV graph
			- ![[filament iv.png|250]]
		- Account for the shape of the graph
			- non-ohmic at high voltages but ohmic at small potential differences. 
			- Increased voltage causes increased rate of flow of electrons through the lamp. At higher speeds there are more collisions with atoms in the conductor. These collisions result in energy loss in the form of heat. 
	- semiconductor diode/Light-Emitting-Diode (LED)
		- Definition
			- a solid substance or material whose electrical conductivity is intermediate between that of conductors and insulators 
		- Draw IV graph
			- ![[semiconductor 3.png|500]]
			- What is the region D? 
				- Reverse Bias - Current does not flow 
			- What is the region B?
				- Forward bias - current flows 
			- Which term refers to the voltage value, E?
				- Knee voltage - Around 0.7 V where current starts to flow 
			- Account for the steep rise in the graph beyond C?
				- The voltage barrier is overcome so current starts to flow 
			- What happens to the diode at A?
				- The depletion region (charge barrier) is removed and a high reverse avalanche current flows, permanently damaging the diode. 
			- Account for the occurrence of the red region
				- In  a semiconductor, a charge barrier is formed between the p-type and n-type material as electrons flow from the n-type to the p-type material 
# Kirchhoff's Laws 

- Kirchhoff's laws are helpful for doing calculations for series-parallel circuits. 
- First law
	- **sum** of the currents entering a junction = **sum** of currents leaving the junction
	- This law must be true since
		- The total amount of electric charge in a system does not change with time. (Law of conservation of charge) 
- Second law
- Use Kirchhoff's laws to derive an equation for 
	- Resistance in parallel
		- ![[paste-397236ac79a75288590112b1733b71b0cbd10e3c.jpg]]
		- Resistance in series 
		
			- Annotated working
			- Factors to consider
				1. $V_{t}  = V_{1}  + V_{2}$  
				2. Current is constant 
				3. Ohmic devices, V= IR
			- Working
				$I_{t}R_{t}  = I_{1}R_{1} + I_{2}R_{2}$
				
				Since current is constant,
				
				$IR = IR_{1} + IR_{2}$
				
				$R_{t}= R_{1}+R_{2}$
	- Resistance in series 

