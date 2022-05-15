# Report
## Absract
Wiper is an essential component that used to wipe raindrops or water from the vehicle’s windscreen. Wipers are designed and made to clear the water from a windscreen. Most of cars have two wipers on the windscreen, one on the rear window and the other on each headlight. The wiper parts visible from outside the car are the rubber blade, the wiper arm holding the blade, a spring linkage, and parts of the wiper pivots. The wiper itself has about six parts called pressure points or claws that are small arms under the wiper.
The prior system required manual wiper activation,by changing the frequency As its results the operation of bringing up the wiper speed is varied . The project's goals are to improve ageing cars' systems by giving automated transmission.wiping system, to improve the system by incorporating a sensor and actuator, and to create a simple software that would completely operate with the system.the framework This proposed wiper system's principle is comparable to those of other existing conventional wipers. Despite the fact that. This system will be upgraded to an automatic control system using a Peripheral Interface to remove water from the windscreen.
## Introduction
A wiper speed control system for an automobile wiper regulates the operating speed of a wiper in accordance with the amount of rain falling on the windshield. This is a very much essential component in each automobile as it avoids the risk of accidents during rainy conditions.It useful in the automotive unit the main purpose of the system is to clean the windscreen sufficiently to provide suitable visibility at all times.
## Software Reqirements
STM32 CUBE IDE
## Components
STM32F4O7VG microcontroller board
## Component description
### STM32F4O7VG 
The STM32F407 Kit makes it simple for users to construct audio-based applications by utilising the high-performance STM32F407 microcontrollers' capabilities. It includes an ST-LINK embedded debug tool, a digital microphone, an audio DAC with integrated class D speaker driver, LEDs, pushbuttons, and a USB OTG micro-AB connector. The STM32F4 DISCOVERY kit now includes Ethernet connectivity, an LCD display, and other features. The Arm® Cortex®-M4 32-bit RISC processor, which works at up to 168 MHz, is at the heart of the STM32F405xx and STM32F407xx families.
### Features of STM32F407VG
* In a LQFP100 package, the STM32F407VGT6 microcontroller has a 32-bit ARM Cortex-M4 with FPU core, 1-Mbyte Flash memory, and 192-Kbyte RAM.
* On-board ST-LINK/V2 or ST-LINK/V2-A on STM32F4 DISCOVERY (old reference) or STM32F407G-DISC1 (new order code)
* USB ST-LINK with three separate interfaces and re-enumeration capability and Virtual Com port Debug port (with new order code only)
* Large-scale storage (with new order code only)
* Board power is supplied through USB or an external 5 V supply source. 3 V and 5 V external application power supply
### Applications
* This Microcontroller is used in printing and scanning machines ,heat ventilation, air conditioning, and security systems.
* Uses of this module can be found in various household products.
## Research
### Objectives
A wiper speed control system for an automobile wiper regulates the operating speed of a wiper in accordance with the amount of rain falling on the windshield. This is a very much essential component in each automobile as it avoids the risk of accidents during rainy conditions. Our objective is to build a Wiper Control system using STM32 which is a 32-bit microcontroller IC.The wiper operation can be carried out with basic modes like On, speed change and Off. As STM32 contains only 1 push button, the same button is utilized for all operations. The discovery board contains 4 LEDs
## Defining our system
Assume the microcontroller is the automobile. When the button is pressed, the first led (red) turns on, the wiper starts, and the second led (blue) turns on at the appropriate rate. The third led (green) will turn on if the button is pressed again, and the wiper speed will be increased in contrast to the previous one. The fourth press will activate the fourth led (orange) and raise the wiper speed in accordance with the previous one. After the fifth click, the microcontroller (vehicle) is turned off.
### System operation
* When the button is pressed once the car will start (Ignition key postion at ACC)
* When the button is pressed again the wiper will start(Wiper On)
* When the button is pressed again the wiper will off(Wiper Off)
* When the button is pressed thrice the car will stop(Ignition key position at Lock)
## SWOT Analysis
### Strength
Windscreen wipers are necessary for maintaining sufficient view for the driver. Also, wipers manages all commands with one key automatically.
### Weakness
Cost of the wiper system is high.
### Opportunities 
Automatic operation can be implemented as further enhancement.
### Threats
Only limited functions available
## 5W's & 1H 
### What
It is Wiper Control system which is generally deployed in all the automobiles
### When
We use wiper system during weather conditions like rain and snow.
### Where
Front and rear windsceen of automobiles.
### Who
Wipers are used by drivers to remove water or snow on the windscreen of automobiles
### Why
To avoid accidents by getting a clear vision of a road.
## High Level Requirements
| ID | Description | Category | Status |
| ---|:------------|:---------|:-------|
| HLR1 | can be able clear rain and snow wind shield | Technical | IMPLEMENTED |
| HLR2 | can be able to improve headlight visibility at night | Technical | IMPLEMENTED |
| HLR3 | can be able to driver to have a clear view | Technical | IMPLEMENTED |
## Low Level Requirements
| ID | Description | HLR ID | Status |
| ---|:------------|:-------|:----------------------------|
| LLR1 | switch on the wiper | HLR1 | IMPLEMENTED |
| LLR2 | press push button for different operations | HLR2 | IMPLEMENTED |
| LLR3 | switch off the wiper | HLR3 | IMPLEMENTED |
## Wiper on various speeds
![](https://github.com/Heiram/M3_Wiper_Control_System/blob/main/5_Report/Wiper%20on%20low%20speed.png)
![](https://github.com/Heiram/M3_Wiper_Control_System/blob/main/5_Report/Wiper%20on%20moderate%20speed.png)
![](https://github.com/Heiram/M3_Wiper_Control_System/blob/main/5_Report/Wiper%20on%20High%20speed.png)
