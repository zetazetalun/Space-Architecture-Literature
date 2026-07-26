# Cross-section extraction and model reconstruction of lava tube based on L1-medial skeleton

**Authors:** Qiao Yang, Zhizhong Kang, Teng Hu, Zhen Cao, Chenming Ye, Dongming Liu, Haoxiang Hu, Shuai Shao
**Journal:** International Journal of Applied Earth Observation and Geoinformation 132 (2024) 104062
**DOI:** 10.1016/j.jag.2024.104062

## Abstract
Lunar lava tube caves, due to their unique geographical structure and potential as shelters, have repeatedly emerged as prime candidates or priority areas during discussions on lunar base site selection. This paper explores a method for extracting lava tube parameters and constructing models using LiDAR point cloud data. The approach encompasses data preprocessing, axis construction of the lava tube (L1-medial skeleton), cross-sectional feature extraction, and 3D model reconstruction. The method achieves high accuracy, with 99% of extracted cross-sectional points exhibiting an error of less than 0.12 m, providing technical support for studies of extraterrestrial volcanic activities and habitat planning.

## 1. Introduction
Lava tubes (roofed passages formed by flowing lava) can travel tens of kilometers. On the Moon and Mars, deep skylights similar to terrestrial lava tubes have been observed. These natural shelters offer protection from extreme temperature fluctuations, cosmic rays, lunar dust, and meteorites, making them suitable for lunar base construction.

## 2. Methodology
The study utilizes a four-step methodology:
1.  **Data Preprocessing:** Voxelization to reduce noise and point cloud volume.
2.  **Lava Tube Axis Establishment:** Using an iterative algorithm based on the L1-medial skeleton to find clustering centers and the central axis.
3.  **Cross-Section Extraction:** Sampling every 0.5 m along the axis to calculate geometric parameters like area, length, and width.
4.  **3D Model Reconstruction:** Building a mesh model by connecting cross-sections sequentially.

### Table 1: Parameters of Handheld Scanner
| Parameters | Numerical Value |
| :--- | :--- |
| Maximum Measuring Range | 100 m |
| Scan Vision Range | 270 x 360° |
| Relative Accuracy | 1.5–3 cm |

### Table 2: Comparison of voxelization results
| State | Number of point clouds | File size |
| :--- | :--- | :--- |
| Before voxelization | 192,171,753 | 6.44 GB |
| After voxelization | 2,363,582 | 9 MB |

## 3. Results and Accuracy Evaluation
The method was validated using the Jingpo Lake lava tube (terrestrial analogue). The accuracy was evaluated using Hausdorff distance.
- 99% of points fell within a 0.15 m error margin.
- Larger errors occurred primarily at sharp bends or areas with high debris/fallen rocks.

### Table 4: Calculation of the internal volume of a lava tube
| Survey region | Volume (m³) |
| :--- | :--- |
| Jingpo lake lava tube(1) | 421.624 |
| Jingpo lake lava tube(2) | 725.942 |
| Jingpo lake lava tube(3) | 614.921 |

## 4. Discussion and Conclusion
Providing accurate and effective internal 3D models is crucial for the utilization of lava tubes and the design of lunar bases. Handheld laser scanning devices integrated onto cave robots can conduct unmanned data collection. The L1-medial skeleton approach offers robust modeling even for irregular natural tunnels in dark environments, facilitating precise calculations of internal volume and structural stability for future habitation.