# A-Simulink-Model-for-the-Induction-Machine-with-an-Inter-Turn-Short-Circuit-Fault

Open source simulation model for the induction machine with an inter-turn short circuit fault

In the provided simulink model, the user can enter the electrical parameters of the motor. Fault ratio and fault resistance parameters can also be specified for the simulation of ITSC.

For a comparison of healthy cases, standard Simulink model has also been provided. For the simulation of a healthy case, entering 'zero' value to the fault ratio yields computing problems. Use a sufficiently small (but non-zero) fault ratio and a sufficiently large fault resistance value, for the simulation of the provided model for the healthy operation of the induction motor. Recommended setting for the healthy case is: fault ratio = 0.005, fault resistance = 1000 ohm.
