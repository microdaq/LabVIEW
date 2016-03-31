MicroDAQ LabVIEW support package
...................

:Latest release: 1.0.0
:Maintainer: Embedded Solutions
:Description: MicroDAQ LabVIEW support package 

Description
============

This respository contains MicroDAQ LabVIEW support package. This package allows user to access MicroDAQ hardware via Ethernet or WIFI. This package supports LabVIEW 2009 and above. In order to install package use LabVIEW Package Manager. You can download LabVIEW Package Manager software from JKI website http://jki.net/vipm/download.


Key Features
============

* DIO, DSP, Encoder, PRU, PWM, Scilab VIs 

New Features
============
* Support for 64-bit platform
* High Speed Analog Input VIs
* Analog VIs - AO write, AI read VIs for AO and AI manipulation
* UART VIs - VIs for serial communication
* DIO func - VI allows to change DIO channels function to ENC1, ENC2, PWM1, PWM2, PWM3 or UART
* Encder read - direction output for rotation direction indication
* None option - selecting None option disables VI execution (data will not be send/recv to MicroDAQ)
* KEY get - VI read MicroDAQ F1, F2 function key state
* LED set - VI sets MicroDAQ LEDs
* PRU exec - now user can select build-in firmware to expand MicroDAQ functionality. Encder and RC controller are avaliable at the moment.

Improvments 
============
* VI descritpion - better Context Help
* DIO set/get/dir DIO number Enum type 
* DIO set/get uses boolean type for input/outpu state
* PRU VIs - PRU number and register as an Enum types
* PWM VIs - Enum types 

Known Issues
============

Support
=======

This package is support by Embedded Solutions. Issues and problems with software can be raported on: 

        info@embedded-solutions.pl

Required software (dependencies)
================================

* MicroDAQ firmware 1.3.0