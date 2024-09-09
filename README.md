# FRANK_ToolHead
this is my custom "Frank" Toolhead that many have been asking about. 
![Frank_front_view](https://github.com/user-attachments/assets/4cef0245-cc67-44f8-abb1-b873dc5ebb6f)
 Note that im fairly new to CAD and have only been building custom toolheads for about a year or so now. that being said, i've been able to successfully install this on my printer with minimal post processing 
 required. 
This toolhead was designed to meet the design requirement of my printed which i call "Voron Frankenstein". I could not think of a cooler name for the tool head other than "FRANK" so that what im calling it for now lol. I've added all the step files to this repository and encourage anyone to iterate on this design to meet there specific build requirement.   
# Print_requirements 
 At this time, none of the stl files are oriented in optimal print positions, im sorry about that. You will need to orientate models to best suit your printer.
 I followed the print requirements of the voron build for printed parts
 
3D PRINTING PROCESS
Fused Deposition Modeling (FDM)

MATERIAL
ABS/ASA

LAYER HEIGHT
Recommended: 0.2mm

EXTRUSION WIDTH
Recommended: Forced 0.4mm

INFILL TYPE
Grid, Gyroid, Honeycomb, Triangle or Cubic

INFILL PERCENTAGE
Recommended: 40%

WALL COUNT
Recommended: 4

SOLID TOP/BOTTOM LAYERS
Recommended: 5

(PULLED FROM VORON MANUAL)

# BOM 
Toolhead mounts to MGN9H rails 

Heatset Screws hole size - M3X5X5

Probe - Beacon RevH Low Profile

Toolhead - Phaetus Rapido UHF with pt1000 temp sensor 

Extruder - LDO orbitor v2 with V2 runout sensor 

Knomi v2 screen (I currently dont have a designs thats made without the screen)

CAN Board - EBB36 W/Max31865(recommend with pt1000 temp sensor for more accurate reading)

Fans - 3010 fans (x2)

Cable Gland - NPT 3/8 spiral cable gland 

Toolhead heatsink  shroud is a standard V6 style. It does install loose on the rapido heatsink due to it being tapered, the shroud is held in place once the main cover is installed. ive had no issues with heat creep or rattling once fully tightened. 

limit switch  dimensions L x W x H =	3.94 x 3.94 x 1.97 inches

# NOTES
The Limit switch is located on the fan duct on the right side (i home x to the right). The xy carriages are custom and limit switch location is desiged 
for this build but should reach to standard voron carriages. You may need to change the design to fit your build or sensorless home. 
![Part Studio 1 (1)](https://github.com/user-attachments/assets/96b011b0-05b6-47e7-9ae2-f275275992e9)


Ive hade connection stability issues with the Knomi screen using the provided antenna. im using a mini Male Right Angle Antenna with IPEX MHF4 to RP-SMA cable to connect to the screen. 
![PXL_20240717_013347062 (1)](https://github.com/user-attachments/assets/801ebe08-832b-49cb-93ce-41089930ef13)
![PXL_20240717_012743512](https://github.com/user-attachments/assets/0bf3882e-db01-4648-baa5-ec9bfa8d387d)


The Extruder driver cooling fan(3010) only mounts to the right rear cover. though there are mounting holes on the left rear cover as well . That is a design flaw that i need to address but have yet to do so. 

![PXL_20240717_013503916](https://github.com/user-attachments/assets/a2dbd077-b394-43e2-836f-aedfbcca220d)



