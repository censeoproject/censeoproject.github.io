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
This device combines an airsoft speed loader and original 3D printed parts to dispense pills one at a time. As they leave the holder, they trigger a break beam sensor connected to an Arduino Nano. This then sends a message to the inventory system and updates the quantity of pills accordingly. This message can be sent completely wirelessly and without manual input.
![Pill Dispenser Image](/images/Pill%20Dispenser%20image.jpeg)
<br />A refill button makes it incredibly easy to automatically record refills of a standard size. Additionally, when the number of pills decreases to a set amount, a red warning light turns on. In theory, the astronauts will have packages of a set amount of pills to refill the dispenser with ease. Non-standard refill sizes can of course be recorded manually in the database.
### 3D Printing
To attach the break beam sensors to the rest of the mechanism, we 3D printed a custom-designed piece.

![CAD design](images/CAD%20drawing%20%231.png)
