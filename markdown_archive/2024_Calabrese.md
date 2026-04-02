# Computer Vision for Terrain Mapping and 3D Printing In-situ of Extra/-terrestrial Habitats

**Authors:** Giuseppe Calabrese, Arwin Hidding, Henriette Bier, Casper van Engelenburg, Seyran Khademi, and Atousa Aslaminezhad  
**Publication:** IntelliSys 2024, LNNS 1067, pp. 349–360, 2024.  
**DOI:** https://doi.org/10.1007/978-3-031-66431-1_23

## Abstract
This paper addresses the complexities inherent in constructing sustainable extraterrestrial habitats within lava tubes that are envisioned as promising locations for human habitation and scientific inquiry. These environments are characterized by various challenges, which are addressed in this case by integrating computer vision (CV) techniques and 3D printing in-situ. The CV component generates a detailed depth map from synthetic imagery to combine this depth map with an adaptive 3D printing process, which is proposed to ensure level surfaces at various depths, facilitating precise foundation and habitat placement within the demanding context of lava tubes. Significantly, synthetic imagery is employed due to the absence of real lava tube photos at this early stage of the current exploration. The focal point lies in utilizing advanced deep learning (DL) algorithms and convolutional neural networks (CNN) to generate depth maps for extra/-terrestrial environments. This research represents a platform for further knowledge development in the fields of CV and its application to 3D printing in-situ, hence opening new avenues for sustainable extraterrestrial habitats.

## 1 Introduction
The exploration and colonization of celestial bodies have long been envisioned by humankind. One of the significant challenges faced in this endeavor is the construction of habitable spaces in extraterrestrial environments, particularly within the irregular and treacherous confines of lava tubes. These natural underground spaces, prevalent on the Moon, Mars, and Earth, offer a unique opportunity for safe habitation and scientific research due to their protective nature against radiation and extreme temperatures.

## 2 Related Work
The integration of CV techniques and 3D printing for in-situ construction builds upon existing research by Bier et al. (2021) on subterranean off-Earth infrastructure and Von Ehrenfried (2022) on cave living. Geological studies by Sauro et al. (2020) provide morphological data on lava tubes used as the basis for this construction methodology.

## 3 Problem Statement
Lava tubes offer natural shielding but present uneven and rugged terrains that pose significant challenges for construction. Integrating CV with 3D printing offers a transformative approach to address these challenges by providing real-time adaptability for terrain leveling.

## 4 Implications
Precisely mapping irregularities ensures structural stability and facilitates the seamless attachment of habitable structures. This CV-supported technology developed for space applications can also be transferred to on-Earth applications in remote or disaster-stricken environments.

## 5 CV vs. LiDAR Scanning
While LiDAR is precise, CV offers several advantages in specific scenarios:
- **Real-time Analysis:** Instantaneous operation for dynamic environments.
- **Cost Efficiency:** Utilizes off-the-shelf, accessible hardware.
- **Low Power Consumption:** Cameras consume less power than laser systems.
- **Rich Data:** Provides color and texture information.

## 6 Methodology
The study employs an incremental solution approach:
1. **Synthetic Depth Map Generation:** Uses Grasshopper and Perlin noise algorithms to simulate lava tube surfaces.
2. **U-Net Deep Learning Framework:** A CNN architecture for image segmentation and depth estimation.
3. **Training:** The model was trained on 600 images across various scenarios (color, B&W, different light sources).

### Results
- **Training Accuracy:** 0.8 (80% pixel classification accuracy).
- **Validation Accuracy:** 0.5, indicating a need for more diverse training data to prevent overfitting.

## 7 Conclusion
The research demonstrates a comprehensive system capable of autonomously analyzing surface data to adapt 3D printing processes for terrain leveling. Future work includes testing in terrestrial lava tubes (e.g., Sicily) to gather real-world imagery for enhanced model training.

***

### Figure 1 Summary
Rhizome 1.0 prototypes include TU Delft rovers and Vertico’s cement-based robotic system for large-scale additive construction.