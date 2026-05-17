# Dual-Mode-Thermal-Energy-Storage-System-

![Status](https://img.shields.io/badge/Status-Prototype_Built-success)
![Domain](https://img.shields.io/badge/Domain-Heat_Pump_+_TES-blue)
![Method](https://img.shields.io/badge/Method-PCM_Integrated-orange)
![Application](https://img.shields.io/badge/Application-Agricultural_Cold_Chain-green)
 
A working heat pump prototype demonstrating **simultaneous capture of cold (0–4 °C) and heat (60–90 °C)** from a single refrigerant cycle, with **phase-change material (PCM) storage** integrated at both ends. Theoretical dual-output COP of **7–9** (combined heating + cooling per electrical input).
 
## Overview
 
Conventional heat pump systems waste one side of the refrigeration cycle. A cold storage facility rejects condenser heat to atmosphere. An industrial dryer dumps the evaporator-side cold. Both pay for energy that produces two useful outputs — but capture only one.
 
This project demonstrates that with proper architecture, both useful outputs can be captured from a single energy input. The combination is especially relevant for agricultural and food-processing facilities in developing regions, where the same site often needs both cold storage and process heat — but cannot afford two separate systems.
 
## Highlights
 
- **Working prototype** delivering simultaneous **70 °C hot / -2 °C cold** output
- Built using salvaged domestic refrigerator compressor + custom heat exchangers in separate water reservoirs
- Designed full PCM-integrated system targeting 0–4 °C cold / 60–90 °C hot
- **Theoretical dual-output COP 7–9** (combined heating + cooling per electrical input)
- Modular architecture: cold storage and drying modules independently or simultaneously operable
- Target applications: agricultural cold-chain + drying, food processing, building thermal services
 
## Prototype
 
![Prototype photo](docs/prototype.jpg)
*Working prototype demonstrating simultaneous hot and cold output*
 
## Methodology
 
1. Refrigeration cycle thermodynamic design for dual-output operation
2. Refrigerant selection for target hot and cold temperature ranges
3. Heat exchanger sizing for both condenser and evaporator-side useful loads
4. PCM selection at transition temperatures matching both target ranges
5. Prototype assembly with salvaged compressor and custom heat exchangers in water reservoirs
6. Experimental validation of simultaneous hot/cold output
7. Full thermodynamic design for the optimised target system (target ranges with PCM storage)
 
## Experimental Results
 
The prototype demonstrated:
 
- **Hot side:** reached **70 °C** in the hot reservoir
- **Cold side:** brought down to **-2 °C** in the cold reservoir
- **Simultaneous operation:** both outputs delivered from one compressor cycle
- Confirmed feasibility of dual-output operation for the target application
 
## Note on the COP Figure
 
The theoretical COP of 7–9 is a **dual-output combined COP** — it accounts for both the heating output and the cooling output delivered, divided by the electrical input. The individual heating-only or cooling-only COP would be lower. The combined figure reflects the total value extracted from a single compressor cycle when both outputs are useful — which is the relevant metric for genuine dual-output applications.
 
## Repository Structure
 
- `/prototype/` — prototype photos and build documentation
- `/cad/` — SolidWorks files for the full designed PCM-integrated system
- `/thermo/` — thermodynamic cycle calculations and COP analysis
- `/pcm/` — PCM selection and sizing analysis
- `/docs/` — design report
- `README.md`
 
## Tech Stack
 
- **CAD:** SolidWorks
- **Analysis:** Python, Excel
- **Hardware:** Domestic refrigerator compressor, custom heat exchangers, water reservoirs
 
## Status
 
Prototype built and tested with measured simultaneous hot/cold output. Full PCM-integrated system design complete on paper. Next phase: purpose-built compressor and PCM-integrated reservoirs.
 
 
