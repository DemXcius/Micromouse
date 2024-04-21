# Micromouse
# The repository for a third-year engineering design project
This repository contains the design and production files for the Power and Sensor modules of a micro-mouse, as part of the EEE3088F course at UCT 2024 Main Project.

# Project Overview: Micro-Mouse Hardware Design

## What is a Micro-Mouse?
In essence, a micro-mouse is a maze-solving robot. If you're unfamiliar with the concept, watch [Veritasium's]([url](https://www.youtube.com/watch?v=ZMQbHMgK2rw)) video to gain a clearer understanding. It's worth noting that while the robots featured in the video may be quite speedy, this micro-mouse will likely (almost certainly) operate at a slower pace. Nonetheless, let the video serve as inspiration.

## Project Description
This project focuses primarily on the design of the micro-mouse's hardware, with some minor software components. The main challenge lies in meeting the project's requirements while adhering to a STRICT budget. To facilitate this endeavor, the project has been divided into four modules: the processor, motherboard, sensing, and power.
The processor and motherboard modules have already been designed and this repository focuses only on the sensing and power modules. 

## Project Modules

### Processor Module: 
This module entails the design of the microcontroller unit responsible for controlling the micro-mouse's actions within the maze. The processor used is an STM32L476.

### Motherboard Module: 
The motherboard serves as the central hub for connecting various hardware components of the micro-mouse. Here, there is leeway as to how you design the motherboard.

### Sensing Module: 
The project will involve designing and manufacturing the sensing module, which comprises sensors responsible for detecting walls, corners, and other obstacles within the maze.

### Power Module: 
Lastly, the project involves designing and manufacturing the power module, which will provide the necessary electrical power to all components of the micro-mouse.

## Budget Constraint
It's crucial to note that this project had a strict budget constraint imposed. While innovation and creativity are encouraged, all design decisions were made with the budget in mind.

## Project Details:
- Project Focus: Power and sensing module design and manufacturing.
- Connectors: JST PH 2mm pin pitch connector for the battery and a 2x8 (2.54mm pin pitch) pin header for interfacing with the motherboard.
- Budget: $8.25 per board.

## Subsystem Description: Power
- Motor Operation: Controls 2 motors, each capable of drawing up to 200mA, powered by a 1S1P battery.
- Battery Voltage Sensing: Provides an analog connection to sense battery voltage for battery state of charge (SoC) monitoring.
- Battery Charging: Charges the battery from the 5V input pin. Must handle the scenario when 5V is removed.
- ON/OFF Switch: Incorporates an ON/OFF switch with specific power consumption requirements in the OFF and ON states.
  
## Subsystem Description: Sensing
- Sensor Operation: Detects whether there is an obstacle in front of the robot or on its sides.
- Power Saving: Has switching means to save power when not in operation.
- Main Components: 4x TSAL4400 IR LED's, 3x SFH205F photodiodes, 1x LiPo 800mAh 3.7V

- ## Included Files:
- Datasheets: Datasheets for components used in the Power and Sensing module.
- Production Files: Files required for manufacturing the Power and Sensing module, including Gerber files and Bill of Materials (BOM).
- Schematics: Schematics for Power and Sensing modules.
  
## Usage:
- Clone the repository to access all project files.
- Review the datasheets for component specifications.
- Use the production files for manufacturing the Power or Sensing module PCB's.
- Review and modify the PCB files as needed for customization.
  
- NOTE: Production and files associated with the production were designed and used to use [jlcpcb]([url](https://jlcpcb.com/)) as the manufacturer.

