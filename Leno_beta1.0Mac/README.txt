Leno Beta v1.0 Mac version 

Release Nov.3, 2015

by Mingda Oscar Li (ml888@cornell.edu)

1. Introduction
	LEGO is the open source electical device simulator.
	The current version Beta v1.0 is tailored for Thin-TFET exclusively, it include 
		1) Electrostatics: 1D Poisson for 3D and 2D semiconductor. 
		2) Tranport: 2D to 2D interlayer quantum tunneling current simulation.

	/*** For Mac Version ***/
	Because some linking problems, SuperLU is disable. So the speed is lower.
	Also, for the time being, all plotting functions are disabled.

2. How to use it
	*** This executable release is for Mac OS X only  ***
        1) Open terminal, go the same folder with Leno_beta1.0_mac
	2) Modify the device file and/or material file as you wish (normally you just need to change voltage ranges)
	3) Run ./Leno_beta1.0_mac -d yourDeviceFileName -m yourMaterialFileName (e.g. ./Leno_beta1.0_mac -d deviceNType -m material)
	4) ( Good ) ? Stay_cool : Email ml888@cornell.edu for help

4. Class Tree:
	MathFunct
		Params
			Material
				Device1D
					(Device2D)
			Poisson1D
				(Poisson2D)
			Transport
				Tunneling
			ExtractData
			InOut

5. Reference:
	"Single particle transport in two-dimensional heterojunction interlayer tunneling field effect transistor" http://dx.doi.org/10.1063/1.4866076
	"Two-Dimensional Heterojunction Interlayer Tunneling Field Effect Transistors (Thin-TFETs)" DOI:10.1109/JEDS.2015.23906

	

