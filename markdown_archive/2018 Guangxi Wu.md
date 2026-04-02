# Fabrication of Flexible Thermoelectric Energy Harvesting System

**Authors:** Guangxi Wu¹, Ferin Neff², and Xiong (Bill) Yu³  
¹ Graduate Assistant, Dept. of Electrical Engineering and Computer Science, Case Western Reserve Univ.  
² Undergraduate Assistant, Dept. of Civil Engineering, Case Western Reserve Univ.  
³ Professor, Dept. of Civil Engineering, Dept. of Electrical Engineering and Computer Science, Case Western Reserve Univ.  

**Published in:** Earth and Space 2018 (ASCE)

## Abstract
Thermoelectric energy harvesting is promising to provide sustainable energy source in the extraterrestrial environment. This paper describes procedures incurred in the fabrication of thermoelectric energy harvester on flexible substrates. An electrically parallel structure is proposed, which features higher energy efficiency than the counterpart electrically series structure based on theoretical analyses. As proof of concept, flexible thermoelectric harvesters in electrically parallel and series structures are prepared with thick film printing procedures. The performance of elements and device with different architectures are characterized. Both analytical and experimental comparison imply a promising improvement of energy conversion efficiency by using the electrically parallel structure.

## Introduction
Thermoelectric modules (TEMs) when used as generators (TEGs) are capable of providing continuous energy for extraterrestrial explorations, where sun light is not always available or intense enough for solar cells to work. For example, the solar brightness on Mars and Jupiter is as weak as 45% and 4%, respectively. TEGs driven by the decay of suitable radioactive materials, such as radioisotope thermoelectric generators (RTGs), have received the most interest. These properties have made RTGs suitable for autonomous missions in the extreme environment of space and on planetary surfaces.

However, the naturally existing ubiquitous temperature gradient on the spacecraft or extraterrestrial vehicle body caused by common drastic temperature change in extraterrestrial environment has not been effectively leveraged. For example, a summer day on Mars may get up to 20°C near the equator, but at night the temperature can plummet to about -73°C. On the moon, the temperature can reach 123°C when sunlight hits the moon's surface. If the spacecraft or extraterrestrial vehicle body surface can be covered by TEGs, energy provided by the TEGs will be significantly boosted up.

## Electrically Series TEM Efficiency
Conventionally, a thermoelectric module (TEM) is composed of alternant p-legs and n-legs that are connected in series both electrically and thermally. The maximum possible energy efficiency is depicted as:

$$\eta_{max} = \frac{T_H - T_C}{T_H} \cdot \frac{\sqrt{1 + Z\bar{T}_{module}} - 1}{\sqrt{1 + Z\bar{T}_{module}} + \frac{T_C}{T_H}}$$

### Table 1. Material properties of a pair of thermoelectric materials (Bi2Te3).

| Material | Electrical Resistivity $\rho$ (m$\Omega \cdot$cm) | Seebeck Coefficient $\alpha$ ($\mu$V/K) | Thermal Conductivity $\kappa$ W/(cm$\cdot$K) | Material figure-of-merit $ZT_{material}$ at 300K |
| :--- | :--- | :--- | :--- | :--- |
| Bi2Te3 (p) | 0.83 | 156.57 | $2.09 \times 10^{-2}$ | 0.42 |
| Bi2Te3 (n) | 0.73 | -193.00 | $2.04 \times 10^{-2}$ | 0.74 |

## TEM Fabrication Process

### Material Preparation
The TE material used is Bi2Te3 for both n-type and p-type. Raw materials were ball milled using a tube driver (IKA ULTRA TURRAX Tube Drive). Isopropanol (IPA) was used as the grinding agent. The rotation speed was ramped up to 6000 rpm to create nanocomposite powders with grain sizes limited to 76 microns.

### TE Ink Preparation
The ground p-type and n-type powders were used as filler particles in an epoxy matrix system (EPON Resin 863, MHHPA hardener, and AC-8 catalyst). The TE powder-to-epoxy system ratio was 4.5:1 to meet viscosity requirements for printing.

### Printing Process
1. **Substrate:** Flexible polyimide (Kapton).
2. **Electrodes:** Printed using commercial gold ink (Ercon E4464) via mesh screens.
3. **TE Legs:** Printed using self-made TE inks via stainless steel stencils.
4. **Curing:** Electrodes were cured at 110°C for 10 minutes; TE legs were cured at 110°C for 24 hours.
5. **Finishing:** After printing, the device is rolled up to form the final TEM.

## Conclusion
This paper proposes an electrically parallel TEM structure to improve output power when used as TEGs. Analytical and preliminary experimental results comply, showing that the parallel structure avoids the performance loss caused by material mismatch (e.g., 32% efficiency increase in the provided example). The thick-film printing technology on flexible substrates provides a prospective solution for large-area implementation on spacecraft or planetary habitat surfaces.