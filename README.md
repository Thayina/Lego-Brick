# Lego-Brick
3D Printing a Lego Brick
## Overview

Designed and 3D printed a Lego brick as a team project. 
The goal was to create a relatively simple object while applying 
engineering, mathematical, CAD, and 3D-printing concepts.


## Objective

The main goals of this project were to:

- Create a lego brick using CAD
- Export design as sn STL file
- 3D print design
- Test physical print and troubleshoot any problems

## Tools and Softwares

- AutoCAD
- PrusaSlicer
- 3D printer

## CAD Design Process

Firstly, we sketched out the brick using a polyline and seven circles
Creating the Base

### Base

Created a 32 mm × 16 mm rectangle using a polyline and extruded it 
to a height of 4 mm.

### Top Studs

Used the Dynamic User Coordinate System (DUCS) to create three 
evenly spaced circles (10mm apart). Three additional circles were created on the bottom 
so that it can connect to another brick.

### Hollow Interior

Used the Press-Pull/Extrude and Shell commands to create the 
interior structure of the brick.

- Shell offset: 1 mm
- Inner circle offset: 0.5 mm
- Top circles extruded: 2 mm
- Bottom circles extruded: 3 mm


## 3D Printing Preparation

Sent partner the design for review and she exported as an STL file then imported the file into PrusaSlicer to prepare it for 3D Printing.

## Printing Troubleshooting

We first printed it upside-down and without supports, since supports are hard to remove on small prints. That attempted failed and we tried again rightside up. That attempt led to a similar result as the first. We then gave supports a try and changed "None" to "Everywhere" which gave a successful print.
We then printed out another to attch to the first.

## Design Challenges

We came to an issue when trying to connect our bricks. The dimensions for the top and bottom didn't work out because the offset of the bottom circles made it too tight for the top studs of the second brick to fit.

Instead of redesigning our bricks, we tested another brick using the same top dimensions and on the bottom, we deceide to create four circles  between the three top circles using the Tan-Tan-Radius command. This allowed the top of a brick that has three to fit between the bottom of the brick that has four.

## What I Learned

This project gave me experience with several CAD commands and showed me how mathematical relationships can affect the physical design. I also learned how to work with a deadline and allowing time for testing and troubleshooting.

## Final Result

![Final Bricks](Images/Final%20Bricks.png)

