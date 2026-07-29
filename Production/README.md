# Production Files
## Assembly
This folder contains a file including all the positions of components on the PCB, in case any manufacturer requires such a file (Custom Tablet_positions.csv). 
It also includes the file used as a bill of materials for all the components JLCPCB will source (Custom Tablet_jlcpcb_bom.csv). 
It also contains a raw bill of materials file that is used for personal reference of all parts (not just JLCPCB sourced parts) (Custom Tablet_bom_raw.csv).
## Checks
This folder contains the final ERC and DRC checks to ensure that the PCB does not have any fatal errors before production. If PCB files are altered, they must be exported again.
## Gerbers
This folder contains all the files most manufacturers will need to manufacture the pcb. This includes drill files and all the other files necessary.
