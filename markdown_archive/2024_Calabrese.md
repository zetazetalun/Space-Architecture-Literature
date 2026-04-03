# Computer Vision for Terrain Mapping and 3D Printing In-situ of Extra/-terrestrial Habitats

**Authors:** Giuseppe Calabrese, Arwin Hidding, Henriette Bier, Casper van Engelenburg, Seyran Khademi, and Atousa Aslaminezhad  
**Publication:** IntelliSys 2024, LNNS 1067, pp. 349–360, 2024  
**DOI:** https://doi.org/10.1007/978-3-031-66431-1_23

## Abstract
This paper addresses the complexities inherent in constructing sustainable extraterrestrial habitats within lava tubes that are envisioned as promising locations for human habitation and scientific inquiry. These environments are characterized by various challenges, which are addressed in this case by integrating computer vision (CV) techniques and 3D printing in-situ. The CV component generates a detailed depth map from synthetic imagery to combine this depth map with an adaptive 3D printing process, which is proposed to ensure level surfaces at various depths, facilitating precise foundation and habitat placement within the demanding context of lava tubes. Significantly, synthetic imagery is employed due to the absence of real lava tube photos at this early stage of the current exploration. The focal point lies in utilizing advanced deep learning (DL) algorithms and convolutional neural networks (CNN) to generate depth maps for extra/-terrestrial environments.

## 1 Introduction
The exploration and colonization of celestial bodies have long been envisioned by humankind. One of the significant challenges faced in this endeavor is the construction of habitable spaces in extraterrestrial environments, particularly within the irregular and treacherous confines of lava tubes. These natural underground spaces, prevalent on the Moon, Mars, and Earth, offer a unique opportunity for safe habitation due to their protective nature against radiation and extreme temperatures.

![Fig. 1. Rhizome 1.0 prototypes using TU Delft rovers (left) and Vertico’s cement-based concrete and robotic system (right)](https://example.com/fig1.png)

## 3 Problem Statement
The prospect of utilizing lava tubes as potential habitation sites has sparked ambitious efforts in space colonization. However, the uneven and rugged terrains within lava tubes pose significant challenges for construction. Integrating CV techniques with advanced 3D printing technology offers a transformative approach to address the challenges posed by complex landscapes, providing real-time adaptability and efficiency.

## 5 CV vs. LiDAR Scanning
While LiDAR is well-established, CV offers several potential advantages in extraterrestrial construction:
- **Real-time Analysis:** CV operates instantaneously, allowing for swift analysis of dynamic environments.
- **Cost Efficiency:** Utilizes off-the-shelf cameras and sensors, making it more cost-effective.
- **Redundancy:** Serves as a reliable backup to LiDAR in extreme dust or low visibility conditions.
- **Low Power Consumption:** Cameras generally consume less power compared to LiDAR systems.
- **Color and Texture Information:** Provides richer data for material identification and mapping.

## 6 Methodology
An incremental solution approach was adopted, moving from synthetic depth map generation to the utilization of the U-Net deep learning framework for image segmentation.

### Depth Map and U-Net
Due to limited real-world lava tube imagery, Perlin noise algorithms were used to create synthetic depth maps representing surface irregularities. A U-Net architecture was employed to associate terrain imagery with these depth maps, enabling the system to comprehend the interplay of depth within the lava tube environment. This understanding forms the foundation of the adaptive filling approach, where irregularities are filled by the 3D printer to create level surfaces.

## 7 Conclusion
Through the integration of CV techniques and 3D printing, complex challenges posed by lava tube irregularities are addressed. The resulting system is capable of autonomously analyzing real-time surface data to adapt construction processes. Future work involves capturing real photographs of lava tubes in terrestrial analogs (e.g., Sicily) to refine the pre-trained models.

## Acknowledgments
Developed as part of the Rhizome 1.0 and 2.0 projects co-funded by ESA and Vertico under contract ESA AO/2-1749/20/NL/GLC.