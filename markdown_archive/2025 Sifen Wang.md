# Control Network Construction for LRO NAC Images Based on Refining Tie Points by Matching With Shaded LOLA DEM

**Journal:** IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing, Vol. 18, 2025
**Authors:** Sifen Wang, Xun Geng, Jiansheng Li, Tao Li, Junming Yu, Ancheng Wang, Jin Wang, Pengying Liu, Zhen Peng, Xin Ma, Yinhui Wang, Yuying Wang, and Guohua Chang

## Abstract
The upcoming exploration activities in the lunar south pole (LSP) require high-resolution mapping products to support landing site selection and navigation. Existing lunar mapping products exhibit limited coverage and accuracy in the south pole region. This study proposes a new control network construction method based on refining tie points by image matching between approximate orthophotos of lunar reconnaissance orbiter narrow-angle camera (NAC) images and shaded digital elevation model (DEM) maps. The experimental results demonstrate that the proposed method can effectively solve the problems of image matching and control network generation for lunar south pole images.

## I. Introduction
The lunar south pole (LSP) is the focus of current deep space exploration activities, including NASA's Artemis-3 and China's Chang'e-7 and Chang'e-8 missions. PSRs in the LSP may contain water ice, a vital resource for sustaining human life and fuel production. However, rugged terrain and unique illumination make robotic and human exploration challenging. Precise landing relies on high-precision maps (submeter-level mosaics and meter-level terrain models).

## IV. Experiments and Results
### Test Datasets
- **Dataset 1:** 87.5°S to 90°S latitude.
- **Dataset 2:** 79.5°S to 81.5°S latitude.
- **LOLA DEMs:** Resolutions of 10, 30, and 60 m/pixel.

### Quantitative Accuracy
Table VI shows quantitative accuracy evaluation results for refined control measures.

| Methods | Pixel coordinates errors (pixels): Sample | Pixel coordinates errors (pixels): Line |
| :--- | :--- | :--- |
| ISIS's cnetref | 18.92 | -14.82 |
| Our method (10m/pixel DEM) | 0.62 | -7.33 |
| Our method (30m/pixel DEM) | -5.88 | -14.75 |
| Our method (60m/pixel DEM) | 16.20 | 43.12 |

## V. Discussion
For the 10 m/pixel LOLA DEM, the pixel coordinate difference is less than two pixels. Converting standard deviation values into absolute units shows values between 5 and 20 m. This indicates high prediction accuracy for determining candidate control measures, laying a foundation for matching control measures.

## VI. Conclusion
The study successfully addressed illumination-related matching failures in the LSP by using shaded DEM maps as a transition for coordinate transformation. This significantly enhances the quality of automatically generated control networks, supporting future landing site selection and mapping missions.