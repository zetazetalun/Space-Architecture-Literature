# Fabrication of Flexible Thermoelectric Energy Harvesting System

**Authors:** Guangxi Wu, Ferin Neff, and Xiong (Bill) Yu  
**Publication:** Earth and Space 2018, ASCE  

## Abstract
Thermoelectric energy harvesting is promising to provide sustainable energy source in the extraterrestrial environment. This paper describes procedures incurred in the fabrication of thermoelectric energy harvester on flexible substrates. An electrically parallel structure is proposed, which features higher energy efficiency than the counterpart electrically series structure based on theoretical analyses. As proof of concept, flexible thermoelectric harvesters in electrically parallel and series structures are prepared with thick film printing procedures. Both analytical and experimental comparison imply a promising improvement of energy conversion efficiency by using the electrically parallel structure.

## Introduction
Thermoelectric modules (TEMs) used as generators (TEGs) provide continuous energy for extraterrestrial explorations where sunlight is insufficient (e.g., Mars at 45% solar brightness, Jupiter at 4%). While radioisotope thermoelectric generators (RTGs) are reliable, they suffer from low conversion efficiency. This research proposes leveraging the naturally existing temperature gradients on spacecraft or extraterrestrial vehicle bodies (e.g., Mars surface temperature shifts from 20°C to -73°C) by covering surfaces with flexible TEGs.

## Technical Analysis: Series vs. Parallel Structures

### Electrically Series TEM Efficiency
Conventionally, TEMs connect p-legs and n-legs in series. The maximum efficiency $\eta_{max}$ is defined by the figure-of-merit ($ZT_{module}$):

$$\eta_{max} = \frac{T_H - T_C}{T_H} \cdot \frac{\sqrt{1 + ZT_{module}} - 1}{\sqrt{1 + ZT_{module}} + \frac{T_C}{T_H}}$$

Where property mismatch between p-type and n-type materials reduces the effective $ZT_{module}$. For Bismuth Telluride ($Bi_2Te_3$), mismatch can waste up to 24% of the material's potential.

### Electrically Parallel TEM Efficiency
The proposed parallel structure allows legs to be made of the same material type (p-type or n-type) to maintain polarity. Analytical results suggest that the parallel structure allows the module's figure-of-merit to reach the maximum value of the superior material, potentially increasing efficiency by 32% compared to mismatched series modules.

## Fabrication Process

### 1. Material Preparation
- **Material:** $Bi_2Te_3$ (n-type and p-type).
- **Process:** Ball milling to create nanocomposites to increase $ZT$ by limiting phonon transport via grain boundary scattering.
- **Grinding:** Isopropanol (IPA) agent, rotation speeds up to 6000 rpm.

### 2. TE Ink Preparation
- **Binder:** Epoxy matrix (EPON Resin 863, MHHPA hardener, AC-8 catalyst).
- **Ratio:** 4.5:1 powder-to-epoxy ratio for optimal viscosity.

### 3. Printing Process
- **Substrate:** Polyimide (thermally stable).
- **Equipment:** MPM TF-100 Thick Film Printer in a class 10,000 clean room.
- **Method:** Stencil printing of gold electrodes (Ercon E4464) followed by TE legs. Curing at 110°C.

## Results and Characterization
Experimental testing using a platinum resistor heat source and iced-water heat sink ($50^{\circ}C$ gradient) showed:
- **n-type Parallel TEM:** Highest maximum power output.
- **p-type Parallel TEM:** Lower output than n-type due to material property differences.
- **Series TEM:** Suffered from high inner resistance, leading to underestimated voltage and lower output power than n-type parallel counterparts.

## Conclusion
The electrically parallel TEM structure improves output power by mitigating material mismatch. Flexible TEMs were successfully fabricated using thick-film printing. While the current "roll-up" method is for testing, a sandwiched multilayered structure is proposed for large-area production to simplify implementation on extraterrestrial structures.