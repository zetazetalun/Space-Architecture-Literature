# Computer Vision for Terrain Mapping and 3D Printing In-situ of Extra/-terrestrial Habitats

**Giuseppe Calabrese**, **Arwin Hidding**, **Henriette Bier**, **Casper van Engelenburg**, **Seyran Khademi**, and **Atousa Aslaminezhad**

## Abstract
This paper addresses the complexities inherent in constructing sustainable extraterrestrial habitats within lava tubes that are envisioned as promising locations for human habitation and scientific inquiry. These environments are characterized by various challenges, which are addressed in this case by integrating computer vision (CV) techniques and 3D printing in-situ. The CV component generates a detailed depth map from synthetic imagery to combine this depth map with an adaptive 3D printing process, which is proposed to ensure level surfaces at various depths, facilitating precise foundation and habitat placement within the demanding context of lava tubes. Significantly, synthetic imagery is employed due to the absence of real lava tube photos at this early stage of the current exploration. The focal point lies in utilizing advanced deep learning (DL) algorithms and convolutional neural networks (CNN) to generate depth maps for extra/-terrestrial environments. This research represents a platform for further knowledge development in the fields of CV and its application to 3D printing in-situ, hence opening new avenues for sustainable extraterrestrial habitats.

**Keywords:** Lava tube habitats, Computer vision, 3D printing, Depth map, Robotic construction, Adaptive filling, Real-time mapping, Surface irregularities, Habitability.

## 1 Introduction
The exploration and colonization of celestial bodies have long been envisioned by humankind. One of the significant challenges faced in this endeavor is the construction of habitable spaces in extraterrestrial environments, particularly within the irregular and treacherous confines of lava tubes. These natural underground spaces, prevalent on the Moon, Mars, and Earth, offer a unique opportunity for safe habitation and scientific research due to their protective nature against radiation and extreme temperatures.

## 6 Methodology
In this research, an incremental solution approach is adopted where the methodology involves breaking down the overarching problem into manageable stages, proposing and implementing solutions one step at a time. Each phase is designed to build upon the preceding steps from synthetic depth map generation to the utilization of the U-Net deep learning framework for image segmentation.

### Depth Map and U-Net
The explored CV-supported methodology employs a Grasshopper script crafted to extract details from a 3D surface model, going beyond mere visual representation. Due to the very limited lava tube imagery, the advanced capabilities of Perlin noise algorithms are leveraged to create synthetic depth maps that unveil the irregularities of the surfaces.

## 7 Conclusion
In conclusion, this research represents a fusion of technological innovation and adaptability, envisaging a new era in construction methodologies. Through the integration of CV techniques and 3D printing technology, the complex challenges posed by lava tube irregularities are addressed. The result is a comprehensive system capable of autonomously analyzing real-time surface data which dynamically adapts the 3D printing construction process to these intricate features of the surface. This procedure provides the necessary prerequisites for leveling surfaces as well as constructing the habitats requiring positioning and maneuvering of the printer robot.