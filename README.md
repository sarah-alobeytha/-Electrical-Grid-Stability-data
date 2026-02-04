The Electrical Grid Stability Simulated Data dataset contains 10,000 simulated observations characterising a small?scale 4-node star power-grid system (one producer node in the centre, three consumer nodes) under a decentralized smart?grid control scheme. For each observation several input features describe reaction times of participants, nominal power produced or consumed, and price-elasticity coefficients. The output variables capture the system stability: one numeric indicator of the real part of the characteristic equation root, and one categorical label (“stable”/“unstable”).


tau1	Reaction time (in seconds) of participant 1 (the electricity producer node) in the network.
tau2	Reaction time of participant 2 (one of the consumer nodes); same unit/range as above.
tau3	Reaction time of participant 3 (a consumer node).
tau4	Reaction time of participant 4 (a consumer node).
p1	Nominal power for participant 1 (the producer node). Positive value (produced power). Negative value indicates consumption.
p2	Nominal power for participant 2 (consumer node). Positive value (produced power). Negative value indicates consumption.
p3	Nominal power for participant 3 (consumer node). Positive value (produced power). Negative value indicates consumption.
p4	Nominal power for participant 4 (consumer node). Positive value (produced power). Negative value indicates consumption.
g1	Coefficient of price-elasticity for participant 1 (producer node).
g2	Price-elasticity coefficient for participant 2 (consumer node).
g3	Price-elasticity coefficient for participant 3 (consumer node).
g4	Price-elasticity coefficient for participant 4 (consumer node).
stab	The maximum real part of the characteristic equation’s root for the simulated system. A positive value indicates the system is linearly unstable, a negative value indicates stable. 
stabf	stable / unstable based on stab value
