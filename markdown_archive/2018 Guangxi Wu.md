# Fabrication of Flexible Thermoelectric Energy Harvesting System

**Authors:** Guangxi Wu, Ferin Neff, and Xiong (Bill) Yu  
**Publication:** Earth and Space 2018, ASCE  
**Pages:** 1203–1215

## Abstract
Thermoelectric energy harvesting is promising to provide sustainable energy source in the extraterrestrial environment. This paper describes procedures incurred in the fabrication of thermoelectric energy harvester on flexible substrates. An electrically parallel structure is proposed, which features higher energy efficiency than the counterpart electrically series structure based on theoretical analyses. As proof of concept, flexible thermoelectric harvesters in electrically parallel and series structures are prepared with thick film printing procedures. Both analytical and experimental comparison imply a promising improvement of energy conversion efficiency by using the electrically parallel structure.

## Introduction
Thermoelectric modules (TEMs) used as generators (TEGs) provide continuous energy for extraterrestrial explorations where sunlight is insufficient (e.g., Mars at 45% solar brightness, Jupiter at 4%). While Radioisotope Thermoelectric Generators (RTGs) are reliable, they suffer from low efficiency. This paper proposes leveraging naturally existing temperature gradients on spacecraft or extraterrestrial vehicle bodies—ranging from -153°C to 123°C on the Moon—by covering surfaces with flexible TEGs.

## Electrically Parallel TEM Efficiency
The paper argues that conventional electrically series structures suffer from material property mismatches between p-type and n-type legs, which impairs the module’s figure-of-merit ($ZT_{module}$). 

### Key Equations
- **Maximum Efficiency ($\eta_{max}$):** 
  $$\eta_{max} = \frac{T_H - T_C}{T_H} \cdot \frac{\sqrt{1 + Z\overline{T}_{module}} - 1}{\sqrt{1 + Z\overline{T}_{module}} + \frac{T_C}{T_H}}$$
- **Parallel Structure Advantage:** By using the same type of material (all p-type or all n-type) in a parallel configuration, the potential of the material is not wasted by the mismatch between two different material types. This can increase efficiency by approximately 32% for standard $Bi_2Te_3$ materials.

## Fabrication Process
The study utilizes **Thick Film Printing Technology**:
1.  **Material Preparation:** $Bi_2Te_3$ (n-type and p-type) powders are ball-milled into nanocomposites to increase $ZT$ by enhancing grain boundary scattering.
2.  **TE Ink Preparation:** Ground powder is mixed with an epoxy matrix (EPON Resin 863) at a ratio of 4.5:1.
3.  **Printing:** 
    - **Substrate:** Polyimide (Kapton), chosen for thermal stability.
    - **Electrodes:** Commercial gold ink (Ercon E4464) printed via mesh screens.
    - **Deposition:** Stencil printing of TE legs on an MPM TF-100 Thick Film Printer in a class 10,000 clean room.
    - **Curing:** Electrodes cured at 110°C (10 mins); TE inks cured at 110°C (24 hours).

## Performance Characterization
Testing was conducted using a printed platinum resistor as a heat source and an aluminum/iced-water sink. Results indicated:
- The n-type electrically parallel structure produced higher maximum output power than the p-type counterpart.
- The parallel structure outperformed the traditional series structure in power output, confirming that the parallel configuration reduces the negative impact of internal resistance and material mismatch.

## Conclusion
The electrically parallel TEM structure is a prospective solution to improve energy conversion efficiency and simplify large-area fabrication. Future designs may move toward a sandwiched multilayered structure to further streamline production for large-scale extraterrestrial applications.