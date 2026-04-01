# Fabrication of Flexible Thermoelectric Energy Harvesting System

**Authors:** Guangxi Wu, Ferin Neff, and Xiong (Bill) Yu
**Source:** Earth and Space 2018, ASCE, pp. 1203-1215

## Abstract
Thermoelectric energy harvesting is promising to provide a sustainable energy source in the extraterrestrial environment. This paper describes procedures incurred in the fabrication of thermoelectric energy harvester on flexible substrates. An electrically parallel structure is proposed, which features higher energy efficiency than the counterpart electrically series structure based on theoretical analyses. As proof of concept, flexible thermoelectric harvesters in electrically parallel and series structures are prepared with thick film printing procedures. Both analytical and experimental comparison imply a promising improvement of energy conversion efficiency by using the electrically parallel structure.

## Introduction
Thermoelectric modules (TEMs) used as generators (TEGs) provide continuous energy for extraterrestrial explorations where sunlight is insufficient (e.g., Mars at 45% solar brightness, Jupiter at 4%). Radioisotope Thermoelectric Generators (RTGs) are favored for reliability, being solid-state, noise-free, and radiation-resistant. The paper suggests leveraging the extreme temperature gradients on spacecraft or planetary surfaces (e.g., Mars: 20°C to -73°C; Moon: 123°C to -153°C) by covering surfaces with flexible TEGs.

## Electrically Series vs. Parallel TEM Efficiency
Conventionally, TEMs use p-legs and n-legs connected in series. The maximum efficiency (η_max) is governed by the figure-of-merit (ZT_module). Material property mismatches (Seebeck coefficient, resistivity, thermal conductivity) between p-type and n-type materials often lead to an attenuation factor (A) that impairs the module's performance.

### Table 1. Material properties of a pair of thermoelectric materials (Bi2Te3) at 300K
| Material | Electrical Resistivity ρ (mΩ·cm) | Seebeck Coefficient α (μV/K) | Thermal Conductivity κ W/(cm·K) | Material figure-of-merit ZT_material |
| :--- | :--- | :--- | :--- | :--- |
| Bi2Te3 (p) | 0.83 | 156.57 | 2.09×10⁻² | 0.42 |
| Bi2Te3 (n) | 0.73 | -193.00 | 2.04×10⁻² | 0.74 |

The paper proposes an **electrically parallel TEM structure** where legs are made from the same type of material (all p-type or all n-type). Analytical derivation shows that in a parallel structure, the module's ZT can reach the maximum value of the superior material, avoiding the mismatch waste inherent in series structures.

## TEM Fabrication Process
1. **Material Preparation:** Bi2Te3 (p-type and n-type) powders were processed via ball milling to create nanocomposites, increasing ZT through grain boundary scattering.
2. **TE Ink Preparation:** Ground powders were mixed with an epoxy matrix (EPON Resin 863, MHHPA, and AC-8 catalyst) at a ratio of 4.5:1.
3. **Screen and Stencil Design:** Mesh screens were used for gold electrode printing (Ercon E4464 ink) and stainless steel stencils for TE legs.
4. **Printing Process:** Layers were printed on flexible polyimide substrates using an MPM TF-100 Thick Film Printer and cured at temperatures ranging from 110°C to 150°C.

## Performance Characterization
The experimental setup utilized a platinum resistor heat source on a ceramic substrate and an aluminum heat sink in iced water (0°C). A trans-impedance amplifier monitored I-V and W-V curves. Results confirmed that the maximum output power of n-type electrically parallel TEMs was higher than the series counterparts, validating the analytical model.

## Conclusion
Electrically parallel TEMs are a prospective solution for extraterrestrial energy harvesting, offering both improved conversion efficiency and simplified fabrication for large-area implementation on flexible spacecraft skins or habitat surfaces.