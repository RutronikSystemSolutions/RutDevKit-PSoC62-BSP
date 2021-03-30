
Rutronik Development Kit PSoC62 Board Support Package

MODIFICATION:

1. Find the Makefile and edit this line: TARGET=PSOC6-GENERIC
2. Delete the folder "TARGET_RutDevKit-PSoC62".
3. Copy the APS6404L-3SQR-ZR.cymem memory configuration file to the directory mtb_shared --> TARGET_PSOC6-GENERIC --> COMPONENT_BSP_DESIGN_MODUS
4. Do all the changes needed.
5. Double click on [Build Targets].
6. Double click on [bsp TARGET_GEN=RutDevKit-PSoC62 DEVICE_GEN=CY8C6245AZI-S3D72].
7. After build is completed successfuly open the Makefile again and edit the line: TARGET=RutDevKit-PSoC62
8. Save the Makefile and build the whole project.

USE THE BSP:

1. Open The Project Creator: File --> New --> ModusToolbox Application
2. Browse the BSP location: The folder inside the  TARGET_RutDevKit-PSoC62 must be selected for a custom BSP usage.
3. Proceed with selecting "Empty PSoC6 App" or any campatible project example. 
4. Finish generating/impoting the project.