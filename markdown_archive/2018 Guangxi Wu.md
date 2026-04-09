# Fabrication of Flexible Thermoelectric Energy Harvesting System

**Guangxi Wu¹; Ferin Neff²; and Xiong (Bill) Yu³**
¹Graduate Assistant, Dept. of Electrical Engineering and Computer Science, Case Western Reserve Univ. E-mail: gxw94@case.edu
²Undergraduate Assistant, Dept. of Civil Engineering, Case Western Reserve Univ. E-mail: fyn2@case.edu
³Professor, Dept. of Civil Engineering, Dept. of Electrical Engineering and Computer Science (Courtesy Appointment), Dept. of Mechanical and Aerospace Engineering (Courtesy Appointment), Case Western Reserve Univ. E-mail: xxy21@case.edu

## ABSTRACT
Thermoelectric energy harvesting is promising to provide sustainable energy source in the extraterrestrial environment. This paper describes procedures incurred in the fabrication of thermoelectric energy harvester on flexible substrates. An electrically parallel structure is proposed, which features higher energy efficiency than the counterpart electrically series structure based on theoretical analyses. As proof of concept, flexible thermoelectric harvesters in electrically parallel and series structures are prepared with thick film printing procedures. The performance of elements and device with different architectures are characterized. Both analytical and experimental comparison imply a promising improvement of energy conversion efficiency by using the electrically parallel structure.

## INTRODUCTION
Thermoelectric modules (TEMs) when used as generators (TEGs) are capable of providing continuous energy for extraterrestrial explorations, where sun light is not always available or intense enough for solar cells to work. For example, the solar brightness on Mars and Jupiter is as weak as 45% and 4%, respectively. TEGs driven by the decay of radioactive materials (RTGs) have received interest due to reliability. However, the naturally existing temperature gradients on spacecraft or extraterrestrial vehicles (e.g., Mars day/night 20°C to -73°C; Moon 123°C to -153°C) have not been effectively leveraged. If surfaces can be covered by TEGs, energy provision will be significantly boosted.

## ELECTRICALLY SERIES vs PARALLEL EFFICIENCY
Conventionally, TEMs are connected in series both electrically and thermally. The maximum energy efficiency is defined by the module's dimensionless figure-of-merit ($ZT_{module}$):

$$\eta_{max} = \frac{T_H - T_C}{T_H} \cdot \frac{\sqrt{1 + \overline{ZT}_{module}} - 1}{\sqrt{1 + \overline{ZT}_{module}} + \frac{T_C}{T_H}}$$

Where material mismatch between p-type and n-type legs reduces efficiency. The paper proposes an alternative TEM structure where legs are connected in parallel both thermally and electrically, made from the same type of TE material to keep polarity. This allows the module's figure-of-merit to match the material with the higher performance, preventing efficiency waste due to material mismatch (up to 32% improvement theorized).

## TEM FABRICATION PROCESS USING FILM PRINTING TECHNOLOGY

### Material Preparation
- **Material:** Bismuth Telluride ($Bi_2Te_3$) for both n-type and p-type.
- **Process:** Ball milling with a tube driver (mass ratio 10:1 between stainless steel balls and TE powder) in Isopropanol (IPA).
- **Sieving:** 200 mesh copper sieve (max grain size 76 microns).

### TE Ink Preparation
- **Binder:** Epoxy matrix (EPON Resin 863, MHHPA hardener, AC-8 catalyst).
- **Ratio:** TE powder-to-epoxy ratio of 4.5:1.

### Printing Process
- **Equipment:** MPM TF-100 Thick Film Printer.
- **Substrate:** Polyimide (Kapton).
- **Curing:** Electrodes (Gold ink) cured at 110°C for 10 min; TE inks cured at 110°C for 24 hours.

## TABLE 1: Material properties of a pair of thermoelectric materials (Bi2Te3)

| Material | Electrical Resistivity $\rho$ ($m\Omega\cdot cm$) | Seebeck Coefficient $\alpha$ ($\mu V/K$) | Thermal Conductivity $\kappa$ ($W/(cm\cdot K)$) | Material figure-of-merit $ZT_{material}$ at 300K |
| :--- | :--- | :--- | :--- | :--- |
| $Bi_2Te_3$ (p) | 0.83 | 156.57 | 2.09 x 10⁻² | 0.42 |
| $Bi_2Te_3$ (n) | 0.73 | -193.00 | 2.04 x 10⁻² | 0.74 |

## CONCLUSION
This study proposes an electrically parallel TEM structure to improve output power. Flexible TEMs were fabricated using thick-film printing and characterized. Results comply with analytical models showing the parallel structure is promising for large-area implementation on extraterrestrial vehicles and structures.