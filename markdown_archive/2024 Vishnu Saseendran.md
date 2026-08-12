# Unlocking the potential: analyzing 3D microstructure of small-scale cement samples from space using deep learning

**Authors:** Vishnu Saseendran, Namiko Yamamoto, Peter J. Collins, Aleksandra Radlińska, Sara Mueller, Enrique M. Jackson

**Journal:** npj Microgravity (2024) 10:11
**DOI:** https://doi.org/10.1038/s41526-024-00349-9

## Abstract
Due to the prohibitive cost of transporting raw materials into Space, in-situ materials along with cement-like binders are poised to be employed for extraterrestrial construction. A unique methodology for obtaining microstructural topology of cement samples hydrated in microgravity environment at the International Space Station (ISS) is presented here. Scanning Electron Microscopy (SEM) micrographs of hardened tri-calcium silicate (C3S) samples were used in a deep learning-based microstructure reconstruction framework. The hydrated space-returned samples exhibited higher porosity content (~70%) with the portlandite phase assuming an elongated plate-like morphology. Reconstructed volumes captured unique morphologies and can be employed as Representative Volume Elements (RVE) to characterize mechanical/transport properties.

## Introduction
Infrastructure on extraterrestrial bodies is required to protect humans and equipment. In-situ resources like lunar regolith formed into cement-like binders are envisioned for construction. However, hydration in microgravity (μg) is poorly understood. Recent studies on the ISS helped understand solidification chemistry, but size limitations of space-returned samples make conventional experimental characterization difficult. Numerical modeling using 3D representations is necessary to evaluate properties.

## Methods
- **Samples:** Tricalcium silicate (C3S) mixed with lime-water (w/c ratio 2.0). 
- **Conditions:** 20 ± 2 °C, 1 ATM, 42 days hydration on ISS vs Ground (1g).
- **Imaging:** SEM (BSE) and Micro-CT.
- **Reconstruction:** Deep learning-based texture synthesis using a CNN-based (VGG-19) framework to generate 3D volumes from 2D exemplars.

## Results and Discussion

### Phase Composition
Table 1 summarizes the phase composition and porosity determined from image analysis.

| Phase | Ground (1g) (%) | Microgravity (μg) (%) |
| :--- | :--- | :--- |
| Porosity | 47.0 ± 14.2 | 70.3 ± 1.4 |
| Porosity (MIP) | 48.4 | 69.4 |
| C-S-H | 41.6 ± 12.0 | 21.2 ± 1.2 |
| CH (Portlandite) | 11.3 ± 2.8 | 8.5 ± 1.4 |

### Microstructural Observations
- **Porosity:** Significantly higher in microgravity (~70%) compared to Earth (~47%).
- **Portlandite (CH):** In 1g, CH crystals are uniformly distributed. In μg, they assume an elongated plate-like morphology due to the lack of directional forces (buoyancy/sedimentation).
- **Reconstruction:** The AI-assisted framework successfully generated statistically equivalent 3D microstructures that matched micro-CT data and captured the unique plate-like morphology of the space samples.

## Conclusion
The deep learning framework effectively reconstructs 3D models from sparse 2D data of space-returned cement. These models serve as RVEs for future micromechanics-based modeling to predict the strength and durability of ISRU-based extraterrestrial infrastructure.