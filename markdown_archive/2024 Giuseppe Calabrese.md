# Computer Vision for Terrain Mapping and 3D Printing In-situ of Extra/-terrestrial Habitats

**Authors:** Giuseppe Calabrese, Arwin Hidding, Henriette Bier, Casper van Engelenburg, Seyran Khademi, and Atousa Aslaminezhad

**Abstract:** This paper addresses the complexities inherent in constructing sustainable extraterrestrial habitats within lava tubes that are envisioned as promising locations for human habitation and scientific inquiry. These environments are characterized by various challenges, which are addressed in this case by integrating computer vision (CV) techniques and 3D printing in-situ. The CV component generates a detailed depth map from synthetic imagery to combine this depth map with an adaptive 3D printing process, which is proposed to ensure level surfaces at various depths, facilitating precise foundation and habitat placement within the demanding context of lava tubes. Significantly, synthetic imagery is employed due to the absence of real lava tube photos at this early stage of the current exploration. The focal point lies in utilizing advanced deep learning (DL) algorithms and convolutional neural networks (CNN) to generate depth maps for extra/-terrestrial environments.

## 1. Introduction
The exploration and colonization of celestial bodies have long been envisioned by humankind. One of the significant challenges faced in this endeavor is the construction of habitable spaces in extraterrestrial environments, particularly within the irregular and treacherous confines of lava tubes. These natural underground spaces, prevalent on the Moon, Mars, and Earth, offer a unique opportunity for safe habitation and scientific research due to their protective nature against radiation and extreme temperatures.

## 2. Related Work
In the realm of 3D printing for extraterrestrial habitats, Bier et al. (2021) introduced significant advancements in the design, production, and operation of subterranean off-Earth infrastructure. Von Ehrenfried (2022) delved into the concept of living in caves on Earth, Moon, and Mars. Sauro et al. (2020) offered a comprehensive review of lava tubes on Earth, Moon, and Mars, shedding light on their varied sizes and morphologies.

## 3. Problem Statement
The uneven and rugged terrains within lava tubes pose significant challenges for construction. Integrating CV techniques with advanced 3D printing technology offers a transformative approach to address the challenges posed by complex landscapes. Terrain analysis is a complex undertaking in a lava tube, primarily due to numerous surface irregularities to traverse in varying lighting conditions.

## 4. Implications
The core objective of employing CV in lava tubes transcends mere technical challenges; it fundamentally impacts the habitability of the constructed spaces. By precisely mapping irregularities, the construction system ensures not only structural stability but also facilitates the seamless attachment of habitable structures against the lava tube walls and ground surfaces where necessary.

## 5. CV vs. LiDAR Scanning
While LiDAR scanning utilizes laser pulses to measure distances, CV offers several advantages:
- **Real-time Analysis:** CV operates instantaneously, allowing for swift analysis of dynamic environments.
- **Cost Efficiency:** CV systems utilize off-the-shelf cameras and sensors.
- **Redundancy:** Employing both LiDAR and CV creates redundancy in data collection.
- **Low Power Consumption:** Cameras generally consume less power compared to LiDAR systems.

## 6. Methodology
An incremental solution approach is adopted, involving phases from synthetic depth map generation to the utilization of the U-Net deep learning framework for image segmentation. Due to the limited lava tube imagery, Perlin noise algorithms are leveraged to create synthetic depth maps. A depth map is represented as a compact integer-valued grayscale image where each pixel represents the distance from the camera to the corresponding point in the scene.

### Depth Map and U-Net
A U-Net DL framework specifically developed for image segmentation is employed to associate depth maps with the intricate features of terrain imagery. The U-Net model takes a grayscale image of the terrain as input and produces a depth map as output.

## 7. Conclusion
This research represents a fusion of technological innovation and adaptability. Through the integration of CV techniques and 3D printing technology, the complex challenges posed by lava tube irregularities are addressed. The result is a comprehensive system capable of autonomously analyzing real-time surface data which dynamically adapts the 3D printing construction process.