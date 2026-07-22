# Numerical Simulation of 3D Printing of Infrastructure Materials

**Authors:** E. Ramyar, Z. Xinwei, G. Cusatis
**Publication:** Earth and Space 2021, pp. 1242-1250
**Publisher:** American Society of Civil Engineers (ASCE)

## Abstract
3D printing is a disruptive force for terrestrial and extraterrestrial infrastructure development. This paper presents the Discrete Fresh Concrete Model (DFCM), a particle-based cementitious material model that simulates rheological and mechanical behavior before, during, and after printing. The interaction among spherical particles is governed by visco-plastic constitutive equations based on stress-strain relationships, enabling a seamless transition from fresh to hardened concrete descriptions.

## Introduction
Concrete 3D printing challenges are twofold: adapting technology to rheological characteristics and developing new materials. Simulation tools are crucial for monitoring, control, and optimization of these processes, especially for autonomous remote operations on other planets.

## Discrete Fresh Concrete Model (DFCM)
The DFCM adopts rigid composite spherical particles to simulate coarse aggregates surrounded by a layer of soft mortar (excess paste theory). 

### Key Parameters of DFCM:
- **Tensile Strength (σt)**
- **Mortar Normal Modulus (En)**
- **Shear Yield Stress (τ0)**
- **Plastic Viscosity (μ∞)**
- **Mortar Thickness (h)**

## Validation of Results
The model was validated using two standard tests:
1. **Slump Test:** Successfully simulated Self-Consolidating Concrete (SCC) with a 25.0 cm slump and printable concrete with minimal slump (a couple of centimeters).
2. **ICAR Rheometer Test:** Reproduced torque vs. rotational speed curves for both standard and printable concrete.

## Numerical 3D Printing of the Northwestern Martian Habitat
In collaboration with Skidmore, Owings & Merrill (SOM), the model was applied to simulate the autonomous 3D printing of a dome-shaped Martian habitat as part of NASA’s 3D-Printed Habitat Challenge. The simulation synchronizes the nozzle motion with the material generator (DEM particles) to predict material flow and final configuration under planetary gravity conditions.

## Conclusion
The DFCM provides an accurate tool for modeling the behavior of various concrete types. It can be successfully used to simulate 3D printing processes for concrete structures on any planet, facilitating autonomous construction for long-term extraterrestrial landings.