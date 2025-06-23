# Orbit_Determination_and_Propagation
Tool for orbit determination and propagation using right ascension and declination tracking station measurements.

This script evaluates the inputs using Gauss' method of preliminary orbit determination. State vectors are obtained before the orbit is propagated through time using an rk45 integration algorithm. The minimum distance between the orbital paths is then calculated. 

The state vector output has been validated against examples in Orbital Mechanics for Engineering Students (H. D. Curtis, 2021), and the plotted propagated orbit has been visually validated in GMAT. 
