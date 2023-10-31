---
layout: default
title: "Main System"
permalink: /main
nav: true
---
# Coding the Inventory System

## Basics

Our main inventory system is written in python and uses a custom tkinter GUI. The inventory data is stored in a JSON file that can be accessed and updated with ease. The system is designed to support automatic data transmission, as is demonstrated in our pill dispenser prototype.

## System Capabilities

*	Medical supplies can be added or removed from the database.
*	The supplies' quantities, names, date added, etc. can be adjusted
* A list of all supplies is neatly presented.
*	Each user is provided with a user ID which is used for signing in and tracking who is updating the inventory system.
*	The system can receive automatic updates from peripheral devices using Bluetooth.

## Stored Data

* The name and ID number of each supply
* The quantity of each supply
* The category of each supply (pill, cream, etc.)
* The time and date at which the supply was first added to the inventory
* The time and date at which the supply was last edited
* User ID numbers
