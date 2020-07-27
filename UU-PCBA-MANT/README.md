# `UU-PCBA-MANT-CON-AA` and `UU-PCBA-MANT-PAT-AA`

![UU-PCBA-MANT Antenna Revision AA](/UU-PCBA-MANT/images/UU-PCBA-MANT-AAA-AA.PNG)



Open-source design for a dual-band 2.5/3.6 GHz BRS/CBRS antenna with dual-polarized feeds for Massive MIMO.

The UU-PCBA-MANT is designed to connect to a Skylark Iris software-defined radio system and provide dual-band operation, providing two ports with 45-degree isolation. Project developed and packaged with Altium Designer 20.0.11.

The antenna is made in two parts to reduce production costs, using nylon rivets to mount the two individual parts together. The completed assembly is called `UU-TASM-MANT-BRS-AA`, while the PCB parts with the dual-band resonating patch is called `UU-PCBA-MANT-PAT-AA` and the PCB part with the RF connectors and feed is called `UU-PCBA-MANT-CON-AA`.

## Contents


The directory structure is as follows:
         
      altium/                  - Altium Designer 20.0.11 project and libraries

      production_files/        - Manufacturing package for producing the designed antenna
	  
	  images/                  - 3D Renders and photos of the finished design

## License

Project files copyright 2020 Skylark Wireless LLC, 4011 Garrot St., Houston, TX (COMPANY). All Rights Reserved.

This design was developed in collaboration with the University of Utah.

This work is licensed under the MIT Open-Source license. 

IN NO EVENT SHALL COMPANY BE LIABLE TO ANY PARTY FOR DIRECT, INDIRECT, SPECIAL, INCIDENTAL, OR CONSEQUENTIAL DAMAGES, INCLUDING LOST PROFITS, ARISING OUT OF THE USE OF THIS SOFTWARE, HARDWARE, AND ITS DOCUMENTATION, EVEN IF COMPANY HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

COMPANY SPECIFICALLY DISCLAIMS ANY WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE. THE SOFTWARE AND ACCOMPANYING DOCUMENTATION, IF ANY, PROVIDED HEREUNDER IS PROVIDED "AS IS". COMPANY HAS NO OBLIGATION TO PROVIDE MAINTENANCE, SUPPORT, UPDATES, ENHANCEMENTS, OR MODIFICATIONS.
