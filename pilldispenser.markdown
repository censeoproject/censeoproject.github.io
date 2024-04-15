---
layout: default
title: "Pill Dispenser"
permalink: /pilldispenser
nav: true
---
## Problem:
It is inefficient to manually track the number of pills on the space station, and there is no way to tell if someone is taking more pills than they should.
## Solution:
We fully designed and built a device that both dispenses and automaticlly tracks of the number of pills used.

### Design
This device utilizes a gear with pill sized slots to dispense the pills.

![smallPill dispenser gear image](https://github.com/censeoproject/censeoproject.github.io/assets/124106490/3dea2cea-6dff-4cfe-8e78-ca5c759805cc)

As the astronaut turns the gear, the pills will be pushed out of the pill dispenser.  In order for it to work in low gravity, we are using a spring to push a 3d printed piece on top of the piils.  As the pills exit the device, they trigger a break beam sensor connected to an Arduino Nano which in turn sends a message to the inventory system and updates the quantity of pills accordingly. This can all be done completely wirelessly and without manual input into a database.  This device, like the others has a magnetic switch which keeps the device off while inside the box, and when taken out, turns on.  This is used to save power on the space station.  A refill button makes it incredibly easy to automatically record refills of a standard size. Additionally whenever the number of pills decreases to a set amount, a red warning light turns on allerting the user sto refill their pill device. The astronauts will have packages of a set amount of pills, so when the warning light comes on, they can take the standard refill size of pills and add them to the dispenser. Non-standard refill sizes can of course be easily recorded manually in the database.

![smallPill dispenser image](https://github.com/censeoproject/censeoproject.github.io/assets/124106490/8c18b5d2-5415-49b8-8aac-49198ed0174c)
