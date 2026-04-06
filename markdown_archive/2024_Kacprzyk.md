# Computer Vision for Terrain Mapping and 3D Printing In-situ of Extra/-terrestrial Habitats

**Giuseppe Calabrese**, **Arwin Hidding**, **Henriette Bier**, **Casper van Engelenburg**, **Seyran Khademi**, and **Atousa Aslaminezhad**

## Abstract
This paper addresses the complexities inherent in constructing sustainable extraterrestrial habitats within lava tubes that are envisioned as promising locations for human habitation and scientific inquiry. These environments are characterized by various challenges, which are addressed in this case by integrating computer vision (CV) techniques and 3D printing in-situ. The CV component generates a detailed depth map from synthetic imagery to combine this depth map with an adaptive 3D printing process, which is proposed to ensure level surfaces at various depths, facilitating precise foundation and habitat placement within the demanding context of lava tubes. Significantly, synthetic imagery is employed due to the absence of real lava tube photos at this early stage of the current exploration. The focal point lies in utilizing advanced deep learning (DL) algorithms and convolutional neural networks (CNN) to generate depth maps for extra/-terrestrial environments. This research represents a platform for further knowledge development in the fields of CV and its application to 3D printing in-situ, hence opening new avenues for sustainable extraterrestrial habitats.

## 1 Introduction
The exploration and colonization of celestial bodies have long been envisioned by humankind. One of the significant challenges faced in this endeavor is the construction of habitable spaces in extraterrestrial environments, particularly within the irregular and treacherous confines of lava tubes. These natural underground spaces, prevalent on the Moon, Mars, and Earth, offer a unique opportunity for safe habitation and scientific research due to their protective nature against radiation and extreme temperatures.

### 3D Printing and AI
In-situ 3D printing, guided by artificial intelligence (AI), enables the on-site production of extra-/terrestrial habitats using locally available information and materials. This research envisages a robotic AI-supported 3D printing construction system that maps the irregularities of lava tube surfaces. The synergy between real-time mapping, machine learning (ML), CV, and depth sensing technologies is aimed at optimizing efficiency, precision, and adaptability.

## 6 Methodology
In this research, an incremental solution approach is adopted. The explored CV-supported methodology employs a Grasshopper script to extract details from a 3D surface model. Due to limited lava tube imagery, Perlin noise algorithms are leveraged to create synthetic depth maps. A depth map is represented as a compact integer-valued grayscale image where each pixel represents the distance from the camera.

### Depth Map and U-Net
A U-Net deep learning framework is employed for image segmentation to associate depth maps with the intricate features of terrain imagery. The model takes a grayscale image of the terrain as input and produces a multi-channel depth map as output.

## 7 Conclusion
This research represents a fusion of technological innovation and adaptability, envisaging a new era in construction methodologies. The integration of CV and 3D printing allows for autonomously analyzing real-time surface data to adapt construction processes to intricate surface features. This provides the necessary prerequisites for leveling surfaces as well as constructing habitats requiring positioning and maneuvering of a printer robot.

### Future Work
Future strategies involve capturing real photographs of a lava tube (e.g., in Sicily) and coupling them with LiDAR results to ascertain depth, providing a tangible dataset for refining and fine-tuning the pre-trained model.