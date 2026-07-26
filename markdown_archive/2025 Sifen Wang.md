# Control Network Construction for LRO NAC Images Based on Refining Tie Points by Matching With Shaded LOLA DEM

## Abstract
The upcoming exploration activities in the lunar south pole require high-resolution mapping products to support landing site selection and navigation. In this study, a new control network construction method is proposed based on refining tie points by image matching between the approximate orthophotos of lunar reconnaissance orbiter narrow-angle camera (NAC) images and shaded digital elevation model (DEM) maps. Experimental results demonstrate that the proposed method effectively solves the problems of image matching and control network generation for lunar south pole images.

## I. INTRODUCTION
The lunar south pole (LSP) is the focus of current deep space exploration activities, including NASA's Artemis-3 and China's Chang'e-7 and Chang'e-8 missions. Water ice in permanently shadowed regions (PSRs) serves as a vital resource for sustaining human life and fuel production. Precise landing is critical; however, existing mapping products often lack the geolocation accuracy and resolution required. High-precision maps are necessary to characterize landing sites and assist navigation.

## II. RELATED WORK
LRO NAC provides images with 0.5–1.5 m/pixel resolution. However, generating large-scale DEMs is difficult due to limited stereo slew opportunities. Existing products like LOLA DEM (laser altimetry) have high vertical accuracy but limited horizontal resolution (approx. 10–60 m/pixel in the LSP). Recent efforts to generate regional high-resolution maps struggle with illumination conditions and low texture in polar regions.

## III. METHODOLOGY
The proposed method involves:
1. Generating shaded DEM maps using LOLA data with illumination conditions matching the acquisition time of NAC images.
2. Establishing coordinate transformations between NAC orthophotos and shaded DEMs using the SIFT algorithm.
3. Using the shaded DEM as a transition to refine tie points and candidate control measures in the control network.
4. Converting refined measures from orthophoto space back to original image space for bundle adjustment.

## IV. EXPERIMENTS AND RESULTS
### Table I: Basic Information of the Test Images
| Images | GSD (m) | Image Size (lines x samples) | Incidence Angle (deg) | Emission Angle (deg) |
|---|---|---|---|---|
| M110779506LE | 0.82 | 52224 x 2532 | 87.75 | 1.70 |
| M1153379413LE | 0.87 | 52224 x 2532 | 83.57 | 1.71 |
| M153386201RE | 0.88 | 52224 x 2532 | 83.49 | 1.17 |

### Table III: Prediction Accuracy Evaluation (M110779506LE)
| Grid Spacing | Max Sample Error (pix) | Max Line Error (pix) | Std Sample Error (pix) | Std Line Error (pix) |
|---|---|---|---|---|
| 10 m/pixel | 2.24 | 22.4 | 0.67 | 0.58 |
| 30 m/pixel | 1.70 | 51.0 | 0.53 | 0.48 |
| 60 m/pixel | 0.48 | 28.6 | 0.22 | 0.29 |

## V. DISCUSSION
For the 10 m/pixel LOLA DEM, the pixel coordinate difference is less than two pixels. Standard deviations (0.58–0.67 pixels) translate to absolute units of approximately 5 to 20 meters, demonstrating high prediction accuracy for determining candidate control measures. This facilitates better bundle adjustment and high-quality topographic mapping.

## VI. CONCLUSION
The harsh environments of the LSP make image matching extremely difficult. This study provides a robust matching strategy using shaded DEMs as a bridge. The method enhances the quality of automatically generated control networks, supporting future exploration missions and scientific research.