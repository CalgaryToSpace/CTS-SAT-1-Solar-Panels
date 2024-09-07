# CTS-SAT-1-Solar-Panels
Solar panel PCB designs for the CTS-SAT-1 3U cubesat

## Overview
* 4x COTS 2U solar panels are the main power generation for the satellite.
* As a proof of concept, the following panels are manufactured from TrisolX cells.
    * 2x 1.25U panels
    * 1x 1.0U panel
* Each panel has backflow blocking diodes and shadow-protection diodes.

## 1.25U Solar Panel

* 30 cells, in a 3S10P configuration (3 cells in each string).

![1.25U Solar Panel - Top](docs/Trisolx%20Solar%20Panel%20-%201.25U%20Top%20Render.png)

![1.25U Solar Panel - Bottom](docs/Trisolx%20Solar%20Panel%20-%201.25U%20Bottom%20Render.png)

## Bill of Materials
* PMEG10020AELPX diode in a SOD128 package

## Specific Notes and Specs
* Coarse star tracker requires a place to epoxy to the panels with a 4.5mm x 10mm rectangle (silk screen box).
* TBC: 4-Layer Circuit Board: back side must be all GND so that it does not short out with the frame.

## Solar Panel Assembly Steps
0.  a) Work in the LFT with proper ESD protection. Wear gloves. Be careful with fragile cells.
    b) Solder on the diodes.

1. Clean solar panel with isopropyl alcohol.
2. Boil some water.
3. Put epoxy in hot water for 10 minutes.
4. Massage epoxy in pouch.
5. Get out the solar cells.
6. Apply some epoxy to solar panel pads.
7. Take a picture of the application for reference on future applications.
8. Use the suction thing to place solar cells on the panels.
9. Apply pressure by placing a PCB on top of the soldered panel, and placing a 300g mass on top.
10. Wait 24h for epoxy to dry.
11. Solder short wires to the nearby pads, ensuring the solder blobs do not stick out the back side.
12. Inspect the work.
13. The assembly is complete. 

## License
This project is licensed under the [CERN OHL v2 Permissive](https://choosealicense.com/licenses/cern-ohl-p-2.0/) license. We appreciate attribution and links back, but you are free to do what you wish with this project.
