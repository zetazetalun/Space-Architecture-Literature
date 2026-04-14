# Computer Vision for Terrain Mapping and 3D Printing In-situ of Extra/-terrestrial Habitats

**Giuseppe Calabrese<sup>1,2</sup>, Arwin Hidding<sup>2</sup>, Henriette Bier<sup>2,3</sup>, Casper van Engelenburg<sup>2</sup>, Seyran Khademi<sup>2</sup>, and Atousa Aslaminezhad<sup>4,5</sup>**

<sup>1</sup> International Research School of Planetary Sciences, Università d’Annunzio, Pescara, Italy
<sup>2</sup> Delft University of Technology, Delft, Netherlands
<sup>3</sup> University of Sydney, Sydney, Australia
<sup>4</sup> University of Antwerp, Antwerp, Belgium
<sup>5</sup> Heriot-Watt University, Dubai, United Arab Emirates

## Abstract
This paper addresses the complexities inherent in constructing sustainable extraterrestrial habitats within lava tubes that are envisioned as promising locations for human habitation and scientific inquiry. These environments are characterized by various challenges, which are addressed in this case by integrating computer vision (CV) techniques and 3D printing in-situ. The CV component generates a detailed depth map from synthetic imagery to combine this depth map with an adaptive 3D printing process, which is proposed to ensure level surfaces at various depths, facilitating precise foundation and habitat placement within the demanding context of lava tubes. Significantly, synthetic imagery is employed due to the absence of real lava tube photos at this early stage of the current exploration. The focal point lies in utilizing advanced deep learning (DL) algorithms and convolutional neural networks (CNN) to generate depth maps for extra/-terrestrial environments. This research represents a platform for further knowledge development in the fields of CV and its application to 3D printing in-situ, hence opening new avenues for sustainable extraterrestrial habitats.

**Keywords:** Lava tube habitats, Computer vision, 3D printing, Depth map, Robotic construction, Adaptive filling, Real-time mapping, Surface irregularities, Habitability.

## 1 Introduction
The exploration and colonization of celestial bodies have long been envisioned by humankind. One of the significant challenges faced in this endeavor is the construction of habitable spaces in extraterrestrial environments, particularly within the irregular and treacherous confines of lava tubes [1]. These natural underground spaces, prevalent on the Moon, Mars, and Earth [2], offer a unique opportunity for safe habitation and scientific research due to their protective nature against radiation and extreme temperatures [3, 4].

This paper presents an innovative approach relying on knowledge developed in the European Space Agency (ESA) funded project, Rhizome 1.0 (see Fig. 1), aiming to revolutionize extraterrestrial construction methodologies by synergizing computer vision (CV) techniques and advanced 3D printing towards transforming lava tubes into viable multi-functional habitats.

## 2 Methodology
In this research, an incremental solution approach is adopted. The methodology involves breaking down the overarching problem into manageable stages, from synthetic depth map generation to the utilization of the U-Net deep learning framework for image segmentation.

### Depth Map and U-Net
The explored CV-supported methodology employs a Grasshopper script crafted to extract details from a 3D surface model. Due to the very limited lava tube imagery, Perlin noise algorithms are leveraged to create synthetic depth maps that unveil the irregularities of the surfaces. A depth map, in this work, is represented as a compact integer-valued grayscale image where each pixel represents the distance from the camera to the corresponding point in the scene.

A U-Net [16]—a DL framework specifically developed for image segmentation—is employed to associate depth maps with the intricate features of terrain imagery within the lava tube environment. The U-Net model takes a grayscale image of the terrain (single-channel) as input and produces a depth map (multi-channel) as output.

## 3 Results and Training
### Training Curves
The U-Net was optimized using the Adam optimizer, cross-entropy loss, and dropout for regularization. The training data consisted of six batches, each containing 100 images categorized into scenarios (color, black/white, various light sources). The training process involved 20 epochs with a learning rate of 0.001.

**Performance Metrics:**
- **Training Accuracy:** 0.8 (The model correctly predicts the desired outcomes 80% of the time on training data).
- **Validation Accuracy:** 0.5 (Suggests a potential risk of overfitting and the need for more diverse data).

## 4 Conclusion
This research represents a fusion of technological innovation and adaptability. Through the integration of CV techniques and 3D printing technology, the complex challenges posed by lava tube irregularities are addressed. The result is a comprehensive system capable of autonomously analyzing real-time surface data which dynamically adapts the 3D printing construction process to these intricate features of the surface. This procedure provides the necessary prerequisites for leveling surfaces as well as constructing the habitats requiring positioning and maneuvering of the printer robot.