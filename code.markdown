---
layout: default
title: "Main System"
permalink: /main
nav: true
---
# Coding the Inventory System
## Basics:
Our main inventory system is primarily written in Python and consists of 660 lines of code in the main file alone. The entire system consists of well over 1000 lines of code. The data is stored in a JSON file where it can be accessed and updated with ease. The system is designed to support automatic data transmission, as is demonstrated in our pill dispenser prototype.
## System Capabilities:
*	Add or remove different medical supplies from the database.
*	Adjust the quantities of those supplies.
*	View all supplies at once.
*	Sort supplies by category or by the date they were added.
*	Keep record logs of all previous updates to the inventory.
*	Use user IDs to see who updated different supplies.
*	Get automatic updates from unique devices via wireless data transmission. 
## Stored Data:
* The name and ID number of each supply
* The quantity of each supply
* The category of each supply (pill, cream, etc.)
* The time at which the supply was first added to the inventory
* Multiple user IDs
* User reports after each change
