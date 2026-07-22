# Fabrication of Flexible Thermoelectric Energy Harvesting System

**Authors:** Guangxi Wu, Ferin Neff, and Xiong (Bill) Yu  
**Publication:** Earth and Space 2018, ASCE

## ABSTRACT
Thermoelectric energy harvesting is promising to provide sustainable energy source in the extraterrestrial environment. This paper describes procedures incurred in the fabrication of thermoelectric energy harvester on flexible substrates. An electrically parallel structure is proposed, which features higher energy efficiency than the counterpart electrically series structure based on theoretical analyses. As proof of concept, flexible thermoelectric harvesters in electrically parallel and series structures are prepared with thick film printing procedures. The performance of elements and device with different architectures are characterized. Both analytical and experimental comparison imply a promising improvement of energy conversion efficiency by using the electrically parallel structure.

## INTRODUCTION
Thermoelectric modules (TEMs) when used as generators (TEGs) are capable of providing continuous energy for extraterrestrial explorations, where sun light is not always available or intense enough for solar cells to work. For example, the solar brightness on Mars and Jupiter is as weak as 45% and 4%, respectively. Radioisotope thermoelectric generators (RTGs) have received interest for autonomous missions in extreme environments. However, the naturally existing temperature gradients on spacecraft or extraterrestrial vehicles (e.g., -153°C to 123°C on the Moon) have not been effectively leveraged. This paper proposes flexible TEGs to cover vehicle or habitat surfaces to boost energy provision.

## ELECTRICALLY SERIES TEM EFFICIENCY
Conventionally, TEMs use series connections. The maximum efficiency $\eta_{max}$ is governed by the dimensionless figure-of-merit ($ZT_{module}$):

$$\eta_{max} = \frac{T_H - T_C}{T_H} \cdot \frac{\sqrt{1 + ZT_{module}} - 1}{\sqrt{1 + ZT_{module}} + \frac{T_C}{T_H}}$$

### Table 1. Material properties of a pair of thermoelectric materials (Bi2Te3).
| Material | Electrical Resistivity $\rho$ (mΩ·cm) | Seebeck Coefficient $\alpha$ (μV/K) | Thermal Conductivity $\kappa$ W/(cm·K) | Material figure-of-merit $ZT_{material}$ at 300K |
| :--- | :--- | :--- | :--- | :--- |
| Bi2Te3 (p) | 0.83 | 156.57 | 2.09×10⁻² | 0.42 |
| Bi2Te3 (n) | 0.73 | -193.00 | 2.04×10⁻² | 0.74 |

The mismatch in p-type and n-type material properties leads to an attenuation factor $A$ (calculated as 0.76 in this case), wasting about 24% of the higher-performing material's potential.

## ELECTRICALLY PARALLEL TEM EFFICIENCY
This paper proposes a structure where legs are connected in parallel both thermally and electrically. This allows the module's figure-of-merit to match the material with the higher $ZT$, potentially increasing efficiency by 32% for the materials listed in Table 1.

## TEM FABRICATION PROCESS USING FILM PRINTING TECHNOLOGY
1.  **Material Preparation:** Bi2Te3 coarse powder was ball-milled to produce nanocomposites, increasing $ZT$ through grain boundary scattering.
2.  **TE Ink Preparation:** Ground p-type and n-type powders were mixed with an epoxy matrix system (EPON Resin 863) at a ratio of 4.5:1.
3.  **Printing Process:** Gold ink (Ercon E4464) was used for electrodes. The TE legs were printed using a stencil printing process on flexible polyimide substrates. Curing was performed at 110°C.

## ELECTRIC OUTPUT PERFORMANCE CHARACTERIZATION
Testing involved a platinum resistor heat source and an iced water heat sink. Performance was monitored using a custom trans-impedance amplifier design. Results indicated that the n-type electrically parallel structure TEM achieved higher maximum output power compared to the p-type parallel and the standard series structures.

## CONCLUSION
The electrically parallel structure is a prospective solution for improving energy conversion efficiency and simplifying large-area fabrication on flexible substrates for space applications. A sandwiched multilayered structure is suggested for future large-area production.