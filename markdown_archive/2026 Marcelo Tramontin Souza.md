# An overview of 3D printing Mars habitats using in-situ resources: materials, processing, structural challenges, and prospects

**Author:** Marcelo Tramontin Souza  
**Journal:** Acta Astronautica 247 (2026) 843–861  
**DOI:** [10.1016/j.actaastro.2026.05.055](https://doi.org/10.1016/j.actaastro.2026.05.055)

## Abstract
The establishment of a sustained human presence on Mars is strongly constrained by the mass, cost, and logistics associated with transporting construction materials from Earth, making in-situ resource utilization (ISRU) a central enabling strategy for surface infrastructure. Among ISRU-compatible approaches, additive manufacturing (3D printing) has emerged as a promising solution due to its compatibility with robotic deployment, efficient material usage, and geometric flexibility under extraterrestrial conditions. This review synthesizes current knowledge on Martian regolith as a construction feedstock, addressing its mineralogical, chemical, and physical characteristics, as well as the extreme environmental constraints imposed by Mars. This paper critically reviews the main 3D printing technologies and material systems proposed for Martian habitat construction, including extrusion-based alkali-activated binders, sulfur-based thermoplastic concretes, and binder-free sintering approaches driven by solar, microwave, or laser energy.

## 1. Introduction
Human exploration of Mars is fundamentally constrained by the cost of surface infrastructure. Jones estimates a first human mission would require USD 300-600 billion. A central driver of this cost is the mass penalty of transporting materials from Earth. ISRU, primarily using Martian regolith, has emerged as a foundational principle to produce construction materials directly on site. Additive manufacturing offers a pathway toward scalable and autonomous construction.

## 2. Background on the Martian regolith and building environment
Martian soil is dominated by plagioclase feldspars, pyroxenes, olivine, and iron oxides. Chemically, it exhibits a basaltic composition (40-50 wt% SiO2, 10-15 wt% Al2O3, 10-20 wt% FeO/Fe2O3). 

| Property | Typical range/value | Notes |
| :--- | :--- | :--- |
| SiO2 content | 40-50 wt% | Basaltic composition |
| Grain size | Silt to fine sand | Favorable for extrusion |
| Bulk density | ~1100-1600 kg/m3 | Depends on compaction |
| Thermal conductivity | ~0.05-0.2 W/m·K | Strongly density dependent |
| Surface temperature | -150 to +30 °C | Extreme variability |
| Atmospheric pressure | ~600 Pa | Affects processing |

## 4. 3D printing technologies and materials

### 4.1 Extrusion-based additive manufacturing: Low temperatures
*   **Alkali-activated binders (Geopolymers):** Rely on water or chemical activators. Monolithic specimens with bioinspired architectures (helical) achieved compressive strengths of ~32 MPa. 
*   **Limitations:** High dependence on water and Earth-derived activators (NaOH, Na2SiO3), and sensitivity to low pressure/temperature during curing.

### 4.2 Thermoplastic extrusion: Middle temperatures
*   **Sulfur Concrete:** Molten sulfur binder + regolith aggregate. Hardening occurs via thermal solidification (120-140 °C). 
*   **Performance:** Compressive strengths of 20-40 MPa (up to 58-60 MPa with DCPD modification). 
*   **Advantages:** Water-free, rapid hardening, and full recyclability through remelting.

### 4.3 Sintering-based additive manufacturing: High temperatures
*   **Solar Sintering:** Exploits silicate mineralogy for structural consolidation. Requires regolith heating to >1000 °C. 
*   **Microwave Sintering:** Uses dielectric losses of iron-rich phases. Volumetric heating is efficient but risks microcracking.
*   **Laser Sintering:** Suitable for small-scale, high-precision components (brackets, seals).

### 4.7 Energy requirements
| Method | Printing Energy (MJ/kg) | Total System Energy (MJ/kg) |
| :--- | :--- | :--- |
| Extrusion-based | 0.36–1.8 | ~5–20 |
| Laser Sintering | 10.8–18 | - |
| Microwave Sintering| 70–100 | - |

## 5. Protective design and performance
Radiation shielding is a primary driver. ~1.0 m of regolith reduces effective dose by ~71%, while ~3.0 m is required to reach terrestrial background levels. Hybrid concepts combine inflatable pressurized modules (Class II) with 3D-printed regolith shielding shells (Class III).

## 6. Structural response
Internal pressurization (50-100 kPa) is the primary load case. Seismic activity (marsquakes) is relatively weak (Mw 1.3-3.7) and unlikely to govern ultimate strength but may cause long-duration vibrations influencing fatigue.