# CTS-SAT-1-Solar-Panels
Solar panel PCB designs for the CTS-SAT-1 3U cubesat

## Overview
* Several difference designs for each face:
    * 1x 2U face, leaving room for deployable booms
    * 2x 3U faces, with holes for fine star tracker
    * 1x 3U face, with no additional holes
* 40mm x 80mm GaAs solar cells are to be epoxied to large pads on an FR4 PCB. This is the simplest possible design.
* Each panel has backflow blocking diodes and shadow-protection diodes.

## License
This project is licensed under the [CERN OHL v2 Permissive](https://choosealicense.com/licenses/cern-ohl-p-2.0/) license. We appreciate attribution and links back, but you are free to do what you wish with this project.

## Comments and Reasoning for Via and Trace widths design decisions. From Frank. B

* Using the PCB trace width calculator on https://www.digikey.ca/en/resources/conversion-calculators/conversion-calculator-pcb-trace-width, using a max current of 0.5 	A, a board thickness of 35 um, a rise temperature of 10 deg C, and an ambient temperature of 45 deg C, the minimum trace width is calculated to be 0.1154693321 	mm. Note that trace length is not necessary for this calculation to work. 
* Since we would like our traces and vias to handle more current than necessary, I have made most of the traces and vias 7x-10x times greater than the minimum trace 	length above, arbitrarily. 
* Already exceeded my minimum trace length in most cases, most traces have 1.9-2mm, while traces within a footprint such as the EPS connector are 1mm. Similarily, via 	holes are 0.75mm and it via diameters are 1.5mm, Choices for these decisions are mainly arbitrary to suit reasonable routing decisions and via placements that 	I have made within this PCB. For more info, contact Frank. B. 

* Associated Calculators used: https://www.digikey.ca/en/resources/conversion-calculators/conversion-calculator-pcb-trace-width
	Formula is also within link.



