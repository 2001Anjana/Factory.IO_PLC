## **Bottle Cap Assembly Factory Simulation**

This repository contains the simulation of a Bottle Cap Assembly Factory, developed using Factory IO, with the programming part handled in SIEMENS TIA Portal V16. The simulation is run using S7 PLCSIM V16, and the programming logic is implemented using Ladder Logic.

**Table of Contents**
- [Overview](#overview)
- [Tools Used](#tools-used)
- [System Workflow](#system-workflow)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Future Improvements](#future-improvements)
- [License](#license)

**Overview**

The project simulates the bottle cap assembly process in a factory environment. It showcases an automated assembly line, controlled by a PLC (Programmable Logic Controller), using ladder logic programming.

**The main objectives of this simulation**:
- To automate the assembly of bottle caps onto bottles.
- To simulate a realistic factory environment for educational and testing purposes.
- To control the process via a PLC, enhancing industrial automation skills.

**Tools Used**
- **Factory IO**: For creating the factory simulation environment.
- **SIEMENS TIA Portal V16**: For writing ladder logic and integrating with the PLC.
- **S7 PLCSIM V16**: To simulate the PLC and test the logic without actual hardware.

**System Workflow**
1. Bottles move along the conveyor belt.
2. A sensor detects the arrival of each bottle.
3. The bottle is positioned under a capping station.
4. The cap is placed on the bottle, and the assembly process is completed.
5. The bottle is moved further for packaging or quality control.

**Prerequisites**
- **Factory IO** (licensed version)
- **SIEMENS TIA Portal V16**
- **S7 PLCSIM V16**

**Usage**
1. Open **Factory IO** and load the factory environment file provided.
2. Open **SIEMENS TIA Portal V16**, and load the ladder logic project.
3. Start **S7 PLCSIM V16** to simulate the PLC and connect it to the factory simulation.
4. Run the simulation to observe the bottle cap assembly process.
