# Computer Vision for Terrain Mapping and 3D Printing In-situ of Extra/-terrestrial Habitats

**Authors:** Giuseppe Calabrese, Arwin Hidding, Henriette Bier, Casper van Engelenburg, Seyran Khademi, and Atousa Aslaminezhad  
**Publication:** IntelliSys 2024, LNNS 1067, pp. 349–360.  
**Publisher:** Springer Nature Switzerland AG 2024  
**DOI:** https://doi.org/10.1007/978-3-031-66431-1_23

## Abstract
This paper addresses the complexities inherent in constructing sustainable extraterrestrial habitats within lava tubes. These environments are addressed by integrating computer vision (CV) techniques and 3D printing in-situ. The CV component generates a detailed depth map from synthetic imagery to combine with an adaptive 3D printing process proposed to ensure level surfaces at various depths, facilitating precise foundation and habitat placement within lava tubes. Deep learning (DL) algorithms and convolutional neural networks (CNN) are used to generate depth maps.

## 1 Introduction
Construction in extraterrestrial environments, particularly within lava tubes on the Moon and Mars, offers protection against radiation and extreme temperatures. However, the irregular terrains of these natural underground spaces pose significant construction challenges.

## 2 Related Work
- **Bier et al. (2021):** Advancements in design and production of subterranean off-earth infrastructure.
- **Von Ehrenfried (2022):** Concepts of living in caves on Moon/Mars.
- **De Angelis et al. (2006):** Radiation safety analysis for lunar lava tubes.
- **Sauro et al. (2020):** Review of lava tube morphology on Earth, Moon, and Mars.

## 3 Problem Statement
Lava tubes present uneven and rugged terrains. Integrating CV with 3D printing provides a transformative approach to address these landscape challenges through real-time adaptability and autonomous terrain leveling.

## 4 Implications
CV-supported mapping facilitates the seamless attachment of habitable structures against lava tube walls and ground surfaces. The pixel-wise classification provided by the model is the cornerstone of the adaptive filling technique used to regularize surfaces.

## 5 CV vs. LiDAR Scanning
- **Real-time Analysis:** CV operates instantaneously compared to some scanning methods.
- **Cost Efficiency:** CV utilizes off-the-shelf cameras and sensors.
- **Redundancy:** Combining CV and LiDAR ensures continuous flow of data if one system fails.
- **Other benefits:** Lower power consumption and richer color/texture data.

## 6 Methodology
- **Incremental Solution:** Breakdown of synthetic depth map generation to U-Net implementation.
- **Depth Map and U-Net:** Used Grasshopper/Rhino and Perlin noise to generate synthetic training data. U-Net (a DL framework for image segmentation) was employed to associate depth maps with terrain features.
- **Thresholding:** Images underwent a thresholding operation classifying pixels into five distinct intensity levels to balance computational efficiency and structural detail.

## 7 Results and Conclusion
- **Training:** The U-Net was optimized using the Adam optimizer and cross-entropy loss over 20 epochs.
- **Accuracy:** Training accuracy reached 0.8 (80% correctly predicted pixels on training data).
- **Validation:** Validation accuracy was lower (0.5), indicating a need for more diverse datasets to prevent overfitting.
- **Conclusion:** The integration of CV and 3D printing allows for autonomous analysis and adaptation to surface irregularities. Future work includes testing in lava tubes in Sicily to capture real-world data.