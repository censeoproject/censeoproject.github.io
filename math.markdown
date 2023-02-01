---
layout: default
title: "Math"
permalink: /math
nav: true
---
# Calculating Medical Cream
## Problem:
Measuring quantities of cream in a low-gravity environment can be quite difficult. Obviously, you could keep track of them by the bottle, but what if you wanted a more precise measurement?
## Solution:
Calculate the volume of cream dispensed as a squeezer moves along the bottle.
# The Math Behind This
## Deriving a Formula for the Geometric Solid
The first step is to represent a tube of medical cream as a three-dimensional geometric solid. At one end, the bottle is a circle. At the other end, it is a flat line. This lead us to discover that a bottle of cream is essentially an ellipse whose height and width shift over the z-axis. The equation for an ellipse is shown below. The width and height of this ellipse are ra and rb, respectively:
REPLACE WITH IMAGE: ELLIPSE
*To make things easier going forward, the constants W, R, and L will represent the width of the flat end, the radius of the round end, and the length of the tube, respectively.*
\nIf r is set to 1, then width and height are simply a and b. Using this, we can then swap out a and b with linear equations that represent the change in height or width as the position along the z-axis changes. This equation represents the geometric solid of a tube of medical cream:
REPLACE WITH IMAGE: TUBE EQUATION
Here is the graph of this equation after it has been solved for z, and arbitrary values have been entered for W, R, and L. As you can see, it clearly resembles a tube of toothpaste:
REPLACE WITH IMAGE: GRAPH
## Calculating the Volume of the Solid
To get the volume of the solid, we use a triple integral. After setting the integrand to 1 and the limits of integration to the appropriate equations/values, we are left with the following equation:
REPLACE WITH IMAGE: TRIPLE INTEGRAL
## Implementation
To use this equation to calculate the volume of medical cream dispensed, we will first calculate the volume of the full bottle. We will then update the equation to account for a shortened length as the squeezer moves along the bottle. This second calculation will return the volume of cream remaining (at least in that bottle), and the difference in the two calculations will return the volume of cream dispensed.
## Testing the Equation
To test the accuracy of the volume equation, we used a bottle of toothpaste. After plugging in the values for the size of the bottle, the equation calculated that a squeezer movement of 8 mm should dispense 5 mL of toothpaste. After repeated measurements at different points along the tube, we saw that the average volume dispensed after an 8 mm movement was roughly 4.8 mL with a standard deviation of 0.4 mL. While the test wasn't incredibly precise, the equation's estimated result was well within the uncertainty of the results.
REPLACE WITH IMAGE: MEASUREMENT
