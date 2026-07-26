# Point cloud-based morphological analysis and surface reconstruction of extraterrestrial lava tubes

**Authors:** Ruimin Lu, Zhibin Sun, Ming Lei, Jiaqi Yao, Yuan Han, Hongxu Ai, Mingyang Zhang  
**Journal:** Advances in Space Research 77 (2026) 7494–7506  
**DOI:** 10.1016/j.asr.2026.01.054  
**Available online:** 21 January 2026

## Abstract
Lava tubes provide vast and structurally stable underground spaces with minimal temperature fluctuations and effective shielding from cosmic radiation, making them promising candidates for extraterrestrial base construction. Assessing their feasibility requires detailed morphological analysis and high-precision three-dimensional surface reconstruction. This paper proposes a point cloud-based surface reconstruction method. Principal Component Analysis (PCA) is used for adaptive normal estimation and normalization, while an anisotropic weighting function combined with the Moving Least Squares (MLS) projection is used to resample curvature-sensitive regions. An implicit surface is then reconstructed using the Poisson algorithm to generate a high-quality triangular mesh. The results indicate that the geometric similarity error of point cloud resampling can be minimized to 2 mm.

## 1. Introduction
Lava tubes are widely distributed on Earth, and lava tube-like voids have also been identified on the Moon and Mars. Their morphological characteristics play an important role in supporting future extraterrestrial human activities, including transportation, infrastructure development, and habitat construction. LiDAR-based scanning is critical for capturing high-density 3D point clouds of interior surfaces to assess stability.

## 2. Proposed Method
### 2.1. Lava tube morphological analysis
1. **Centerline Extraction:** Original point clouds are voxel-downsampled and segmented. A Mean Shift (MS) algorithm is applied to extract centerline points, refined by cubic spline interpolation.
2. **Cross-sectional Analysis:** Sections are generated at equal intervals along the centerline. A convex hull algorithm extracts the cross-sectional contour.

### 2.2. Point cloud resampling (ASR Method)
- **Adaptive Neighborhood Normal Estimation:** Uses PCA to adjust neighborhood scale according to local geometric features.
- **Anisotropic Weights:** Introduces normal vector distance as a metric to preserve fine structures in high-curvature areas.
- **Poisson Reconstruction:** An implicit surface reconstruction method to obtain a watertight mesh.

## 3. Evaluation Metrics
- **Geometric Similarity:** RMSE between resampled and original point clouds.
- **Curvature Similarity:** Mean absolute curvature difference.
- **Surface Accuracy:** Hausdorff distance and Mean Error (ME).

## 4. Results and Discussion
- **Dataset:** Tested on the 'Indian Tunnel' dataset provided by NASA.
- **Morphological Findings:**
  - Total length: ~250 m.
  - Height: 6.39 to 12.83 m.
  - Width: 12.01 to 24.55 m.
  - Cross-sectional area: 63 to 169 m².
- **Reconstruction Performance:** The proposed ASR method achieves a minimum reconstruction Mean Error (ME) of 2 mm. It outperforms OSR and MLS methods in preserving local structural details and overall continuity.

## 5. Conclusion
The study provides a solid geometric foundation for subsequent numerical simulations and safety assessments of extraterrestrial underground habitats. The ASR method demonstrates robust performance under low-density and high-noise conditions characteristic of robotic LiDAR missions.