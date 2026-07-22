# Optimizing Magnesium Phosphate Binders with Boric Acid for Additive Construction Applications

**Authors:** H. Alkhateb, H. Almashaqbeh, J. Edmunson, M. Fiske, Y. Najjar, and Damian Stoddard
**Conference:** Earth and Space 2021
**Publisher:** ASCE

## Abstract
The authors propose a framework to utilize magnesia-based binders (MBBs) as an ordinary portland cement (OPC) alternative for extraterrestrial habitats and terrestrial 3D construction. MBBs show promise due to high compressive strength, rapid setting, and the potential for harvesting from lunar and Martian regolith. The research focuses on magnesia phosphate cement (MPC) composites with additives (boric acid, GnP, acetic acid) to optimize setting time and performance for 3D printing. Experimental results indicate that boric acid alters phase compositions and improves initial setting time. Artificial neural networks (ANN) are employed to optimize formulations for real-time printing adjustments.

## Introduction
Additive Manufacturing (AM) in construction can reduce costs and time but faces challenges in planetary environments, including material scarcity and 3D printing process requirements. Utilizing in-situ resources (ISRU) for habitat structures on the Moon and Mars is critical for long-duration missions. MPC is formed by reacting magnesium oxide with a soluble phosphate compound. While MPC has superior properties (high strength, durability), its extremely rapid setting time (seconds) complicates 3D construction. This study identifies additives to retard setting time without compromising mechanical properties.

## Magnesium Phosphate Cements
MPC belongs to the chemically bonded ceramics (CBCs) group. The reaction involves an acid-base interaction between dead-burned magnesia and phosphate. Traditionally using ammonium dihydrogen phosphate (ADP), current research favors potassium dihydrogen phosphate (KDP) to avoid unpleasant odors. The hydration produces K-struvite ($MgKPO_4 \cdot 6H_2O$).

## Methodology
The experimental program studied the effect of boric acid on MPC performance. Critical properties for 3D construction printing (3DCP) include setting time, workability, and green strength. ANN models were utilized to optimize mix formulations.

### Materials
- MgO: Dead-burned magnesia from Martin Marietta Magnesia Specialties.
- KDP: Monopotassium phosphate from Premier Magnesia, LLC.
- Boric Acid ($H_3BO_3$): 99.9% purity from Duda Energy, LLC.
- Distilled Water.

**Table 1: Chemical composition of the dead-burned MgO powder**

| Magnesium Oxide (MgO)% | Silicon Oxide (SiO2) % | Calcium Oxide (CaO)% | Iron Oxide (Fe2O3) % | Aluminum Oxide (Al2O3) % |
| :--- | :--- | :--- | :--- | :--- |
| 98.00 | 0.70 | 0.95 | 0.15 | 0.20 |

**Table 2: Physical and chemical properties of boric acid powder**

| Physical/chemical property | Description/Measured value |
| :--- | :--- |
| Appearance | Crystalline, White Solid |
| pH | 5.1 at 1.8 g/l at 25 °C (77 °F) |
| Melting point | 160 °C |
| Initial boiling point and boiling range | 1860 °C |
| Relative density | 1.440 g/cm3 |
| Solubility | In Water: 4.7% @ 20°C; 27.5% @ 100°C |
| Decomposition temperature | 169±1 to HBO2 & -1 1/2 H20 at 300°C |

## Results and Discussion
### Physical Properties
Boric acid acts as a retarder by forming a temporary layer of lunebergite ($Mg_3B_2(PO_4)_2(OH) \cdot 6H_2O$) that coats magnesium cations. Increasing the Boric acid/Magnesia (B/M) ratio up to 5% increases initial setting time. Beyond 5%, setting time may decrease due to rapid fluidity loss.

### Mechanical Properties
Compressive strength is highly dependent on the Magnesia/Phosphate (M/P) ratio. For a Water/Phosphate (W/P) ratio of 3.0, the optimal M/P ratio is 6. High water content (W/S ratio) reduces compressive strength and hydration temperature while increasing fluidity.

## ANN Numerical Simulation
ANN models were developed to predict flow, setting time, and compressive strength based on mix ingredients (M/P, W/P, B/M ratios).

**Table 4: Statistical measurements of ANN1-1 model (Structure 5-5-3)**

| Model | MARE training | MARE Testing/ validation | R2 Training | R2 Testing/ validation | ASE Training | ASE Testing/ validation | ASE Com. |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Training-testing | 15.85 | 31.88 | 0.93 | 0.84 | 0.0025 | 0.0129 | 0.0154 |
| Training-validation | 15.85 | 23.6 | 0.93 | 0.77 | 0.0025 | 0.0130 | 0.0155 |
| Training all | 17.28 | NA | 0.89 | NA | 0.0042 | NA | NA |

## Conclusions
1. Manipulating M/P, W/P, and B/M ratios allows tailoring MPC for 3D printing.
2. Boric acid up to 5% improves initial setting time (up to 15 minutes).
3. Boric acid reduces compressive strength more significantly in low M/P ratio mixes.
4. ANN effectively predicts MPC properties with high confidence for real-time adjustments.