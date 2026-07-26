# Physical domain knowledge based image processing algorithm for in-situ surface porosity inspection and digitalization for 3D concrete printing structures

**Authors:** Andreas K. Lianos, Jeffrey W. Bullard, Dimitris C. Lagoudas, Satish T.S. Bukkapatnam
**Journal:** Cement and Concrete Research 207 (2026) 108271
**DOI:** https://doi.org/10.1016/j.cemconres.2026.108271

## Abstract
Concrete 3D printing holds transformative potential for construction because it can enable rapid, design-flexible structures from terrestrial housing to extraterrestrial habitats. However, its scalability is limited by challenges in quality control which governs structural integrity and durability, among which the volume fraction and size distribution of macro-porosity are especially critical. This study presents a novel scientific in-process monitoring technique for real-time macro-porosity analysis in 3D-printed concrete extrudates. Using a microscopy system with a side-mounted light source, the monitoring system captures surface microstructure without labor-intensive petrographic post-processing. A self-calibrating computer vision algorithm, leveraging a Perimeter-to-Area Ratio (PAR) metric and concrete domain knowledge, accurately distinguishes air voids from aggregates, overcoming conventional image processing misclassification. Validated against expert annotations, the algorithm achieved a 98% porosity prediction accuracy relative to manual petrographic baselines. Furthermore, the bimodal thresholding successfully mathematically isolates small-entrained spherical pores (<1.0 mm) from large-entrapped irregular voids (>1.25 mm) without manual input. This precise pore geometry and distribution analysis provides the actionable data required to optimize mixture designs on-the-fly, forecast a material's resistance to environmental stressors like freeze-thaw cycles, and enable the creation of digital twins for predictive maintenance.

## 1. Introduction
Concrete 3D printing has the potential to revolutionize construction by enabling rapid, cost-effective, and design-flexible structures for applications ranging from affordable housing to lunar habitats. However, its manufacturing readiness is currently limited by the complex rheological properties of concrete mixtures. Crucially, these factors shape the printed material's microstructure, particularly its porosity, which dictates both structural integrity and durability.

## 2. Methods
This system integrates a novel hardware-algorithm pipeline to monitor extrudate porosity in real-time 3D-printed concrete. It combines optical microscopy with a self-calibrating computer vision pipeline to overcome limitations of conventional petrographic image analysis.

### 2.1. Experimental setup
The system was tested using a cured cast UHPC cube without fibers, simulating extrudate surfaces without additional processing. A microscope with a side-mounted light source captured microstructure images.

### 2.1.1. Computer vision pipeline
Images undergo grayscale-to-binary conversion using a threshold, followed by contour detection via the Suzuki method. Porosity estimates are sensitive to threshold selection. To overcome this, the algorithm optimizes thresholds using a Perimeter-to-Area Ratio (PAR) metric:

$$PAR = \frac{P}{\sqrt{A}}$$

Where $P$ is the perimeter and $A$ is the area.

## 3. Results
The average algorithm porosity prediction of all pores among all microstructure images exhibits a 2% error. The algorithm correctly identified the number and location of the largest entrapped pores (>1.25 mm) for most microstructure splits.

### 3.1. Threshold variability
The optimal binary threshold (8-bit grayscale) has a mean of 129 and a standard deviation of 27.9, emphasizing the need for a self-calibrating step.

### 3.5. Validation summary
The developed monitoring system achieved a 98% porosity prediction accuracy compared to the petrography experts.

### 3.6. Porosity characterization
Smaller pores are more frequent than larger ones, following a geometric distribution. Most pores are nearly circular (low PAR values).

## 4. Discussion
PORECAST is an in-process tool providing a first-of-its-kind operational baseline for assessing internal concrete porosity via surface imaging. This eliminates reliance on labor-intensive ex-situ methodologies or expensive micro-CT for on-the-fly quality assurance.

## 5. Conclusions
1. **Precise Porosity Characterization**: The algorithm successfully distinguishes air voids from dark aggregates in 2D surface microstructures.
2. **Self-Calibrating Bimodal Thresholding**: The implementation of a PAR metric within a double Gaussian distribution model allows the system to dynamically self-calibrate.
3. **Scalable Hardware Integration**: Relies on accessible optical hardware, allowing for rapid deployment in terrestrial, military, and extraterrestrial applications.

### Table 1: Methodological framework.
| Category | Variable/parameter | Description & operating range |
| :--- | :--- | :--- |
| **I. Physical parameters** | Material composition | Ultra-High-Performance Concrete (UHPC) baseline mixture |
| | Hardware & illumination | Optical microscopy; side-mounted illumination |
| **II. Algorithmic variables** | Perimeter-to-area ratio | Shape descriptor for distinguishing spherical vs irregular voids |
| | Bimodal Gaussian threshold | Self-calibrated thresholding for entrained vs entrapped pores |
| **III. Indicators (outputs)** | Macroporosity fraction | Calculated percentage of surface area occupied by voids |
| | Void size distribution | Quantitative spread of pore diameters |