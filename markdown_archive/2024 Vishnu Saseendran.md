# Unlocking the potential: analyzing 3D microstructure of small-scale cement samples from space using deep learning

**Authors:** Vishnu Saseendran, Namiko Yamamoto, Peter J. Collins, Aleksandra Radlińska, Sara Mueller, Enrique M. Jackson
**Journal:** npj Microgravity (2024) 10:11
**DOI:** [https://doi.org/10.1038/s41526-024-00349-9](https://doi.org/10.1038/s41526-024-00349-9)

## Abstract
Due to the prohibitive cost of transporting raw materials into Space, in-situ materials along with cement-like binders are poised to be employed for extraterrestrial construction. A unique methodology for obtaining microstructural topology of cement samples hydrated in microgravity environment at the International Space Station (ISS) is presented here. Distinctive Scanning Electron Microscopy (SEM) micrographs of hardened tri-calcium silicate (C3S) samples were used as exemplars in a deep learning-based microstructure reconstruction framework. The hydrated space-returned samples exhibited higher porosity content (~70 %) with the portlandite phase assuming an elongated plate-like morphology. The reconstructed volumes captured the unique microstructural morphology of the hardened C3S samples of both space-returned and ground-based samples, and can be directly employed as Representative Volume Element (RVE) to characterize mechanical/transport properties.

## Introduction
With the advent of crewed missions as part of the Artemis program, interests are being renewed to sustainably prolong human space expeditions. This requires infrastructure on extraterrestrial bodies to protect both humans and equipment from extreme environments. Given the cost of transporting materials, it is envisioned that in-situ resources such as lunar regolith formed into cement-like binders can be employed for construction. However, there is very little understanding of the hydration of cement-like binders in space.

## Methods

### Process Parameters
- **Material:** Tricalcium silicate (C3S) [Ca3SiO5].
- **Mix Ratio:** Water-to-cement (w/c) ratio of 2.0 by mass (5g C3S, 10g lime-water).
- **Environment:** Samples mixed and hydrated aboard the ISS for 42 days (microgravity, 1 ATM, 20±2°C, 35% humidity) and on ground (1g).

### Characterization
- **2D Imaging:** BSE micrographs (FEI Q250) at 500x magnification.
- **3D Imaging:** Micro-CT (Zeiss Xradia 620 Versa).
- **Reconstruction:** Deep learning-based Solid Texture Synthesis (STS) using the VGG-19 architecture to generate 3D volumes from 2D SEM exemplars.

## Results and Discussion

### Phase Composition and Porosity
| Property | Ground (1g) | Microgravity (µg) |
| :--- | :--- | :--- |
| Porosity (%) | 47.0 ± 14.2 | 70.3 ± 1.4 |
| Porosity - MIP | 48.4 | 69.4 |
| C-S-H (%) | 41.6 ± 12.0 | 21.2 ± 1.2 |
| CH (%) | 11.3 ± 2.8 | 8.5 ± 1.4 |

### Microstructural Observations
- **Ground Samples:** Portlandite (CH) crystals are uniformly distributed in the C-S-H matrix.
- **Space Samples:** CH crystals assumed an elongated plate-like morphology due to the absence of directional force (gravity).
- **Reconstruction:** The AI-assisted framework successfully captured the high porosity and unique phase growth of space samples, creating Representative Volume Elements (RVEs) for numerical modeling.

## Conclusions
The methodology presented fills the gap in computational modeling of space-cured materials where sample size is limited. Reconstructed volumes successfully captured randomly oriented elongated plate-like morphology of the portlandite phase in space-cured samples. These can be utilized in micromechanical-based codes for mechanical characterization and long-term durability studies of extraterrestrial structures.