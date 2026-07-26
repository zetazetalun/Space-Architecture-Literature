# Computer Vision for Terrain Mapping and 3D Printing In-situ of Extra/-terrestrial Habitats

**Authors:** Giuseppe Calabrese, Arwin Hidding, Henriette Bier, Casper van Engelenburg, Seyran Khademi, and Atousa Aslaminezhad

## Abstract
This paper addresses the complexities inherent in constructing sustainable extraterrestrial habitats within lava tubes that are envisioned as promising locations for human habitation and scientific inquiry. These environments are characterized by various challenges, which are addressed in this case by integrating computer vision (CV) techniques and 3D printing in-situ. The CV component generates a detailed depth map from synthetic imagery to combine this depth map with an adaptive 3D printing process, which is proposed to ensure level surfaces at various depths, facilitating precise foundation and habitat placement within the demanding context of lava tubes. Significantly, synthetic imagery is employed due to the absence of real lava tube photos at this early stage of the current exploration. The focal point lies in utilizing advanced deep learning (DL) algorithms and convolutional neural networks (CNN) to generate depth maps for extra/-terrestrial environments.

## 1 Introduction
The construction of habitable spaces in extraterrestrial environments, particularly within the irregular confines of lava tubes, offers unique opportunities for radiation protection and thermal stability. However, harnessing these requires innovative approaches to overcome surface irregularities.

## 2 Related Work
- **Bier et al. (2021):** Advancements in design and operation of subterranean off-earth infrastructure.
- **Von Ehrenfried (2022):** Concepts for living in caves on Earth, Moon, and Mars.
- **Sauro et al. (2020):** Review of lava tubes morphology on Earth, Moon, and Mars.

## 3 Problem Statement
Lava tubes offer natural shielding but present uneven and rugged terrains. Integrating CV with 3D printing brings real-time adaptability to address terrain analysis in varying lighting conditions and complex topographies.

## 4 Implications
Precise mapping allows for "adaptive filling," ensuring structural stability and the seamless attachment of habitable structures to walls and ground surfaces.

## 5 CV vs. LiDAR Scanning
- **CV Advantages:** Real-time analysis, cost-efficiency (off-the-shelf cameras), lower power consumption, and rich color/texture data.
- **Redundancy:** Ideally, both LiDAR and CV should be used to ensure continuous operations in cases of sensor failure (e.g., extreme dust).

## 6 Methodology
- **Incremental approach:** Synthetic depth map generation followed by U-Net deep learning framework for image segmentation.
- **Synthetic Data:** Due to lack of real images, Perlin noise algorithms were used to create 3D surface models and grayscale depth maps.
- **U-Net Architecture:** Used to associate depth maps with terrain features. It takes a single-channel grayscale image and produces a multi-channel depth map.

## 7 Results and Discussion
- **Training Data:** Six batches of 100 images (color, B&W, various light sources).
- **Training Accuracy:** 0.8 (80%), suggesting reasonable proficiency in pattern capture on training data.
- **Validation Accuracy:** 0.5 (50%), indicating a need for more diverse data to prevent overfitting and improve generalization.

## 8 Conclusion
The research demonstrates a system capable of autonomously analyzing surface data to adapt 3D printing for terrain leveling. Future work includes testing in a terrestrial lava tube in Sicily to capture real photographic datasets for validation.