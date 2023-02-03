---
layout: default
title: "Main System"
permalink: /main
nav: true
---
# Coding the Inventory System

## Basics

Our main inventory system is primarily written in Python and consists of 660 lines of code in the main file alone. The entire system consists of well over 1000 lines of code. The data is stored in a JSON file where it can be accessed and updated with ease. The system is designed to support automatic data transmission, as is demonstrated in our pill dispenser prototype.

## System Capabilities

*	Different medical supplies can be added or removed from the database
*	The supplies' quantities, names, dates, etc. can be adjusted
* A list of all supplies can be provided and sorted by either date or category
*	Previous updates to the inventory are stored in user reports
*	Each user is provided with a user ID which will be used to track which person made which update to the inventory system.
*	The system can receive automatic updates from unique devices using UDP data transfer

## Stored Data

* The name and ID number of each supply
* The quantity of each supply
* The category of each supply (pill, cream, etc.)
* The time at which the supply was first added to the inventory
* Multiple user IDs
* User reports after each change

## User Reports:
To keep a log of previous interactions with the database, we use a user report system. Each report contains the details of a change made to the inventory system. These include the user ID of who made the change, the time at which they made the change, which supply was updated, and what changed about that supply.
