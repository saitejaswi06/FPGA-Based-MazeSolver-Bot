
# FPGA-Based MazeSolver Bot
### e-Yantra Robotics Competition 2025–26 | Verilog HDL | FPGA | Robotics | Embedded Systems

An FPGA-based autonomous MazeSolver Robot developed as part of the **e-Yantra Robotics Competition (eYRC) 2025–26**, organized by **e-Yantra, IIT Bombay**. The project focused on designing a complete robotic system powered by a custom FPGA architecture capable of autonomous maze navigation, sensor interfacing, and environmental monitoring inside a warehouse-inspired environment.

The competition emphasized designing the complete digital hardware architecture from scratch using **Verilog HDL**, including processor design, peripheral interfacing, memory architecture, control logic, and hardware verification.

---

# Table of Contents

- Overview
- Competition Theme
- Project Objectives
- System Architecture
- Hardware Architecture
- Processor Architecture
- Robot Functionality
- Our Contributions
- Technologies Used
- Learning Outcomes
- Future Scope
- Team
- Acknowledgements

---

# Overview

The MazeSolver Bot (MB) theme challenged participants to design an autonomous robot capable of navigating through a dynamically changing warehouse maze while collecting environmental information from different sensing zones.

Unlike conventional robotics competitions that primarily rely on microcontrollers, this project required building the complete digital system around an **FPGA**, implementing the processor, control logic, communication interfaces, and peripheral modules using **Verilog HDL**.

The project combined concepts from:

- Digital Design
- FPGA Design
- Verilog HDL
- Computer Architecture
- Embedded Systems
- Robotics
- Sensor Interfacing
- Hardware Verification

---

# Competition Theme

Modern agricultural warehouses require intelligent autonomous systems capable of navigating changing storage layouts while monitoring environmental conditions.

The MazeSolver Bot was designed to:

- Navigate through an unknown warehouse maze
- Detect obstacles
- Execute autonomous path planning
- Read environmental sensors
- Monitor warehouse microclimate
- Communicate with a central control system

The warehouse environment simulated:

- Produce storage racks
- Dynamic pathways
- Environmental sensing stations

The bot was expected to collect information such as:

- Temperature
- Relative Humidity
- Soil Moisture

while autonomously traversing the arena.

---

# Project Objectives

The project aimed to develop an FPGA-powered autonomous robot capable of:

- Autonomous maze solving
- Digital motor control
- Sensor data acquisition
- Peripheral communication
- Instruction execution
- Environmental monitoring
- Real-time robotic control

---

# System Architecture

```

Warehouse Arena
│
├── Obstacle Detection
├── Navigation
├── Sensor Nodes
│
▼

MazeSolver Robot
│
├── FPGA
│ ├── Custom RISC CPU
│ ├── Instruction Decoder
│ ├── Control Unit
│ ├── Register File
│ ├── ALU
│ ├── Program Counter
│ ├── Memory Interface
│ └── Peripheral Controller
│
├── Sensors
├── Motor Driver
├── Wireless Communication
└── Power System

````

---

# Hardware Architecture

The robot was designed around an FPGA platform implementing a complete digital hardware system.

Major hardware modules included:

* Custom Processor
* Instruction Memory
* Data Memory
* ALU
* Register File
* Control Unit
* GPIO Interface
* Motor Controller
* Sensor Interface
* UART Communication
* PWM Control

---

# Processor Architecture

One of the primary objectives of the competition was designing a simple processor capable of executing robotic instructions.

The processor architecture included:

* Program Counter (PC)
* Instruction Memory
* Instruction Decoder
* Arithmetic Logic Unit (ALU)
* Register File
* Control Logic
* Memory Interface

The processor executed instructions responsible for:

* Robot movement
* Sensor acquisition
* Decision making
* Motor control
* Communication

---

# Robot Functionality

The intended robot workflow consisted of:

1. Read sensor inputs

2. Identify surrounding walls

3. Decide navigation path

4. Execute movement instruction

5. Update robot position

6. Acquire environmental sensor data

7. Continue exploration until destination

---

# Our Contributions

As part of the competition, our team worked on developing the FPGA-based digital architecture required for the MazeSolver Bot.

Our contributions included:

* Implemented digital hardware modules using **Verilog HDL**
* Developed RTL modules for processor and control logic
* Designed instruction execution flow for robot navigation
* Worked on custom **RISC-based processor** architecture
* Applied **Finite State Machines (FSMs)** for robot control
* Implemented instruction decoding and datapath modules
* Worked on memory organization and peripheral interfacing
* Performed functional verification through simulation
* Studied FPGA implementation workflow and hardware debugging
* Worked towards integrating autonomous navigation and environmental sensor interfaces

The team successfully progressed to **Stage 2** of the **e-Yantra Robotics Competition**, completing the required design milestones before concluding the project.

---

# Technologies Used

## Hardware Description Language

* Verilog HDL

## Digital Design

* RTL Design
* FSM Design
* Datapath Design
* Processor Design

## FPGA

* FPGA Architecture
* Hardware Verification
* Digital Logic Design

## Robotics

* Autonomous Navigation
* Sensor Interfacing
* Robot Control

## Computer Architecture

* RISC Processor
* Instruction Decoder
* Register File
* ALU
* Memory Organization

---

# Skills Demonstrated

* Verilog HDL
* FPGA Design
* RTL Design
* Digital Logic Design
* Computer Architecture
* Embedded Systems
* Hardware Verification
* Finite State Machines
* Processor Design
* Robotics
* Sensor Interfacing
* Autonomous Navigation

---

# Learning Outcomes

Through this project, we gained practical experience in:

* FPGA-based system development
* RTL design methodology
* Verilog HDL programming
* Processor architecture
* Hardware modularization
* FSM-based control systems
* Functional verification
* Simulation and debugging
* Embedded hardware design
* Collaborative engineering development

The competition also strengthened our understanding of designing complete digital systems for real-time robotic applications.

---

# Future Scope

Potential future improvements include:

* Complete FPGA implementation on hardware
* Advanced autonomous path planning algorithms
* Dynamic obstacle avoidance
* Real-time wireless telemetry
* Multi-sensor fusion
* Optimized processor pipeline
* Hardware acceleration for navigation
* Complete environmental monitoring system
* FPGA-based SLAM implementation

---

# Team

* **Uppuluri Sai Tejaswi**
* **Harish V**
* **Athish Hariharan**
* **Hiba Fatima**

Department of Electrical and Electronics Engineering
**National Institute of Technology Calicut**

---

# Acknowledgements

We sincerely thank **e-Yantra, IIT Bombay** for organizing the **e-Yantra Robotics Competition (eYRC) 2025–26**, which provided an excellent opportunity to explore FPGA-based robotics, digital system design, processor architecture, and autonomous robotic systems.

We also acknowledge the guidance and support provided by the faculty mentors and the Robotics Interest Group (RIG), NIT Calicut, throughout the project.

---


