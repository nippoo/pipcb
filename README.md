PipCB
========
This repository houses the electronics, firmware, and case design for the PipCB.

This board was designed with and to the specifications of Pip Coen and colleagues at the CortexLab (pipcoen@gmail.com). It comprises several different, independent sections, designed to replace a number of different individual components in use for experimental neuroscience rigs at the CortexLab. As such the design serves lots of different (somewhat unrelated) tasks and it is unlikely that another user will use all of its features!

The board as sold comprises:
- 24V, 220W power supply
- Photodiode (2-pin)
- Temperature sensor (3-pin)
- Enclosure
- PipCB v1, with the following features
	- Temperature-controlled PID Peltier cooler output with overheat protection
	- Two fixed 12V, 3A(max) 2A(continuous) power rails for auxiliary devices, one with switchable on/off output
	- Four variable 3-23V, 3A(max) 2A(continuous) power rails for auxiliary devices, all with switchable on/off outputs
	- One 1A ±12V, zero-centred power supply for Thorlabs photodiode
	- Photosensor with variable sensitivity trigger (5V TTL digital output)
	- Three DRV104 valve controllers, 12V output
	- Two logic inverters (5V TTL logic I/O)
	- One Arduino Nano V3, used to control Peltier output and random ‘flipper’ output, with 6 spare IO for future expansion
