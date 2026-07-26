# In-depth analysis of sintering, exposure time, and layer height (um) in LRS 3D printed devices with DLP

## Abstract
This study evaluates the mechanical properties of Lunar Regolith Simulant (LRS) components printed using vat photopolymerization (DLP). It investigates the impact of layer height ($L_H$ 10–60 μm), exposure time ($E_T$ 3000–11,000 ms), and sintering temperature (1075–1090 °C). Using a 55% volume suspension of LRS, the study achieved a maximum compressive strength of 330 MPa and flexural strength of 100 MPa at 1085 °C.

## Introduction
In-situ resource utilization (ISRU) and in-situ fabrication and repair (ISFR) are critical for sustainable lunar presence. Lunar regolith is the most abundant material for such purposes. Additive manufacturing (AM) techniques like DLP offer high precision for miniature components and equipment.

## Experimental
- **Material:** CLRS-2 (Lunar Regolith Simulant), basaltic, low-titanium (Apollo 14 model).
- **Slurry:** 55 vol% LRS, HDDA (bifunctional resin), TMP3EOTA (trifunctional resin), TPO (photoinitiator).
- **Printing:** Ceramatrix (Spaceworks, China) DLP printer, 405 nm peak wavelength, 50 μm pixel size.
- **Sintering:** Air atmosphere; Debinding at 200/425/600 °C; Sintering at various temperatures up to 1090 °C.

### Table 1: Sintering Furnace Specifications
| Feature | Specification |
| :--- | :--- |
| Standard Temp | 1600 °C |
| Max Temp | 1700 °C |
| Heating Rate | 0–20 °C/min |
| Controller | PID with 30 segments |

## Results and Discussion
- **Rheology:** 55% solid content shows shear-thinning behavior, suitable for layer printing.
- **Particle Size:** Grinding reduced $d_{50}$ from 88.2 μm to 7.62 μm.
- **Green Body Strength:** Increased with higher $E_T$ (max at 11,000 ms) and lower $L_H$ (optimum at 30 μm).
- **Sintering:** Optimal temperature is 1085 °C. Higher temperatures cause warping or degradation.
- **Fast Sintering:** Higher rates (1–3 °C/min) improved densification and mechanical strength compared to slow rates.

### Table 2: Dimensional Shrinkage (Rod & Block)
| Parameter | Rod (X/Y/Z) | Block (X/Y/Z) |
| :--- | :--- | :--- |
| Green Body (mm) | 39.67 / 3.97 / 3.11 | 12.54 / 5.10 / 5.03 |
| 1085 °C Sintered (mm) | 35.17 / 3.52 / 2.64 | 11.14 / 4.45 / 4.39 |

## Conclusion
The study confirms that 55 vol% LRS slurry can be printed with high accuracy. Optimized parameters ($L_H$ 30 μm, $E_T$ 11,000 ms, Sintering 1085 °C) yield robust ceramic-like structures for lunar infrastructure.