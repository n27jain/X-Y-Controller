# X-Y-Controller
**File Created By:** Naman Jain
**Last Update:** 1/5/2020

This is a collaborated university embedded systems project created by Naman Jain and Anubhav Saini. To learn more check out our project presentation [Slides]!


## Project Technologies and Resources :
  - [Diptrace] (Schematic) (PCB Design) (Manual Wire Routing) 
  - [MSP-EXP430FR4133] (Micro-Controller Board)
  - [Rigidware MarketPlace] (University Store) (Circuitry parts and wiring)
  - [Sodering] () 
  - [Oscilliscope] (Circuitry Debugging)
  - 
## Data Sheets


## Objectives
- A two-axis system where each axis is driven by a single stepper motor
- Each axis has limiters in the form of REFL Light Sensors
- User enters coordinates of desired position via Keypad
- Coordinates displayed on LCD
- Prepare and design a PCB board that is placed upon a microcontroller
- Print the PCB from a factory and then solder the componenets
- Assembly external wires and components to the board

![Project Schematic](https://firebasestorage.googleapis.com/v0/b/storage-for-projects.appspot.com/o/Schematic%20Design.png?alt=media&token=a768c626-d163-4b11-878d-ef2b09a010ed)

---(Schematic of the PCB Design)---

This Diagram is created using diptrace to allow a high level view of what the routing will look like in the final PCB Design. This tool allows the user to easily find routing mistakes and open connections. 

![PCB Diagram](https://firebasestorage.googleapis.com/v0/b/storage-for-projects.appspot.com/o/pcb%20routing.png?alt=media&token=aa9da03f-c664-4e67-8560-9a63efa13afb)

---(PCB Final Layout)---

This diagram is made using diptrace. This tool is useful because production factories can take the produced file and print out the solid PCB easily. Due to space constraints our design is a little messy. There are too many shared lines, and because of 16 diodes we have many wires crossing over. Both the top and bottom of the board are shown here.

 ![PCB Top](https://firebasestorage.googleapis.com/v0/b/storage-for-projects.appspot.com/o/solder%20top.jpg?alt=media&token=f9645fa9-86d3-456a-8b33-00efecda9b50)

![Bottom](https://firebasestorage.googleapis.com/v0/b/storage-for-projects.appspot.com/o/solder%20bottom.jpg?alt=media&token=4e0a6e08-397c-4091-8673-cc264e50d14a)

---(PCB Printed and Soldered )---



## Contribution and Usage Rights
Pull requests are welcome. No changes allowed! Please do not copy the documents provided as they are our acedemic properties. Please credit where images are used.

[Diptrace]: <https://diptrace.com/>
[MSP-EXP430FR4133]: <https://firebase.google.com/>
[Rigidware MarketPlace]: <https://www.engsoc.uwaterloo.ca/ridgidware/>
[Oscilliscope]: <https://github.com/ArthurHub/Android-Image-Cropper>
[Slides]: <https://docs.google.com/presentation/d/1CYS54YSZ_er0cwmIdWw0txBPDk2QcQ2v4sf5bczO5I4/edit?usp=sharing>
