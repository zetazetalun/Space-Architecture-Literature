# Unlocking the potential: analyzing 3D microstructure of small-scale cement samples from space using deep learning

**Authors:** Vishnu Saseendran, Namiko Yamamoto, Peter J. Collins, Aleksandra Radlińska, Sara Mueller, Enrique M. Jackson
**Journal:** npj Microgravity (2024) 10:11
**DOI:** 10.1038/s41526-024-00349-9

## Abstract
Due to the prohibitive cost of transporting raw materials into Space, in-situ materials along with cement-like binders are poised to be employed for extraterrestrial construction. A unique methodology for obtaining microstructural topology of cement samples hydrated in microgravity environment at the International Space Station (ISS) is presented here. Scanning Electron Microscopy (SEM) micrographs of hardened tri-calcium silicate (C3S) samples were used in a deep learning-based microstructure reconstruction framework. The hydrated space-returned samples exhibited higher porosity content (~70%) with the portlandite phase assuming an elongated plate-like morphology.

## Introduction
Infrastructure on extraterrestrial bodies is required to protect humans and equipment from extreme environments. In-situ resources such as lunar regolith combined with cement-like binders are envisioned for constructing these habitats. Understanding the hydration of cement-like binders in microgravity is critical for evaluating the resulting mechanical properties.

## Methods
- **Material:** Tricalcium silicate (C3S) mixed with lime-water (w/c ratio 2.0 by mass).
- **Environment:** Samples hydrated for 42 days onboard the ISS (microgravity) and on Earth (1g).
- **Analysis:** Backscattered Electron (BSE) micrographs (SEM) were used as 2D exemplars.
- **Reconstruction:** A Solid Texture Synthesis (STS) deep learning framework using VGG-19 was employed to generate 3D Representative Volume Elements (RVEs).

## Results and Discussion
| Phase Composition | Ground (1g) [%] | Microgravity (μg) [%] |
| :--- | :--- | :--- |
| Porosity | 47.0 ± 14.2 | 70.3 ± 1.4 |
| C-S-H | 41.6 ± 12.0 | 21.2 ± 1.2 |
| Portlandite (CH) | 11.3 ± 2.8 | 8.5 ± 1.4 |

### Key Observations
- **Porosity Difference:** Microgravity samples exhibited significantly higher porosity (~70%) compared to Earth samples (~47%).
- **Crystal Morphology:** Portlandite (CH) crystals in microgravity assumed an elongated plate-like morphology due to the lack of directional forces, whereas they were uniformly distributed in 1g samples.
- **Validation:** The AI-reconstructed 3D volumes were statistically consistent with experimental data and micro-CT scans.

## Conclusion
The study provides an AI-assisted framework to quantitatively characterize 3D microstructures of materials when experimental data is sparse. This is vital for space architecture to establish process-microstructure-property linkages for ISRU construction materials.