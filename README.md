# ClickForce
Force field visualization using D3.js

Simulation can be found at:
https://bl.ocks.org/Shaan-B/852f6b99be4acded0225ae58c7080ce1

This file creates a simulation of dots which can be affected by a repulsive force created by clicking and dragging.

Each dot exerts a repulsive force on each other dot, and all dots are attracted to a common gravitational force located in the center of the canvas. Dots are also restricted from moving outside of the canvas area.

Clicking produces a repulsive force at the position of the cursor. Dragging moves the center of the force field, and releasing the click removes the force.

The following parameters can be tweaked:
* numCircles - the number of dots in the simulation
* dropoffRadius - size of click force

This simulation is an example of many small objects following simple rules coming together to construct a greater whole, which can itself be considered a single entity (the network of dots).
