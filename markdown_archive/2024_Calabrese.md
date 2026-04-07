# Computer Vision for Terrain Mapping and 3D Printing In-situ of Extra/-terrestrial Habitats

**Authors:** Giuseppe Calabrese, Arwin Hidding, Henriette Bier, Casper van Engelenburg, Seyran Khademi, and Atousa Aslaminezhad  
**Affiliations:** International Research School of Planetary Sciences (Italy), Delft University of Technology (Netherlands), University of Sydney (Australia), University of Antwerp (Belgium), Heriot-Watt University (Dubai)  
**Publication:** IntelliSys 2024, LNNS 1067, pp. 349–360, 2024.  
**DOI:** https://doi.org/10.1007/978-3-031-66431-1_23

---

## Abstract
This paper addresses the complexities inherent in constructing sustainable extraterrestrial habitats within lava tubes. These environments are addressed by integrating computer vision (CV) techniques and 3D printing in-situ. The CV component generates a detailed depth map from synthetic imagery to combine with an adaptive 3D printing process, ensuring level surfaces for foundations. Utilizing advanced deep learning (DL) algorithms and convolutional neural networks (CNN), the research develops a platform for sustainable extraterrestrial habitats.

## 1 Introduction
Exploration of celestial bodies faces the challenge of constructing habitable spaces in irregular environments like lava tubes. Prevalent on the Moon and Mars, these tubes offer protection against radiation and extreme temperatures. This research synergizes CV and 3D printing to transform lava tubes into viable habitats.

## 2 Related Work
- **Bier et al. (2021):** Advancements in design and operation of subterranean off-Earth infrastructure.
- **Von Ehrenfried (2022):** Concepts of living in caves on Moon and Mars.
- **Sauro et al. (2020):** Review of lava tube morphologies through comparative planetology.
- **Sauro et al. (2020):** Geological features of lava tubes on Earth, Moon, and Mars.

## 3 Problem Statement
Lava tubes offer natural shielding but present uneven, rugged terrains that pose challenges for construction. Traditional methods are inadequate, necessitating autonomous systems capable of real-time mapping and adaptive filling to ensure stable surfaces.

## 4 CV vs. LiDAR Scanning
The paper identifies several advantages of CV over LiDAR in certain scenarios:
- **Real-time Analysis:** CV allows for immediate decisions based on visual data.
- **Cost Efficiency:** Uses off-the-shelf cameras compared to expensive LiDAR units.
- **Redundancy:** CV serves as a backup when LiDAR fails due to technical or environmental constraints (e.g., dust).
- **Low Power Consumption:** Cameras consume less power than LiDAR systems.

## 5 Methodology
An incremental solution approach was adopted:
1. **Synthetic Depth Map Generation:** Grasshopper and Perlin noise algorithms were used to create synthetic data due to the lack of real lava tube imagery.
2. **U-Net Framework:** A deep learning framework was employed for image segmentation, associating depth maps with terrain features.
3. **Training:** The model was trained using 20 epochs, a 0.001 learning rate, and the Adam optimizer.

## 6 Results
- **Training Accuracy:** 0.8 (80%). The model effectively captured patterns within the training set.
- **Validation Accuracy:** 0.5 (50%). The lower score suggests a potential risk of overfitting and the need for more diverse datasets to enhance generalization.

## 7 Conclusion
The research demonstrates a system capable of autonomously analyzing surface data to adapt 3D printing processes for terrain leveling. Future work includes a physical experimental setup in a Sicilian lava tube to capture real imagery for model refinement.