## Members
Eddie Pritchard, Camille Lyles
epritchard@vt.edu, camillevl@vt.edu

## Mentor
Eddie Pritchard

## Current Status
IN PROGRESS

## Project Overview

Arduino based moisture sensor planted in soil of plant pot. Arduino controls water delivery valve according to watering profile. Arduino also reads lighting sensor while controlling a relay which gates the state of a grow light. Various lighting and watering profiles will be experimented with across several different plant species. Down the line, humidity sensing and control of a fan may be added.

## Educational Value Added

This will provide a experimentation platform to grow knowledge of electronic control systems of a 24v DC solenoid and accompanying control circuitry. Will also be a challenging computer engineering problem in order to synchronize the states of the water/light/humidity control loops with the profiles of several different plant species. Additionally, experimentation with different types of plants will contribute to the knowledge base of botany. 

## Tasks

Already completed the solenoid valve control circuitry for delivering water. Now need to integrate this circuit onto a PCB which includes a battery or several 9v batteries. Desired battery voltage sensor could be added to alarm when battery is dropping as the 9v batteries have proven to discharge quickly when opening the water solenoid valve.

Moisture sensor and light sensors need to be added to the arduino/(pi).

Relay for grow light needs to be added. This system might need to be a COTS 120v AC switch or a motor controlling a physical switch in line on the power cord of a grow light if a 120v relay is too dangerous. 



## BOM + Component Cost

Solenoid already owned.
Arduino already owned.
Grow light bar already owned.
~50$ needed for PCB for solenoid valve control board.
Photosensor already owned.

Need to buy or build a moisture meter.

## Timeline

PCB designed by 2/4/24.

