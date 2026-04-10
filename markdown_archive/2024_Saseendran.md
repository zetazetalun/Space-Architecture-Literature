# Unlocking the potential: analyzing 3D microstructure of small-scale cement samples from space using deep learning

**Authors:** Vishnu Saseendran, Namiko Yamamoto, Peter J. Collins, Aleksandra Radlińska, Sara Mueller and Enrique M. Jackson
**Journal:** npj Microgravity (2024) 10:11
**DOI:** https://doi.org/10.1038/s41526-024-00349-9

## Abstract
Due to the prohibitive cost of transporting raw materials into Space, in-situ materials along with cement-like binders are poised to be employed for extraterrestrial construction. A unique methodology for obtaining microstructural topology of cement samples hydrated in microgravity environment at the International Space Station (ISS) is presented here. Distinctive Scanning Electron Microscopy (SEM) micrographs of hardened tri-calcium silicate (C3S) samples were used as exemplars in a deep learning-based microstructure reconstruction framework. The hydrated space-returned samples had exhibited higher porosity content (~70 %) with the portlandite phase assuming an elongated plate-like morphology. Detailed assessment of the reconstructed volumes captured the unique microstructural morphology of the hardened C3S samples of both space-returned and ground-based samples, and can be directly employed as Representative Volume Element (RVE) to characterize mechanical/transport properties.

## Introduction
Infrastructure on extraterrestrial bodies is required to protect both humans and equipment from extreme environments. In-situ resources such as lunar regolith formed into cement-like binders are envisioned for constructing habitats. However, there is very little understanding on the hydration of cement-like binders in space. Tricalcium silicate (C3S) [Ca3SiO5] constitutes ~50–70% of Ordinary Portland Cement (OPC) by mass and governs the hydration process. Due to size limitations and high porosity of space-returned samples, conventional experimental characterization techniques like Micro-CT have limitations, necessitating numerical modeling based on accurate 3D representations.

## Methods
- **Process Parameters:** Mixture of C3S and lime-water at a water-to-cement (w/c) ratio of 2.0. Experiments conducted aboard the ISS (microgravity, μg) and on ground (1g) at 20 ± 2 °C and 1 ATM.
- **Microscope Observations:** Backscattered Electron (BSE) micrographs obtained using FEI Q250 at 500x magnification. Image resolution of 0.54 μm.
- **Micro-CT Analysis:** Acquired using a Zeiss Xradia 620 Versa X-ray Microscope for 3D verification.
- **Deep Learning Reconstruction:** A CNN-based Solid Texture Synthesis (STS) framework using a pre-trained VGG-19 descriptor was employed to generate 3D virtual volumes from 2D BSE images.

## Results and Discussion

### Table 1: Summary of individual phase composition (%) of hydration products and porosity per image analysis (±SD) of 1g and μg samples

| Phase | Ground (1g) | Microgravity (μg) |
| :--- | :--- | :--- |
| Porosity (%) | 47.0 ± 14.2 | 70.3 ± 1.4 |
| Porosity - MIP [2] (%) | 48.4 | 69.4 |
| C-S-H (%) | 41.6 ± 12.0 | 21.2 ± 1.2 |
| CH (Portlandite) (%) | 11.3 ± 2.8 | 8.5 ± 1.4 |

### Microstructural Findings
- **Porosity:** Microgravity samples exhibited ~70% porosity, significantly higher than the ~47% found in Earth-based samples.
- **Morphology:** Portlandite (CH) crystals in 1g samples were uniformly distributed, while in μg samples, they assumed an elongated plate-like morphology due to the lack of buoyancy-driven convection.
- **Reconstruction:** The deep learning model successfully captured the anisotropic phase growth and spatial distribution of porosity, creating statistically equivalent Representative Volume Elements (RVEs) validated against Micro-CT data.

## Conclusion
The methodology presented allows for the creation of high-fidelity 3D microstructural models of cementitious materials hydrated in space using sparse 2D data. These models are vital for predicting the mechanical and transport properties of structures built using in-situ resources in extraterrestrial environments.