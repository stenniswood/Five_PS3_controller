# Five_PS3_controller
"Drive Five" Demo software for Raspberry PI - control all five motors from PS3 controller.

PS3 Buttons are:
================
	Left POD Up/Down 	- Move motor V forward/reverse
	L1 + Left POD Up/down	- Move motor W forward/reverse
	
	Right POD Up/Down	- Move motor X forward/rev
	R1 + Right POD Up/Down	- Move motor Y forward/rev

	R2 + Right POD Up/Down	- Move motor Z forward/rev

The motors are run in open loop PWM mode only.


This repository has been built for Raspberry PI but should work on most any other linux system 
with only minor modifications.


BUILD:
======
	cd Five_PS3_controller/
	make clean
	make

RUN:
====
	./joys

