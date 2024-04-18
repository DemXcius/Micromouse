# Micromouse
# The repository for my third-year engineering design project
This repository contains the design and production files for the Power and Sensor modules of a micro-mouse, as part of the EEE3088F course at UCT 2024 Main Project.
# Project Overview: Micro-Mouse Hardware Design
## What is a Micro-Mouse?
In essence, a micro-mouse is a maze-solving robot. If you're unfamiliar with the concept, watching the Veritasium video linked below will provide you with a clearer understanding. It's worth noting that while the robots featured in the video may be quite speedy, your micro-mouse will likely (almost certainly) operate at a slower pace. Nonetheless, let the video serve as inspiration for your project.

## Project Description
This project focuses primarily on the design of the micro-mouse's hardware, with some minor software components. The main challenge lies in meeting the project's requirements while adhering to a STRICT budget. To facilitate this endeavor, the project has been divided into four modules: the processor, motherboard, sensing, and power.

The processor and motherboard modules have already been designed and will be provided. The task involves designing and manufacturing the sensor and power modules.

## Project Modules
### Processor Module: 
This module entails the design of the microcontroller unit responsible for controlling the micro-mouse's actions within the maze. The processor module has already been developed and will be supplied.

### Motherboard Module: 
The motherboard serves as the central hub for connecting various hardware components of the micro-mouse. Like the processor module, the motherboard has been designed and will be provided.

### Sensing Module: 
The project will involve designing and manufacturing the sensing module, which comprises sensors responsible for detecting walls, corners, and other obstacles within the maze.

### Power Module: 
Lastly,the project involves designing and manufacturing the power module, which will provide the necessary electrical power to all components of the micro-mouse.

## Budget Constraint
It's crucial to note the strict budget constraint imposed on this project. While innovation and creativity are encouraged, all design decisions must be made with the budget in mind.
## Project Details:
- Project Focus: Power and sensing module design and manufacturing.
- Project Components: Power module must operate 2 motors, provide battery voltage information, charge the battery, and include an ON/OFF switch.
- Connectors: JST PH 2mm pin pitch connector for the battery and a 2x8 (2.54mm pin pitch) pin header for interfacing with the motherboard.
## Subsystem Description: Power
- Motor Operation: Control 2 motors, each capable of drawing up to 200mA, powered by a 1S1P battery.
- Battery Voltage Sensing: Provide an analog connection to sense battery voltage for battery state of charge (SoC) monitoring.
- Battery Charging: Charge the battery from the 5V input pin. Must handle the scenario when 5V is removed.
- ON/OFF Switch: Incorporate an ON/OFF switch with specific power consumption requirements in the OFF and ON states.
## Included Files:
- Datasheets: Datasheets for components used in the Power and Sensing module.
- Production Files: Files required for manufacturing the Power and Sensing module, including Gerber files and Bill of Materials (BOM).
## Usage:
- Clone the repository to access all project files.
- Review the datasheets for component specifications.
- Use the production files for manufacturing the Power module PCB.
- Review and modify the PCB files as needed for customization.
- 

