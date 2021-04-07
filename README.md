# RutDevKit-PSoC62 BSP

Rutronik Development Kit Programmable System-on-Chip CY8C6245AZI-S3D72 Board Support Package. 

 <img src="images/rutdevkit_model.png" alt="banner" style="zoom:20%;" />

------



### MODIFICATION:

1. Find the Makefile and edit this line: TARGET=PSOC6-GENERIC
2. Delete the folder "TARGET_RutDevKit-PSoC62".
3. Copy the APS6404L-3SQR-ZR.cymem memory configuration file to the directory mtb_shared --> TARGET_PSOC6-GENERIC --> COMPONENT_BSP_DESIGN_MODUS
4. Do all the changes needed.
5. Double click on [Build Targets].
6. Double click on [bsp TARGET_GEN=RutDevKit-PSoC62 DEVICE_GEN=CY8C6245AZI-S3D72].
7. After build is completed successfully open the Makefile again and edit the line: TARGET=RutDevKit-PSoC62
8. Save the Makefile and build the whole project.

### USE THE BSP:

1. Open The Project Creator: File --> New --> ModusToolbox Application
2. Browse the BSP location: The folder inside the  TARGET_RutDevKit-PSoC62 must be selected for a custom BSP usage.
3. Proceed with selecting "Empty PSoC6 App" or any compatible project example. 
4. Finish generating/importing the project.



## LEGAL DISCLAIMER

The evaluation board including the software is for testing purposes only and, because it has limited functions and limited resilience, is not suitable for permanent use under real conditions. If the evaluation board is nevertheless used under real conditions, this is done at one’s responsibility; any liability of Rutronik is insofar excluded. 



<img src="images/rutronik_origin_kaunas.png" alt="banner" style="zoom:55%;" />



