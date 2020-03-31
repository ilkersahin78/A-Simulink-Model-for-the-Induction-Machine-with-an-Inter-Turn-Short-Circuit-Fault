# A-Simulink-Model-for-the-Induction-Machine-with-an-Inter-Turn-Short-Circuit-Fault

Open source simulation model for the induction machine (IM) with an inter-turn short circuit (ITSC) fault, for the paper "A Simulink Model for the Induction Machine with an Inter-Turn Short Circuit Fault" to be presented in ICEM2020 https://icem2020.se/ .
 
In the provided simulink model, the user can enter the electrical parameters of the motor. Fault ratio and fault resistance parameters can also be specified for the simulation of ITSC. The preset model assumes an IM with an ITSC of 5% over a short-circuit resistance of 0.2 Ohm.

For a comparison of healthy cases, standard Simulink model is also included in the provided 'slx' file. For the simulation of a healthy case, entering 'zero' value to the fault ratio yields computing problems. Use a sufficiently small (but non-zero) fault ratio and a sufficiently large fault resistance value, for the simulation of the provided model for the healthy operation of the induction motor. Recommended setting for the healthy case is: fault ratio = 0.005, fault resistance = 1000 ohm.
