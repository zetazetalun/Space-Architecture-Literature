# Point cloud-based morphological analysis and surface reconstruction of extraterrestrial lava tubes

**Authors:** Ruimin Lu, Zhibin Sun, Ming Lei, Jiaqi Yao, Yuan Han, Hongxu Ai, Mingyang Zhang
**Journal:** Advances in Space Research 77 (2026) 7494–7506
**DOI:** 10.1016/j.asr.2026.01.054

## Abstract
Lava tubes provide vast and structurally stable underground spaces with minimal temperature fluctuations and effective shielding from cosmic radiation, making them promising candidates for extraterrestrial base construction. Assessing their feasibility requires detailed morphological analysis and high-precision three-dimensional surface reconstruction. This paper proposes a point cloud-based surface reconstruction method. Principal Component Analysis (PCA) is used for adaptive normal estimation and normalization, while an anisotropic weighting function combined with the Moving Least Squares (MLS) projection is used to resample curvature-sensitive regions. An implicit surface is then reconstructed using the Poisson algorithm to generate a high-quality triangular mesh.

## 1. Introduction
Lava tubes are identified on the Moon and Mars. Their morphological characteristics, spatial distribution, and material composition play an important role in supporting future extraterrestrial human activities, including transportation, infrastructure development, and habitat construction. Geometric parameters such as height, width, and cross-sectional morphology are of critical importance for understanding their formation processes and evaluating their potential for underground habitats.

## 2. Methodology
### 2.1. Lava Tube Morphological Analysis
- Original point cloud is voxel-downsampled.
- Mean Shift (MS) algorithm is applied to extract centerline points.
- Cubic spline interpolation fits a continuous principal axis curve.
- Cross-sections are generated at equal intervals.
- Convex hull algorithm extracts cross-sectional contours.

### 2.2. Point Cloud Resampling (ASR Method)
- **Normal Vector Estimation:** Uses PCA to dynamically adjust neighborhood scale based on local geometric features.
- **Anisotropic Weights:** Introduces normal vector distance as a metric to preserve sharp features.
- **Reprojection:** Local fitting and adjustment for each point.

### 2.3. Poisson Reconstruction
Generates a watertight surface model with a smooth surface and strong robustness.

## 3. Results
- **Validation:** Tested using an Indian lava tube dataset (250 meters long).
- **Cross-sections:** 27 typical cross-sections were extracted.
- **Morphology:** Heights ranged from 6.39 to 12.83 m; widths from 12.01 to 24.55 m; aspect ratios between 1.25 and 3.7.
- **Accuracy:** The geometric similarity error of point cloud resampling was minimized to 2 mm.
- **Comparison:** The proposed ASR method outperformed OSR and MLS methods in both geometric similarity (20-40% improvement) and curvature similarity (over 30% improvement).

## 4. Conclusion
The method provides a theoretical basis and methodological support for the site selection of extraterrestrial bases. It enables high-precision modeling that preserves local structural details, crucial for structural stability assessment and path planning inside lunar or Martian voids.