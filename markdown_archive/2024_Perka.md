# 3D Printing of Tubular Connectors for Space Frame Structures

**Authors:** Ashok Kumar Perka, Bijoy Rajak, Shibashis Ghosh  
**Affiliations:** Tata Steel R&D, Jamshedpur; Altair, Pune, India  
**Year:** 2024  
**Source:** 3DcP 2023, STAM, pp. 251–262

## Abstract
In the construction industry, wire-based steel 3D printing (WBS-3DP) technology for structural parts has yet to be explored. This research discusses the application of wire-arc additive manufacturing (WAAM) in the fabrication of space frame structures for T-K-Y joints. The study demonstrates how WAAM can produce more efficient structures by eliminating challenges involved in tube joining and manual welding through topology optimization. It concludes that WBS-3DP can revolutionize construction by producing innovative parts like tube connectors with ease of fabrication.

## 1. Introduction
Additive Manufacturing (AM) involves depositing thin layers of material to generate a physical model. While aerospace and automotive industries have embraced metal 3D printing, the steel construction industry has moved slower due to part size and load requirements. Steel tubes are frequently used for trusses and space frames, but manual welding at T, K, and Y connections (TKY joints) is labor-intensive and prone to stress concentrations. 3D printing offers a way to manufacture complex shapes with better process control and reduced lead times.

## 2. Materials and Methods

### 2.1 Prototype for Tubular Joints Design
A prototype spaceframe structure was designed to accommodate all types of T-K and Y-type tube connections. 
- **Software:** Altair Inspire Print3D was used for topology optimization to reduce material usage and print time.
- **Optimisation:** Surfaces were smoothened to avoid irregularities; excess overhangs were avoided.

### 2.2 Tubular Joining Using Additive Manufacturing
- **Facility:** Centre for Advanced Welding and Joining (CAWJ), Tata Steel.
- **Equipment:** Robotic WAAM system consisting of Metal Inert Gas (MIG) welding connected to a 6-axis robotic arm.

### 2.3 Printing Process
- **Feedstock:** Carbon steel wire (0.8 mm diameter).
- **Shielding Gas:** 82% Ar + 18% CO2 at 15 l/min.
- **Parameters:** Bead height 2 mm, width 6 mm, constant bead overlap 1.5 mm.
- **Interpass Temperature:** Kept below 120 °C using temperature sensors.

| Wire Type | Dia. (mm) | C | Si | Mn | Ys (MPa) | UTS (MPa) | %El |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Low carbon steel | 0.8 | 0.07 | 0.83 | 1.48 | >470 | >565 | >22 |

## 3. Results and Discussion

### 3.1 Connector Data
Table 2: Details of the T-K-Y connections after topology optimization:

| Connection | Quantity | Part Boundary Dimensions (mm) | Weight (kg) |
| :--- | :--- | :--- | :--- |
| A | 2 | 240 x 284 x 340 | 42 |
| B | 4 | 257 x 227 x 338 | 42 |
| C | 2 | 200 x 344 x 304 | 32 |
| D | 3 | 327 x 200 x 224 | 26 |
| E | 6 | 150 x 150 x 201 | 10 |
| F | 3 | 305 x 120 x 100 | 5.5 |

### 3.2 Mechanical Properties
- **Repeatability:** Weights of the F-connectors were 6.95 kg, 6.97 kg, and 6.93 kg (approx. 99% repeatability).
- **Isotropy:** Tensile properties showed no significant differences across 0, 45, and 90-degree orientations.
- **Yield Strength:** 395–405 MPa.
- **Tensile Strength:** 497–507 MPa.
- **Elongation:** 32–40%.
- **Microstructure:** Equiaxed ferrite matrix with 7–10% pearlite. No directional solidification texture was found due to a 90° print layer rotation strategy.

## 4. Conclusions
The research successfully demonstrates a digital setup using WAAM to produce 20 tubular connectors for a space frame. These connectors can be installed with better tolerances than conventional TKY connections and meet the mechanical property requirements of conventional tubular steels. The process reduces welding difficulty from complex 6GR positions to simpler 5F joints.