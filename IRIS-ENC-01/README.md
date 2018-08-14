# IRIS-ENC-01

![IRIS-ENC-01 Enclosure Rev 4](/IRIS-ENC-01/images/IRIS-ENC-01-TOP.PNG)


Top cover of plastic enclosure designed for [Skylark Wireless](http://www.skylarkwireless.com) IRIS Software Defined Radio (SDR) platforms that supports 2x2 TDD or FDD MIMO operation between 50 - 3800 MHz.
The Iris-FE-01-DEV provides a starting point for developing custom RF front-ends and provides no filtering or amplification.

![IRIS-ENC-01-BOT Enclosure Rev 4](/IRIS-ENC-01/images/IRIS-ENC-01-BOT.PNG)

Bottom cover of plastic enclosure designed for [Skylark Wireless](http://www.skylarkwireless.com) IRIS Software Defined Radio (SDR) platforms that supports 2x2 TDD or FDD MIMO operation between 50 - 3800 MHz.
The Iris-FE-01-DEV provides a starting point for developing custom RF front-ends and provides no filtering or amplification.

![IRIS-ENC-01-MID Enclosure Rev 4](/IRIS-ENC-01/images/IRIS-ENC-01-MID.PNG)

IRIS-FE-01-DEV insert for plastic enclosure designed for [Skylark Wireless](http://www.skylarkwireless.com) IRIS Software Defined Radio (SDR) platforms that supports 2x2 TDD or FDD MIMO operation between 50 - 3800 MHz.
The Iris-FE-01-DEV provides a starting point for developing custom RF front-ends and provides no filtering or amplification.

![IRIS-ENC-01-SEP Enclosure Rev 4](/IRIS-ENC-01/images/IRIS-ENC-01-SEP.PNG)

Separator to help with removing front ends from IRIS board, use caution when disassembling to not bend pins or break parts.


## Contents


The directory structure is as follows:
         
      stl/                      - stl files for printing or manufacturing
	  
      step/                     - 3d step files for printing or manufacturing
	  
	  images/                   - 3D Renders and photos of the finished design

## Use
	This enclosure design is to protect the IRIS-030 and IRIS-FE-01-DEV from minor accidental damage and shorting of components. It is provided in both step and stl format to allow for printing or manufacturing. 
	It has been tested on a CR10s and MakerBot Replicator 2.
	Settings can be fairly low on either printer, 0.2mm with 25% infill works well as long as enough shell layers are used.
	For post processing, it is recommended to use a 3/32 bit to bore out the friction fit posts holes and a 7/16 bit to drill out the alignment hole.
	Friction pins are 3/32 in size and available from McMaster-Carr part number 98381A436. 6 are used per enclosure. two in the top cover and 4 in the bottom cover. They should by glued in place.
	The LED shrouds can have 1/8" acrylic rod cut and inserted to act as light pipes. It is recommended that they be glued in place. These rods are available from McMaster-Carr part number 8531K11.
	The fan should be a 3 pin 30x30x10mm fan mounted with No 6 thread forming screws McMaster-Carr part number 96068A153. 
	A small low clearance heatsink should be installed on the Xilinx Zynq Chip.
	
## License

Copyright ©2016. Skylark Wireless LLC, 1953 Richmond Ave, Houston, TX 77098 (COMPANY). All Rights Reserved.

This work is licensed under the Creative Commons Attribution-ShareAlike 4.0 International License. To view a copy of this license, visit http://creativecommons.org/licenses/by-sa/4.0/ or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.

IN NO EVENT SHALL COMPANY BE LIABLE TO ANY PARTY FOR DIRECT, INDIRECT, SPECIAL, INCIDENTAL, OR CONSEQUENTIAL DAMAGES, INCLUDING LOST PROFITS, ARISING OUT OF THE USE OF THIS SOFTWARE, HARDWARE, AND ITS DOCUMENTATION, EVEN IF COMPANY HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

COMPANY SPECIFICALLY DISCLAIMS ANY WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE. THE SOFTWARE AND ACCOMPANYING DOCUMENTATION, IF ANY, PROVIDED HEREUNDER IS PROVIDED "AS IS". COMPANY HAS NO OBLIGATION TO PROVIDE MAINTENANCE, SUPPORT, UPDATES, ENHANCEMENTS, OR MODIFICATIONS.

[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
