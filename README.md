🚀 Rocket Specifications

The physical and geometric parameters used in the simulation model are detailed below:

| Parameter | Value | Unit | Description |
| :--- | :--- | :--- | :--- |
| *Mass* | 44,2] | g | Total mass |
| *Mass with 276H 152-15A-6* | 342 | g | Total mass with 276H 152-15A-6 |
| *Mass with G77R-6* | 199 | g | Total mass with G77R-6 |
| *Body Diameter* | 2,5 | cm | Outer airframe diameter |
| *Total Length* | 42,5 | cm | Overall rocket length |
| *Nose Cone Types* | Ogive / Conical / Ellipsoid | - | Evaluated geometries |
| *Recovery System* | Dual Deployment | - | Drogue & Main Parachutes |

### Propulsion System Details
* *276H 152-15A-6 Motor:* High-impulse configuration targeting ~2200 m Apogee.
* *G77R-6 Motor:* Standard impulse configuration targeting ~1200 m Apogee.

## Aerodynamic Stability & Mass Properties 

The static stability margin is calculated based on the distance between the Center of Gravity (CG) and the Center of Pressure (CP), expressed in body diameters (Caliber).

**For 276H 152-15A-6
| Parameter | Launch Condition | Unit |
| :--- | :--- | :--- |
| *Center of Gravity (CG)* | 29.3 | cm |
| *Center of Pressure (CP)* | 32 | cm |
| *Distance (CP - CG)* | 2.7 | cm |
| *Static Stability Margin* | *1.07* | *Caliber* |

**For G77R-6
| Parameter | Launch Condition | Unit |
| :--- | :--- | :--- |
| *Center of Gravity (CG)* | 29.4 | cm |
| *Center of Pressure (CP)* | 32 | cm |
| *Distance (CP - CG)* | 2.5 | cm |
| *Static Stability Margin* | *1.05* | *Caliber* |

> *Note:* A static stability margin between *1 and 2.0 Caliber* was targeted throughout the powered flight phase to ensure aerodynamic stability without over-restoration under crosswind conditions.

 
📈 Rocket Performance and Aerodynamic Analysis Simulation (MATLAB)

This repository contains a MATLAB simulation designed to analyze the flight dynamics of rocket motors (276H & G77) under varying environmental wind conditions (0, 10, 20 km/h) and aerodynamic nose cone geometries (Ogive, Conical, Ellipsoid).

### Key Features
- **Motor Comparison:** Apogee (peak altitude) and vertical velocity analysis between 276H and G77 motors.
- **Aerodynamic Optimization:** Evaluation of Drag Coefficient ($C_d$) effects across Ogive, Conical, and Ellipsoid nose cones.
- **Wind Dynamics:** Assessment of vertical velocity stability and apogee loss under different wind speeds.
- **Data Visualization:** Automated multi-subplot line & bar charts generated via MATLAB.

### Key Insights
- The Ogive nose cone achieved the highest apogee by minimizing aerodynamic drag.
- The 276H motor yielded approximately 83% higher peak altitude compared to the G77 motor.
