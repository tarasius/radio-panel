# MICROSOFT FLIGHT SIMULATOR 2020 - RADIO PANEL
Forked from https://github.com/scott-vincent/radio-panel
Removed support of displays

# Quick Start

Link: [Latest release of Instrument Data Link for Windows](https://github.com/scott-vincent/instrument-data-link/releases/latest/download/instrument-data-link-v2.0.0-windows-x64.zip)

Unzip instrument-data-link into its own folder and double-click instrument-data-link.exe to run it.

Untar radio-panel on your Raspberry Pi. Edit settings/radio-panel.json and in the "Data Link" section change the IP address of the "Host" to the address where FS2020 is running on your local network, e.g. 192.168.0.1 - You can find the correct address of your host by running a command prompt on the host machine and running ipconfig, then scroll back and look for the first "IPv4 Address" line. Now enter ./run.sh to run the program.

# Introduction

A radio panel for MS FlightSim 2020. This program is designed to run
on a Raspberry Pi Zero W and requires the following hardware:

Push button with LED x 3 : https://www.amazon.co.uk/gp/product/B07KPSZ731 

Rotary encoder x 3 : https://www.amazon.co.uk/gp/product/B07FYHG2QZ  

It requires the companion program from here

  https://github.com/scott-vincent/instrument-data-link

The companion program runs on the same host as MS FS2020 and passes data between
the panel and the flight simulator over your Wifi connection.
