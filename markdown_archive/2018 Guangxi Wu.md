# Fabrication of Flexible Thermoelectric Energy Harvesting System

**Authors:** Guangxi Wu, Ferin Neff, and Xiong (Bill) Yu
**Source:** Earth and Space 2018, pp. 1203-1215
**Publisher:** © ASCE

## Abstract
Thermoelectric energy harvesting is promising to provide sustainable energy source in the extraterrestrial environment. This paper describes procedures incurred in the fabrication of thermoelectric energy harvester on flexible substrates. An electrically parallel structure is proposed, which features higher energy efficiency than the counterpart electrically series structure based on theoretical analyses. As proof of concept, flexible thermoelectric harvesters in electrically parallel and series structures are prepared with thick film printing procedures. The performance of elements and device with different architectures are characterized. Both analytical and experimental comparison imply a promising improvement of energy conversion efficiency by using the electrically parallel structure.

## Introduction
Thermoelectric modules (TEMs) used as generators (TEGs) provide continuous energy where sunlight is limited (e.g., Mars at 45% solar brightness, Jupiter at 4%). Traditional Radioisotope Thermoelectric Generators (RTGs) are reliable but suffer from low conversion efficiency. This paper suggests leveraging the extreme temperature gradients on planetary surfaces (e.g., Mars: 20°C to -73°C; Moon: 123°C to -153°C) by covering spacecraft or habitat surfaces with flexible TEGs.

## Electrically Series vs. Parallel Structures

### Series Efficiency
Conventionally, TEMs use alternating p-legs and n-legs connected in series. The maximum efficiency is defined by the dimensionless figure-of-merit ($ZT_{module}$):

$$ZT_{module} = \frac{(\alpha_p - \alpha_n)^2 \bar{T}}{(\sqrt{\kappa_p \rho_p} + \sqrt{\kappa_n \rho_n})^2}$$

Mismatched properties between p-type and n-type materials (common in organic and nanostructured materials) significantly impair $ZT_{module}$. For $Bi_2Te_3$ at 300K, an attenuation factor of 0.76 is observed due to mismatch.

### Parallel Efficiency
The paper proposes an electrically parallel TEM where legs are of the same material type (all p-type or all n-type). This allows the module's $ZT$ to match the $ZT$ of the superior material, preventing the 'waste' of potential from the higher-performing material.

## Fabrication Process

### Material Preparation
- **Material:** $Bi_2Te_3$ (n-type and p-type).
- **Process:** Ball milling (2200 to 6000 rpm) to create nanocomposites, increasing $ZT$ by limiting phonon transport through grain boundary scattering.
- **Particle Size:** Limited to 76 microns via 200 mesh filtering.

### Ink Preparation
- **Matrix:** Epoxy system (EPON Resin 863, MHHPA hardener, AC-8 catalyst).
- **Ratio:** TE powder-to-epoxy ratio of 4.5:1.

### Printing Sequence
1. **Substrate:** Flexible polyimide.
2. **Electrodes:** Stencil printed commercial gold ink (Ercon E4464), cured at 110°C.
3. **TE Legs:** Printed using left-leg and right-leg stencils.
4. **Curing:** 110°C for 24 hours.
5. **Assembly:** Rolled up into final TEM form.

## Results and Characterization
Testing under a 50°C temperature gradient showed:
- **Open-circuit Voltage:** n-type parallel structure was higher than p-type parallel.
- **Output Power:** The maximum output power of the n-type parallel structure exceeded that of the traditional series structure, confirming that the parallel design mitigates efficiency losses from material mismatch.

## Conclusion
The electrically parallel TEM structure is a prospective solution to improve energy conversion efficiency and simplify large-area fabrication. A future "sandwiched" multilayered structure is proposed for even simpler large-scale implementation.