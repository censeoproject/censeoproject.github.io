---
layout: default
title: "Pill Dispenser"
permalink: /pilldispenser
nav: true
---
## Problem:
It is inneficient to manually track the number of pills on the space station.
## Solution:
We designed and built a device that both dispenses and automaticlly tracks of the number of pills used.

### Design
This device combines an airsoft speed loader and original 3D printed parts to dispense pills one at a time. As they leave the holder, they trigger a break beam sensor connected to an Arduino Nano. This then sends a message to the inventory system and updates the quantity of pills accordingly. This can all be done completely wirelessly and without manual input.
![Pill Dispenser Image](/images/Pill%20Dispenser%20image.jpeg)
A refill button makes it incredibly easy to automatically record refills of a standard size. Additionally whenever the number of pills decreases to a set amount, a red warning light turns on. The astronauts will have packages of a set amount of pills, so when the warning light comes on, they can take the standard refill size of pills and refill the dispenser. Non-standard refill sizes can of course be easily recorded manually in the database.

This pill dispenser is an original design that we 3D printed to hold the break beam sensors and an airsoft speed loader so that when the pill was dispensed
### The Problem:
There was no holder online that would hold the the beam break sensors held in place under the speed loader.
### The Solution:

![CAD design](images/CAD%20drawing%20%231.png)