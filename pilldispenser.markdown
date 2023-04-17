---
layout: default
title: "Pill Dispenser"
permalink: /pilldispenser
nav: true
---
## Problem:
It is inefficient to manually track the number of pills on the space station.
## Solution:
We designed and built a device that both dispenses and automaticlly tracks of the number of pills used.

### Design
This device combines an airsoft speed loader and original 3D printed parts to dispense pills one at a time. As they leave the holder, they trigger a break beam sensor connected to an Arduino Nano. This then sends a message to the inventory system and updates the quantity of pills accordingly. This can all be done completely wirelessly and without manual input.
![Pill Dispenser Image](/images/Pill%20Dispenser%20image.jpeg)
<br />A refill button makes it incredibly easy to automatically record refills of a standard size. Additionally whenever the number of pills decreases to a set amount, a red warning light turns on. The astronauts will have packages of a set amount of pills, so when the warning light comes on, they can take the standard refill size of pills and refill the dispenser. Non-standard refill sizes can of course be easily recorded manually in the database.

This pill dispenser is an original design that we 3D printed to hold the break beam sensors and an airsoft speed loader so that when the 
pill was dispensed

# 3D Printing
## The Problem:
There was no holder online that would hold the the beam break sensors held in place under the speed loader.
## The Solution:
Using a platform called Freecad, we designed from scratch a way to hold all the peices together.

We used a digital caliper to determine how to fit the beam break sensors snug without having to be fasened down.  It took us a few designs before it would work.
![First Dispenser Design](/images/first%20despenser%20design%20(small).png)
<br />This design was nice and compact but with the beam break sensors this close, the beam would reflect around the pill.  So we had to pull the sensors apart, and when we did, the beam was weak enough where when the pill passed by, it would detect that there was something in the way, and then send a message to the database.

This was our final design:
![CAD design](images/CAD%20drawing%20%231.png)
<br />This design worked the best out of all the designs, and the sensor detects the pill being dropped out of the dispenser 100% of the time.

Here is the link to download the stl fil to load directly into a 3D printer software: [Cad file for break beam sensor holder](/images/Break%20Beam%20holder%20%233.stl)
