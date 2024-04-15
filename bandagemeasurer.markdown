---
layout: default
title: "Bandage Measurer"
permalink: /bandagemeasurer
nav: true
---
## Goal:
Measuring the length of bandage on a roll is difficult, so our goal is to design a device that tracks bandages as they are pulled from a roll.
## Design:
The roll of bandages is held on an axle with its output being fed through two sets of wheels. These wheels are compressed by springs to ensure that they are turned as the bandage is pulled.
## 3D Printing:
The entire structure of the device was designed in FreeCAD and 3D printed in multiple parts.
## Electronics:
To track the rotation of the wheels, we use a rotary encoder. We then send the rotation data to our main system using a wireless Bluetooth Low Energy connection from an Arduino RP-2040 microcontroller.

![small Bandage Dispenser Photo](https://github.com/censeoproject/censeoproject.github.io/assets/124106490/20d484ea-0e30-47da-8724-ba054b93b966)
