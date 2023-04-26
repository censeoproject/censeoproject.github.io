---
layout: default
title: "Measuring Creams"
permalink: /cream
nav: true
---
# Tracking Medical Creams
## Problem:
In a low-gravity environment, it is difficult to measure medical creams since they cannot be weighed.
## Solution:
We decided to calculate the volume of cream dispensed as a squeezer moves along the bottle.
# Measuring the Squeezer's Movement
To improve consistency and predictability, we use a squeezer to dispense the medical creams. To measure how far it has travelled along the tube, we use a color sensor that detects movement along a multi-colored strip of paper. The sensor is attached to the squeezer so that they move together. The colored strip is comprised of three distinct colors: red, green, and yellow. After careful testing, we determined that these colors were the easiest for the sensor to distinguish between. Because we designed the strip with three different colors as opposed to just two, we were able to program the color sensor to tell which direction it has moved. Thanks to this method, the device is able to store its furthest position along the tube and only update the system when it passes that point.
image: squeezer + sensor
# Calculating Volume
We created an equation that calculates the volume of toothpaste dispensed as the squeezer moves. To test the accuracy of this equation, we used a bottle of toothpaste. After plugging in the values for the size of the bottle, the equation calculated that a squeezer movement of 8 mm should dispense 5 mL of toothpaste. After repeated measurements at different points along the tube, we saw that the average volume dispensed after an 8 mm movement was roughly 4.8 mL with a standard deviation of 0.4 mL. While the test wasn't incredibly precise, the equation's estimated result was well within the uncertainty of the results.
![Measurement of Toothpaste](/images/Measurement%20of%20Toothpaste.jpeg)
