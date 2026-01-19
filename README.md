# beaver-3D-puzzle
A 3D-printed puzzle of a beaver in a top hat.

# Gravity-Driven Mechanical Beaver Puzzle 

## Project Overview
This project is a 3D mechanical puzzle designed in **SolidWorks**. It features a linkage mechanism where actuating the beaver's tail triggers a state transition, raising a top hat. The design relies on gravity-driven mechanics rather than springs or electronics.

## Key Engineering Features

### Mechanism Design
* **Dual-State Stability:** Engineered a linkage system with two points (Default & Top-Hat-Raised).
* **Gravity Validation:** Validated the state transitions using SolidWorks Motion Analysis to ensure reliable actuation without external springs.

### Design for Manufacturability (DFM)
* **Parametric Scaling:** Implemented **Global Variables** for tolerances. This allows the entire assembly to be scaled down by 20% while automatically preserving critical functional clearances (0.2mm - 0.3mm).
* **Interference Detection:** Used assembly analysis to ensure zero collisions during the kinematic path of the linkage.

## Technical Details
* **Software:** SolidWorks (Modeling & Motion Study)
* **Material:** PLA
