# Computer Vision for Terrain Mapping and 3D Printing In-situ of Extra/-terrestrial Habitats

**Authors:** Giuseppe Calabrese, Arwin Hidding, Henriette Bier, Casper van Engelenburg, Seyran Khademi, and Atousa Aslaminezhad
**Year:** 2024
**Publisher:** Springer Nature Switzerland AG
**DOI:** 10.1007/978-3-031-66431-1_23

## Abstract
This paper addresses the complexities inherent in constructing sustainable extraterrestrial habitats within lava tubes that are envisioned as promising locations for human habitation and scientific inquiry. These environments are characterized by various challenges, which are addressed in this case by integrating computer vision (CV) techniques and 3D printing in-situ. The CV component generates a detailed depth map from synthetic imagery to combine this depth map with an adaptive 3D printing process, which is proposed to ensure level surfaces at various depths, facilitating precise foundation and habitat placement within the demanding context of lava tubes. Significantly, synthetic imagery is employed due to the absence of real lava tube photos at this early stage of the current exploration. The focal point lies in utilizing advanced deep learning (DL) algorithms and convolutional neural networks (CNN) to generate depth maps for extra/-terrestrial environments.

## 1 Introduction
The exploration and colonization of celestial bodies require innovative approaches to overcome irregularities in environments like lava tubes. These natural underground spaces on the Moon, Mars, and Earth offer protection against radiation and extreme temperatures.

## 2 Related Work
- **Bier et al. (2021):** Advancements in design, production, and operation of subterranean off-Earth infrastructure.
- **Von Ehrenfried (2022):** Concepts of living in caves on Moon and Mars.
- **Sauro et al. (2020):** Review of lava tubes morphology through comparative planetology.

## 3 Methodology
An incremental solution approach was adopted:
1. **Synthetic Depth Map Generation:** Used Perlin noise algorithms in Grasshopper/Rhino to create synthetic datasets due to lack of real lava tube imagery.
2. **U-Net Framework:** A deep learning framework for image segmentation was used to associate depth maps with terrain features.
3. **Training:** The model was trained on six batches (100 images each) covering various lighting scenarios (left/right light, flash, grayscale, color).

## 5 CV vs. LiDAR Scanning
| Feature | Computer Vision (CV) | LiDAR |
| :--- | :--- | :--- |
| **Real-time Analysis** | Instantaneous, swift for dynamic environments | High precision, but can be slower |
| **Cost** | Cost-effective, uses off-the-shelf cameras | Expensive |
| **Power** | Lower power consumption | Higher power consumption |
| **Information** | Provides color and texture | Distance-based only |

## 6 Results and Findings
- **Training Accuracy:** 0.8 (80% correctly predicted outcomes on training data).
- **Validation Accuracy:** 0.5 (indicates potential overfitting and the need for more diverse datasets).
- **Classification:** The image thresholding operation classified pixels into five distinct intensity/depth levels to balance computational efficiency and structural detail.

## 7 Conclusion
The research demonstrates a comprehensive system capable of autonomously analyzing real-time surface data to adapt 3D printing processes for leveling surfaces in lava tubes. Future work involves using real photographs from lava tubes in Sicily to refine the dataset.