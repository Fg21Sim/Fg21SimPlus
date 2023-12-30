Foreground Simulation Suite Plus for the 21 cm Reionization Signal Detection
=============================================================

The `Fg21Sim+` is a simulation suite in the radio domain aiming to offer a 
high-resolution, high-fidelity modelling of the various foregrounds for the 
21 cm signal detection. 

This is the next-gen version of our `fg21sim` low-frequency radio simulator.
We build the `Fg21Sim+` to generate a full sky simulation map for radio 
facilities like BINGO, MWA, and SKA. 

Initial Release
--------
The `Fg21Sim+` package is under its initial realise with the following individual models:
- [ESim](https://github.com/Fg21Sim/ESim) for extragalactic discrete emission
- [GSim](https://github.com/Fg21Sim/GSim) for Galactic diffuse emission
- [21cmSim](https://github.com/Fg21Sim/21cmSim) for the 21-cm signals

The model-defect simulation is an ongoing project @ `Fg21Sim team`, we are happy to 
release the 1st defect model:
- [BlendSim](https://github.com/Fg21Sim/BlendSim) for simulating blending of discrete sources

Dev Status
--------
The integration of individual models into a full suite is a 2nd phase development goal. If 
prefer the traditional usage with a config file. You can still use the last-gen 
[`fg21sim`](https://github.com/Fg21Sim/fg21sim).
