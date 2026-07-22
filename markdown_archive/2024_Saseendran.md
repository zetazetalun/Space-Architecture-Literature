# Unlocking the potential: analyzing 3D microstructure of small-scale cement samples from space using deep learning

**Authors:** Vishnu Saseendran, Namiko Yamamoto, Peter J. Collins, Aleksandra Radlińska, Sara Mueller, and Enrique M. Jackson
**Journal:** npj Microgravity (2024) 10:11
**DOI:** https://doi.org/10.1038/s41526-024-00349-9

## Abstract
Due to the prohibitive cost of transporting raw materials into Space, in-situ materials along with cement-like binders are poised to be employed for extraterrestrial construction. A unique methodology for obtaining microstructural topology of cement samples hydrated in microgravity environment at the International Space Station (ISS) is presented here. The hydrated space-returned samples had exhibited higher porosity content (~70 %) with the portlandite phase assuming an elongated plate-like morphology.

## Introduction
Infrastructure on extraterrestrial bodies is required to protect both humans and equipment from extreme environments. It is envisioned that in-situ resources such as lunar regolith formed into cement-like binders can be employed for constructing habitats. However, there is very little understanding of the hydration of cement-like binders in space. Tricalcium silicate (C3S) constitutes ~50–70 % of Ordinary Portland Cement (OPC) and governs its hydration.

## Results and Discussion

### Image Analysis of 2D Exemplars
The study discerned C3S hydration products: calcium silicate hydrate (C-S-H), portlandite (CH), and porosity in both space-returned and ground-based samples. 

**Table 1: Summary of individual phase composition (%) of hydration products and porosity.**

| Phase | Ground (1g) | Microgravity (μg) |
| :--- | :--- | :--- |
| Porosity | 47.0 ± 14.2 | 70.3 ± 1.4 |
| Porosity - MIP | 48.4 | 69.4 |
| C-S-H | 41.6 ± 12.0 | 21.2 ± 1.2 |
| CH (Portlandite) | 11.3 ± 2.8 | 8.5 ± 1.4 |

### Microstructure Comparison
- **Ground Samples (1g):** CH crystals are uniformly distributed in the C-S-H matrix.
- **Space Samples (μg):** Due to the lack of directional force (buoyancy/sedimentation), the CH assumed an elongated plate-like morphology and significantly higher total porosity (~70% vs ~47%).

### Microstructure Reconstruction
A deep learning-based texture synthesis architecture (utilizing VGG-19) was used to generate 3D Representative Volume Elements (RVEs) from sparse 2D SEM images. The reconstructed volumes captured the unique microstructural morphology of the space-returned samples and were validated against micro-CT data.

## Conclusions
The synthesized 3D microstructures successfully captured randomly oriented elongated plate-like morphology of the portlandite phase contained in space-cured samples. The methodology fills a gap in generating RVEs to investigate process-structure-property linkages of space-cured material systems without the need for extensive 3D scanning.