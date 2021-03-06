.. raw:: html

    <style> .red {color:#f21717; font-weight:bold; font-size:16px} </style>

.. role:: red

.. raw:: html

    <style> .green {color:#009933; font-weight:bold; font-size:16px} </style>

.. role:: green

.. raw:: html

    <style> .blue {color:#1777f2; font-weight:bold; font-size:16px} </style>

.. role:: blue

.. raw:: html

    <style> .orange {color:#dc7633; font-weight:bold; font-size:16px} </style>

.. role:: orange

.. raw:: html

    <style> .pink {color:#cc00cc; font-weight:bold; font-size:16px} </style>

.. role:: pink

*********
Changelog
*********

V1.0
====

`V1.0 <https://github.com/Gondolindrim/AcheronLibrary/releases/tag/V1.0>`_ :sub:`(2019/04/15)`
----------------------------------------------------------------------------------------------

	- [:blue:`Feature`] **First version**. This version is the bare needed for a keyboard, including:

		- Keyboard MX switches, reversed (R), hotswap (H), and reversed hotswap (HR) versions;
		- Switch slots to make plates;
		- Adapted footprints for components like crystal, connector and more.

It is widely used in the SharkPCB (V2.0 and lower), ArcticPCB V1 and KeebsPCB V1.

V2.0
====

`V2.0 <https://github.com/Gondolindrim/AcheronLibrary/releases/tag/V2.0>`_ :sub:`(2019/06/20)`
----------------------------------------------------------------------------------------------

	- [:blue:`Feature`] **Optimization for manufacturing and assembly**. In this version, I decided that the objective of the AcheronLibrary is to build footprints aimed at optimizing manufacturing speed and cost. For this I adopted IEEE Standard 315 and changed some footprints and symbols to conform to it. This was done in two ways: talking to friends and contacts in the PCB manufacturing and assembly business, and feedback from my own projects by the assembly factories themselves. In order to do this, I added some footprints and modified other ones:
		
		- LQFP48, SOIC-8 and SOT-23-6 footprints now have more resources to tell which is the first pin. There are two ways: an arrow was added and the pad formad. All pads were made oval, but the pin 1 pad, which is square. This way it is easier for the assembler to know the orientation of the package;
		- SOD-123 has the diode arrow signaling which are anode and cathode pads. Also, the cathode pad was overlined;
		- R_1026 is an 1026 footprints that has the resistor symbol inside it to signal that it is a resistor;
		- Footprints for pin headers were added, ranging from straight and angled pin headers, with 4, 5 or 6 pins;
		- The ``halfSideHole`` footprint was added, which consists of those side holes using for mounting the PCB onto the case. This is not yet perfected because the hole is not plated, but it is usable;
		- Open-Source Hardware (OSH) logos added;
		- Acheron Logo added in compact and extended forms;
		- I added a footprint for the Blue Pill breakout board, which I'm developing PCBs for.

`V2.1 <https://github.com/Gondolindrim/AcheronLibrary/releases/tag/V2.0>`_ :sub:`(2019/06/21)`
----------------------------------------------------------------------------------------------

	- [:blue:`Feature`] **Further optimization**. Still going in the optimization of the last subversion, the footprint for the WS2812B LED was changed. All pads were made oval and pin 1 is square; also the chamfer was added to signal pin 3 (that's where the chamfer of that LED is) and the arrow is added to signal pin 1.

	- [:green:`Update`] **ALPS EC11E footprint was made better**. The ALPS EC11E rotary encoder footprint was made more robust; its pads were too thin, specially the two that hold the encoder into place. These were made thicker to better hold the component.
