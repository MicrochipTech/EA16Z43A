# SAMA7G54 System-On-Modules Series
## Early Access Repository
The Microchip SAMA7G54 System-On-Module Series is a small double-sided SOM series based on a System-in-Package (SiP) Arm® Cortex®-A7 CPU-based embedded microprocessor running up to 1 GHz.
The SAMA7G54 SOM Series is built on a common set of proven Microchip components to reduce time to market by simplifying hardware design and software development.
The SOM embeds a SAMA7G5 Series SiP microprocessor with up to 2-Gbit DDR3L SDRAM, up to 4-Gbit NAND Flash memory, a 64-Mbit serial Quad I/O Flash memory and a dedicated Power Management Unit.
The SAMA7G54 SOM Series also limits design rules of the main application board, reducing overall PCB complexity and cost. The SAMA7G54 SOM Series is supported by a free Linux® distribution and bare metal C examples. 

For more information about the SAMA7G54 MPU, or the associated SIPs referenced above, please visit the respective product page on Microchip.com:
* SoC
  * [SAMA7G54](https://www.microchip.com/en-us/product/SAMA7G54): Released to Production (RTP)
* SiP
  * [SAMA7G54D1G](https://www.microchip.com/en-us/product/SAMA7G54D1G): Released to Production (RTP)
  * [SAMA7G54D2G](https://www.microchip.com/en-us/product/SAMA7G54D2G): Released to Production (RTP)
  * [SAMA7G54D4G](https://www.microchip.com/en-us/product/SAMA7G54D4G): Released to Production (RTP)
* SOM
  * SAMA7G54D1GN0 1Gb DDR3L / No Nand: Early Adopter (EA)
  * SAMA7G54D1GN2 1Gb DDR3L / 2Gb Nand: Early Adopter (EA)
  * SAMA7G54D2GN4 2Gb DDR3L / 4Gb Nand: Early Adopter (EA)
  * SAMA7G54D4GN8 4Gb DDR3L / 8Gb Nand: Coming Soon
 
<p align="center"><img src="SAMA7G54-SOM.jpg" /></p>

## EA16Z43A - SAMA7G54 SOM EA Bundle
The EA16Z43A is a bundle of 3 pre-production Microchip SAMA7G54 System-On-Module products.  
These are small double-sided MPU SOMs based on a System-In-Package (SIP) Arm® Cortex®-A7 CPU-based embedded microprocessor with 2-Gbit DDR3L SDRAM integrated running up to 1 GHz.

Order in Microchip Direct: https://www.microchipdirect.com/dev-tools/EA16Z43A 

## Assembly Limitations
It is not recommended to use industrial automated reflow process with oven to solder the product on the mother board, as the process might impact the System-On-Module reliability.

Work Around: Solder the System-On-Module on the mother board manually.

## Collaterals
* Hardware
  * [SAMA7G54 SOM Hardware Design Files](Hardware/)
* Documentation
  * [SAMA7G54 SOM Series Preliminary Data Sheet](Documentation/)
  * [System-On-Module (SOM) Assembly and Storage Guidelines](https://ww1.microchip.com/downloads/aemDocuments/documents/MPU32/ApplicationNotes/ApplicationNotes/System-On-Module-SOM-Assembly-and-Storage-Guidelines-DS00005249.pdf)
  * [System-On-Module (SOM) Pick and Place Guidelines](https://ww1.microchip.com/downloads/aemDocuments/documents/MPU32/ApplicationNotes/ApplicationNotes/System-On-Module-SOM-Pick-and-Place-Guidelines-DS00004878.pdf)
* Tools
  * [SAM-BA Programming Tool](https://github.com/atmelcorp/sam-ba/releases/tag/v3.9)
