# Aircraft-6DOF-Simulation---Handling-Qualities

The program computes the 6DOF nonlinear dynamics model and integrates it with FlightGear to provide real-time visualization. The Research Civil Aircraft Model (RCAM) aerodynamic data is used as a test case to validate the output states (U,V,W,phi,theta,psi,P,Q,R,PN,PE,h) of the 6DOF program. The Simulink model utilizes the Model Linearizer function to determine steady-state conditions and linearize the dynamics model at the trim points. The program also determines flying qualities for longitudinal and lateral-directional motions, where the control inputs are ailerons, elevator, rudder, and throttle position of engines 1 and 2. 

Features
============
* Compute the states of the nonlinear 6DOF rigid body dynamics
* Provide real time visualization via FlightGear 
* Determine the equilibrium points of the dynamics model 
* Linearize the dynamics model at the desired trim points
* Decouple the state-space model into longitudinal and lateral motions
* Compute flying qualities for Phugoid, short-period,dutch-roll, spiral, and roll motions 

Installation
============
1. Extract the ZIP file (or clone the git repository) 
2. Run "AircraftSim.mlx" 
