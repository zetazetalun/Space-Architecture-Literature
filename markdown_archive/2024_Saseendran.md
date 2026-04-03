# Unlocking the potential: analyzing 3D microstructure of small-scale cement samples from space using deep learning

**Authors:** Vishnu Saseendran, Namiko Yamamoto, Peter J. Collins, Aleksandra Radlińska, Sara Mueller, Enrique M. Jackson
**Journal:** npj Microgravity (2024) 10:11
**DOI:** https://doi.org/10.1038/s41526-024-00349-9

## Abstract
Due to the prohibitive cost of transporting raw materials into Space, in-situ materials along with cement-like binders are poised to be employed for extraterrestrial construction. A unique methodology for obtaining microstructural topology of cement samples hydrated in microgravity environment at the International Space Station (ISS) is presented here. Scanning Electron Microscopy (SEM) micrographs of hardened tri-calcium silicate (C3S) samples were used as exemplars in a deep learning-based microstructure reconstruction framework. The hydrated space-returned samples exhibited higher porosity content (~70%) with the portlandite phase assuming an elongated plate-like morphology.

## Introduction
Infrastructure on extraterrestrial bodies is required to protect humans and equipment. In-situ resources such as lunar regolith formed into cement-like binders are envisioned for construction. Tricalcium silicate (C3S) constitutes ~50–70% of Ordinary Portland Cement (OPC) and governs hydration. Due to size limitations and high porosity of space-returned samples, conventional 3D characterization like micro-CT is challenging; hence, numerical modeling and deep learning reconstruction are employed.

## Methodology
### C3S Hydration
- **Mixture:** C3S mixed with lime-water at a water-to-cement (w/c) ratio of 2.0 by mass.
- **Location:** Onboard the ISS (microgravity) and on Earth (1g).
- **Conditions:** 20 ± 2 °C, 1 ATM, 35% relative humidity.
- **Duration:** 42 days of hydration.

### Reconstruction Framework
- **Algorithm:** Convolutional Neural Networks (CNNs) using a VGG-19 descriptor.
- **Technique:** Solid Texture Synthesis (STS) to generate 3D volumes from 2D SEM images.
- **Input:** High-resolution 2D BSE micrographs (0.54 μm resolution).

## Results
### Phase Composition
| Phase | Ground (1g) (%) | Microgravity (µg) (%) |
|---|---|---|
| Porosity | 47.0 ± 14.2 | 70.3 ± 1.4 |
| Porosity - MIP | 48.4 | 69.4 |
| C-S-H | 41.6 ± 12.0 | 21.2 ± 1.2 |
| CH (Portlandite) | 11.3 ± 2.8 | 8.5 ± 1.4 |

### Key Observations
- **Microgravity Samples:** Lack of directional force led to elongated plate-like portlandite morphology.
- **Reconstruction:** The deep learning model effectively captured the unique microstructural topology of space-returned samples compared to 1g controls.
- **Validation:** Reconstructed 3D volumes were validated against micro-CT data using two-point correlation and lineal-path functions.

## Conclusion
The study provides a cost-effective method to generate virtual Representative Volume Elements (RVEs) for space-cured materials, enabling the prediction of mechanical and transport properties for extraterrestrial construction planning.