# Computer Vision for Terrain Mapping and 3D Printing In-situ of Extra/-terrestrial Habitats

**Authors:** Giuseppe Calabrese, Arwin Hidding, Henriette Bier, Casper van Engelenburg, Seyran Khademi, and Atousa Aslaminezhad

## Abstract
This paper addresses the complexities inherent in constructing sustainable extraterrestrial habitats within lava tubes that are envisioned as promising locations for human habitation and scientific inquiry. These environments are characterized by various challenges, which are addressed in this case by integrating computer vision (CV) techniques and 3D printing in-situ. The CV component generates a detailed depth map from synthetic imagery to combine this depth map with an adaptive 3D printing process, which is proposed to ensure level surfaces at various depths, facilitating precise foundation and habitat placement within the demanding context of lava tubes. Significantly, synthetic imagery is employed due to the absence of real lava tube photos at this early stage of the current exploration. The focal point lies in utilizing advanced deep learning (DL) algorithms and convolutional neural networks (CNN) to generate depth maps for extra/-terrestrial environments. This research represents a platform for further knowledge development in the fields of CV and its application to 3D printing in-situ, hence opening new avenues for sustainable extraterrestrial habitats.

## 1 Introduction
The exploration and colonization of celestial bodies have long been envisioned by humankind. One of the significant challenges faced in this endeavor is the construction of habitable spaces in extraterrestrial environments, particularly within the irregular and treacherous confines of lava tubes. These natural underground spaces offer unique opportunities for safe habitation due to their protective nature against radiation and extreme temperatures.

## 2 Related Work
The integration of CV techniques and 3D printing for in-situ construction aligns with existing research by Bier et al. (2021) on subterranean off-Earth infrastructure and Sauro et al. (2020) on lava tube morphologies. This study uniquely focuses on the fusion of CV and 3D printing to address lava tube complexities.

## 3 Problem Statement
Lava tubes present uneven and rugged terrains that pose significant challenges for construction. Integrating CV with 3D printing offers a transformative approach to achieve real-time adaptability and efficiency for leveling surfaces and foundation placement.

## 4 Implications
Precisely mapping irregularities ensures structural stability and facilitates the attachment of habitable structures. This CV-supported technology, while developed for off-Earth applications, also has potential terrestrial transfers for disaster-stricken or remote environments.

## 5 CV vs. LiDAR Scanning
Advantages of CV over LiDAR include:
- **Real-time Analysis:** CV operates instantaneously for swift decision-making.
- **Cost Efficiency:** Utilizes off-the-shelf cameras and sensors.
- **Redundancy:** Provides a backup to LiDAR in conditions like extreme dust.
- **Low Power Consumption:** Generally lower than LiDAR systems.
- **Rich Data:** Provides color and texture information.

## 6 Methodology
An incremental solution approach was adopted:
1. **Synthetic Depth Map Generation:** Leveraging Grasshopper and Perlin noise algorithms to create synthetic training data mimicking lava tube textures.
2. **U-Net for Segmentation:** A deep learning framework (U-Net) is used to process terrain imagery and produce depth maps as output.
3. **Training Process:** The model was trained using six batches of 100 images each, categorized by lighting and color scenarios, across 20 epochs.

## 7 Results and Findings
- **Training Accuracy:** Reached 0.8 (80% correct classification of pixels in the training set).
- **Validation Accuracy:** Reached 0.5, indicating a risk of overfitting and the need for more diverse datasets.
- **Segmentation:** The technique classified pixels into five distinct intensity levels to capture both coarse and fine-grained structures.

## 8 Conclusion
The research demonstrates a comprehensive system for autonomous surface analysis and adaptive 3D printing. Future work involves capturing real photographs in terrestrial lava tubes (e.g., in Sicily) to enhance the training dataset and fine-tune the model for real-world scenarios.