USB Isolator
============

This repository contains the KiCAD PCB project files for the USB Isolator project by Galvant Industries.

Pre-assembled boards will be available shortly at www.galvant.ca

About
-----

A USB isolator allows for a device to be connected to a PC while providing electrical isolation between the two.
This project uses an `Analog Devices ADuM4160 
<http://www.analog.com/en/interface-isolation/usb-isolators/adum4160/products/product.html>`_ full-speed USB digital
isolator chip to acheive this.

Features
--------

In comparison to other OSHW USB isolators out there, this project features a few improvements.

 - USB-B and micro-USB connectors on the host (upstream) side.
 - In addition to accepting power via the barrel connector (which goes through a basic 7805 linear regulator), there
   is also a micro-USB port for device-side power. This allows you to use the now common cell phone charger cube to
   power your isolated device.
 - Push-button switch for easy USB disconnection events.
 - Encased in a small box to protect the IC from the world.
 
License
-------

This work is released under the Creative Commons Attribution-Sharealike 3.0 license.
See http://creativecommons.org/licenses/by-sa/3.0/ or the included license/LICENSE.TXT file for more information.
