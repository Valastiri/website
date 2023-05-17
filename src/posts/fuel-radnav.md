---
title: Major Updates to Fuel Simulation + RADNAV Functionality
date: 'tbd'
authors:
    - 'UhYouFoundZack'
    - 'Valastiri'
category: 'UPDATE'
metaImage: '/img/notam-images/flypados3/flypad-hero.png'
---

## Overview

As with every update, the FlyByWire team has been working long and hard to ensure we can bring you the very best high fidelity freeware product we possibly can. With that, we present to you the development team’s newest and finest work on the A32NX. Continue reading to learn more about improvements to the RADNAV Systems and improving the accuracy of the fuel system to match that of the real A320NEO. 

## New Radio Navigation (RAD NAV) features

With this update a few new additions have been made to the aircrafts ever expanding navigational toolbox. 

* FMS Navaid selection for Navigation and Display
* Tuned Navaids are now sent to the EFIS
* ILS Course and slope is now available for database navaids
* The “RADIO NAV” page has been re-implemented into the MCDU
* A “SELECTED NAVAIDS” page is now also present
* A “NAVAID” page is now also present
* SPECIF VOR/D UNVAIL message is also now present
* TUNE BBB FFF.FF, SPECIF NDB UNAVAIL message is also now present

## Fuel Architecture Overhaul

The FlyByWire team does the best we can to maintain the highest level of realism possible. With this, the fuel system in the A32NX has recently been overhauled. The A32NX currently uses the default Asobo A320NEO fuel architecture, which is incorrectly based off of the A320CEO. With the new custom A32NX fuel architecture, fuel will be transferred from the center tanks, to the inner tanks, before finally entering the engines instead of going directly into the engines from the center tanks. This function will take place so long as both the ‘Mode Sel’ switch, to which functionality was added with this update, and the center tank valve(s) (currently labeled pump(s)) are in the AUTO position (No white panel lights illuminated, as shown below). Furthermore, the inner tank fuel level must reach a level 500 kilograms less than the inner fuel tank capacity (i.e., the transfer starts for each inner tank when that tank fuel quantity is less than 5019 kilograms). The transfer will cease when the center tank is empty, or the inner tank that was being fed is full. The valves will also close five minutes after the center tank reaches its low fuel point of 130 kilograms of fuel.

*                                                                                                          Insert first image here                                                                                                                  *


When the ‘Mode Sel’ is switched to the MAN position, all center tank fuel transfer is controlled manually by the flight crew. Center tank transfer can be started to an inner tank by putting the respective center tank valve push button (currently labeled pump(s)) into the ON position.


*                                                                                                          Second image still needed                                                                                                                *

The ECAM fuel page has also been updated to show fuel quantity changes, and correct valve positioning. 

Please note, with this update support for the auto start/stop engine triggers (Ctrl+E by defualt) has been removed. Use of this feature in the past was discouraged, but possible whereas it is now completely removed.


