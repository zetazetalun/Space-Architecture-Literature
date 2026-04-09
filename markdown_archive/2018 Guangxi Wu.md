# Fabrication of Flexible Thermoelectric Energy Harvesting System

**Authors:** Guangxi Wu, Ferin Neff, and Xiong (Bill) Yu  
**Publication:** Earth and Space 2018, ASCE  

## Abstract
Thermoelectric energy harvesting is promising for providing a sustainable energy source in extraterrestrial environments. This paper describes procedures for the fabrication of thermoelectric energy harvesters on flexible substrates. An electrically parallel structure is proposed, which features higher energy efficiency than the counterpart electrically series structure based on theoretical analyses. As a proof of concept, flexible thermoelectric harvesters in electrically parallel and series structures are prepared with thick film printing procedures. Both analytical and experimental comparisons imply a promising improvement of energy conversion efficiency by using the electrically parallel structure.

## Introduction
Thermoelectric generators (TEGs) provide continuous energy for extraterrestrial exploration where sunlight is insufficient (e.g., Mars at 45% solar brightness, Jupiter at 4%). Radioisotope thermoelectric generators (RTGs) have been reliable for 50 years but suffer from low efficiency. This research explores leveraging the naturally existing temperature gradients on spacecraft or planetary vehicle bodies (e.g., Mars surface temperatures ranging from 20°C to -73°C) by covering surfaces with flexible TEGs.

## Electrically Parallel vs. Series Structure
### Electrically Series TEM Efficiency
Conventionally, TEMs use alternating p-legs and n-legs connected in series. Mismatches in material properties (resistivity, thermal conductivity, Seebeck coefficient) between p-type and n-type materials lead to an attenuation factor ($A < 1$) in the module's figure-of-merit ($ZT_{module}$).

### Electrically Parallel TEM Efficiency
The paper proposes an alternative where legs are connected in parallel. This allows the use of the same type of material (all p-type or all n-type) for both legs of a unit, ensuring the module figure-of-merit reaches the maximum intrinsic value of the superior material. Analytical results suggest a potential efficiency increase of 32% compared to mismatched series modules.

## Fabrication Process
### Material Preparation
- **Material:** Bismuth Telluride ($Bi_2Te_3$) for both p-type and n-type.
- **Process:** Nanocomposite bulk processing emulated via ball milling (2200 to 6000 rpm) to increase $ZT$ by grain boundary scattering.
- **Ink:** TE powder mixed with epoxy resin (EPON Resin 863) at a 4.5:1 ratio.

### Printing Technology
- **Printer:** MPM TF-100 Thick Film Printer.
- **Substrate:** Flexible Polyimide.
- **Electrodes:** Commercial gold ink (Ercon E4464).
- **Curing:** Electrodes at 110°C for 10 min; TE inks at 110°C for 24 hours.

## Performance Characterization
Testing was conducted using a printed platinum resistor heat source and an aluminum/iced water heat sink (0°C). A trans-impedance amplifier was used for accurate I-V and W-V curve measurement at a 50°C temperature gradient.

| Material | Resistivity $\rho$ (mΩ·cm) | Seebeck Coefficient $\alpha$ (μV/K) | Thermal Conductivity $\kappa$ W/(cm·K) | $ZT_{material}$ at 300K |
| :--- | :--- | :--- | :--- | :--- |
| $Bi_2Te_3$ (p) | 0.83 | 156.57 | $2.09 \times 10^{-2}$ | 0.42 |
| $Bi_2Te_3$ (n) | 0.73 | -193.00 | $2.04 \times 10^{-2}$ | 0.74 |

## Conclusion
The electrically parallel structure is a prospective solution to improve energy conversion efficiency and simplify the fabrication of large-area flexible TEGs. Future implementations may utilize a sandwiched multilayered structure to further simplify production.