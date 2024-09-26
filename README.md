# EA16Z43A - SAMA7G54 SOM EA Bundle
Early Access repository for the SAMA7G54 System-On-Module products

The EA16Z43A is a bundle of 3 pre-production Microchip SAMA7G54 System-On-Module products.  
These are small single-sided MPU SOMs based on a System-In-Package (SIP) Arm® Cortex®-A7 CPU-based embedded microprocessor with 2-Gbit DDR3L SDRAM integrated running up to 1 GHz.

The SAMA7G54 SOM family is built on a common set of proven Microchip components to reduce time to market by simplifying hardware design and software development.  
In addition to the 2-Gbit DDR3L SAMA7G54 MPU SIP, the SOM embeds a 4-Gbit NAND Flash memory, a 64-Mbit serial Quad I/O Flash memory and a dedicated Power Management Unit.
The SAMA7G54 SOM limits design rules of the main application board, reducing overall PCB complexity and cost. 
The SAMA7G54 SOM family is supported by a free Linux® distribution and bare metal C examples. 

Order in Microchip Direct: https://www.microchipdirect.com/dev-tools/EA16Z43A 

## Assembly Limitations
It is not recommended to use industrial automated reflow process with oven to solder the product on the mother board, as the process might impact the System-On-Module reliability.

Work Around: Solder the System-On-Module on the mother board manually.

## Collaterals
* Hardware
  * SOM Hardware Design Files are available upon request through a licence agreement. Please contact your local [Microchip Sales or Sales representative](https://www.microchip.com/en-us/about/global-sales-and-distribution) for more information
* Documentation
  * [SAMA7G54 SOM Series Preliminary Data Sheet](Documentation/)
  * [System-On-Module (SOM) Assembly and Storage Guidelines](https://ww1.microchip.com/downloads/aemDocuments/documents/MPU32/ApplicationNotes/ApplicationNotes/System-On-Module-SOM-Assembly-and-Storage-Guidelines-DS00005249.pdf)
  * [System-On-Module (SOM) Pick and Place Guidelines](https://ww1.microchip.com/downloads/aemDocuments/documents/MPU32/ApplicationNotes/ApplicationNotes/System-On-Module-%28SOM%29-Pick-and-Place-Guidelines-ds00004878.pdf)
* Tools
  * [SAM-BA Programming Tool](https://github.com/atmelcorp/sam-ba/releases/tag/v3.8.1)
