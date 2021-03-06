*********************
Simulations and tests
*********************

============
Introduction
============

	In analog electronics, a big deal of efforts is made into making the design perfetcly adjusted --- given performance, costs and practical constraints.

	The vast majority of compliance testing and characteristics are associated with early simulations, done primarily through solving the set of differential and algebraic equations of the system in study.

	In this chapter the characteristics and performance simulations of the Ouroboros will be presented. All simulations were done with LTSpice XVII; the component library I used can be found at the official repository. The simulation files can be found in `the simulations folder <https://github.com/Gondolindrim/Ouroboros/tree/master/simulations>`_.

	Since the Ouroboros can function with a 5 to 20V simmetrical power source, the simulations were done with an array of values: 5V, 9V, 10V, 12V, 15V and 20V.

==============
Open Loop Gain
==============

.. figure:: ../images/ouroboros/openLoopGain.svg
	:width: 800 px

	Figure 1: Open Loop Gain bode plot of the circuit in figure 2.

.. figure:: ../images/ouroboros/openLoopTest.svg
	:width: 250 px

	Figure 2: schematic of the circuit used to simulate the amplifier in Open Loop.

==================================
Common Mode Rejection Ratio (CMRR)
==================================

.. figure:: ../images/ouroboros/cmrr.svg
	:width: 800 px

.. figure:: ../images/ouroboros/cmrrTest.svg
	:width: 400 px
