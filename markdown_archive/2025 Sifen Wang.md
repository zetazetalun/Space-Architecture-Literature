# Control Network Construction for LRO NAC Images Based on Refining Tie Points by Matching With Shaded LOLA DEM

## Abstract
The upcoming exploration activities in the lunar south pole require high-resolution mapping products to support landing site selection and navigation. The special terrain and illumination conditions in the lunar south pole pose significant challenges to photogrammetric processing. In this study, a new control network construction method is proposed based on refining tie points by image matching between the approximate orthophotos of lunar reconnaissance orbiter narrow-angle camera (NAC) images and shaded digital elevation model (DEM) maps. The experimental results demonstrate that the proposed method can effectively solve the problems of image matching and control network generation for lunar south pole images.

## I. Introduction
The lunar south pole (LSP) is the focus of current deep space exploration activities, including NASA's Artemis-3 and China's Chang'e-7 and Chang'e-8 missions. Precise landing is critical, as large landing errors may lead to probes falling into permanently shadowed regions (PSRs). High-precision maps are required to fully characterize landing sites and assist navigation.

## II. Methodology
The key to constructing a high-quality control network is finding enough conjugate feature points for overlapping images. The proposed method includes:
1. **Generation of Shaded DEM Maps**: Using the photograph time of on-orbit LRO NAC images to ensure similar illumination conditions.
2. **Image Matching**: Using SIFT and pyramid matching between LRO NAC Digital Orthophoto Models (DOMs) and shaded DEM maps.
3. **Control Measure Refinement**: Establishing a coordinate transformation relationship (homograph matrix) to refine candidate control measures in orthophoto space before converting them to original image space.

## III. Experiments and Results
Two datasets were used: Dataset 1 (87.5° S to 90° S) and Dataset 2 (79.5° S to 81.5° S). 

### Table III: Prediction Accuracy Evaluation Results (M110779506LE)
| Grid Spacing | Max Sample (pixels) | Max Line (pixels) | Ave Sample (pixels) | Ave Line (pixels) | Std Sample (pixels) | Std Line (pixels) |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 10 m/pixel | 2.24 | 1.87 | 0.0001 | 0.0001 | 0.67 | 0.58 |
| 30 m/pixel | 1.70 | 1.51 | 0.0001 | 0.0001 | 0.53 | 0.48 |
| 60 m/pixel | 0.48 | 0.67 | 0.0001 | 0.0001 | 0.22 | 0.29 |

## IV. Discussion and Conclusion
The method achieved sub-pixel accuracy in many cases and maintained a sigma naught (bundle adjustment) of 0.48. The root mean square error of the images in the bundle adjustment was 0.43–0.72 pixels. This demonstrates the feasibility of high-precision mapping even in the challenging illumination of the lunar south pole.