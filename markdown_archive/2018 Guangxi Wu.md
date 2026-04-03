# Fabrication of Flexible Thermoelectric Energy Harvesting System

**Authors:** Guangxi Wu; Ferin Neff; and Xiong (Bill) Yu  
**Publication:** Earth and Space 2018, ASCE

## Abstract
Thermoelectric energy harvesting is promising to provide a sustainable energy source in the extraterrestrial environment. This paper describes procedures incurred in the fabrication of thermoelectric energy harvester on flexible substrates. An electrically parallel structure is proposed, which features higher energy efficiency than the counterpart electrically series structure based on theoretical analyses. As proof of concept, flexible thermoelectric harvesters in electrically parallel and series structures are prepared with thick film printing procedures. The performance of elements and device with different architectures are characterized. Both analytical and experimental comparison imply a promising improvement of energy conversion efficiency by using the electrically parallel structure.

## Introduction
Thermoelectric modules (TEMs) used as generators (TEGs) provide continuous energy for extraterrestrial explorations where sunlight is insufficient. For example, solar brightness on Mars and Jupiter is only 45% and 4% of Earth's, respectively. While Radioisotope Thermoelectric Generators (RTGs) have been used for decades, they suffer from low conversion efficiency. This paper suggests leveraging the ubiquitous temperature gradients on spacecraft or planetary vehicle bodies (e.g., Mars ranges from 20°C to -73°C; the Moon ranges from 123°C to -153°C) by covering surfaces with flexible TEGs.

## Electrically Series vs. Parallel Efficiency
### Electrically Series
Conventionally, TEMs connect p-legs and n-legs in series. The maximum efficiency is defined by:

$$\eta_{max} = \frac{T_H - T_C}{T_H} \cdot \frac{\sqrt{1 + Z\bar{T}_{module}} - 1}{\sqrt{1 + Z\bar{T}_{module}} + \frac{T_C}{T_H}}$$

Where $ZT_{module}$ is the dimensionless figure-of-merit. Mismatches between p-type and n-type material properties (resistivity, thermal conductivity, Seebeck coefficient) often impair this figure-of-merit.

### Electrically Parallel
This paper proposes an alternative structure where legs are connected in parallel both thermally and electrically. This allows using only the most efficient type of material (either p-type or n-type) for both legs, eliminating the mismatch loss. Theoretical analysis suggests an efficiency increase of approximately 32% using standard materials like Bismuth Telluride ($Bi_2Te_3$).

## Fabrication Process
Flexible TEMs were fabricated using **thick film printing technology**:

1.  **Material Preparation:** $Bi_2Te_3$ (n-type and p-type) was ball-milled to create a nanocomposite powder to increase $ZT$ through grain boundary scattering.
2.  **TE Ink Preparation:** Ground powder was mixed with an epoxy matrix system (EPON Resin 863, MHHPA hardener, and AC-8 catalyst) at a 4.5:1 ratio.
3.  **Printing:** 
    *   Substrate: Flexible polyimide.
    *   Electrodes: Commercial gold ink printed via mesh screens.
    *   TE Legs: Printed via stainless steel stencils.
4.  **Curing:** Gold electrodes cured at 110°C for 10 min; TE inks cured at 110°C for 24 hours.

## Experimental Results
Performance was characterized using a printed platinum resistor as a heat source and an aluminum/ice water heat sink. 

*   **I-V and W-V Curves:** The n-type electrically parallel structure exhibited higher open-circuit voltage and maximum power output compared to the p-type parallel and the conventional series structure.
*   **Power Output:** Experimental results confirmed that parallel structures improved the figure-of-merit by utilizing the material with superior properties without being limited by a mismatched partner material.

## Conclusion
Electrically parallel TEMs are a prospective solution for improving energy conversion efficiency and simplifying the fabrication of large-area energy harvesting skins for space applications. Future developments suggest a sandwiched multilayered structure for streamlined production.