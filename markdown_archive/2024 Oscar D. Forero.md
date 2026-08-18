# Seismic Vulnerability Assessment of Non-Structural Elements Inside an Inflatable Lunar Habitat

**Authors:** Oscar D. Forero, Julio A. Ramirez, Ph.D., and Shirley J. Dyke, Ph.D.
**Publication:** Earth and Space 2024, ASCE

## Abstract
This study develops a procedure for vulnerability assessment of essential non-structural elements (NSE) inside an inflatable lunar habitat, specifically focusing on the Environmental Control and Life Support System (ECLSS). Using NASA's Moon to Mars Architecture requirements, the study addresses moonquakes (shallow seismic events) which are often overlooked compared to launch vibrations. Findings suggest that due to epistemic uncertainty, significant long-lasting vibrations may occur, necessitating effective mitigation measures.

## Introduction
NASA's Artemis program plans for surface missions by the end of the decade. Inflatable habitats are a focus due to their high payload-to-volume efficiency. While designs are typically engineered for launch vibrations, the risk posed by shallow moonquakes to structural integrity and internal contents remains a critical question.

## Case Study
The analyzed habitat is a torus-shaped inflatable structure mounted atop a lander. 
- **Height:** 6 meters, two floors.
- **Support:** Cantilever hydraulic jack system.
- **Internal Component:** ECLSS universal pallet (0.60m x 0.60m x 1.80m) located on the second floor.
- **Connections:** Pin connections to the aluminum core of the torus.

## Launch and Seismic Environments
### Launch Dynamic Environment
- **Tests:** Sine sweep and random vibration tests (based on Atlas V and Falcon 9 specifications).
- **Duration:** Typically a few minutes.
- **Focus:** High-frequency excitations from engine ignition, liftoff, and aerodynamic pressure.

### Lunar Seismic Motion Environment
- **Data Source:** Apollo Passive Seismic Experiment (APSE).
- **Events:** 28 shallow moonquakes (High-Frequency Teleseismic events).
- **Characteristics:** Low frequency (primarily < 10 Hz), potential ground acceleration up to 1.6g_L or 4g_L near the source.
- **Duration:** Can persist for over an hour.

## Numerical Simulation and Results
A time-stepping technique using Newmark's method was used for dynamic analysis. 
- **Deployed Primary Structure:** Maximum displacement of 2.4 cm under 1.0g_L seismic load.
- **Undeployed Structure (Launch Config):** Maximum displacement of 0.6 cm.
- **Scaling Factor:** A scale factor of 3.0g_L was identified to approximate the deformation levels of launch requirements.
- **Resonance:** Low-frequency seismic waves (<10 Hz) may resonate with deployed lunar habitats, a condition not currently accounted for in launch-based vibration designs.

## Discussion and Conclusion
There is a significant disparity between launch loads and seismic loads. While the ECLSS (with high fundamental frequency) is susceptible to launch vibrations, the primary deployed habitat structure is more sensitive to the low-frequency, long-duration nature of moonquakes. Future long-term surface settlements must consider these seismic effects for material integrity and functionality of life support systems.