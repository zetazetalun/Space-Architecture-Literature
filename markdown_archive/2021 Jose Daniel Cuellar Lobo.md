# Building Information Modelling- (BIM-) Based Generative Design for Drywall Installation Planning in Prefabricated Construction

**Authors:** Jose Daniel Cuellar Lobo, Zhen Lei, Hexu Liu, Hong Xian Li, and SangHyeok Han

**Publication:** Advances in Civil Engineering, Volume 2021, Article ID 6638236

**DOI:** https://doi.org/10.1155/2021/6638236

## Abstract
In prefabricated construction, building components are manufactured off-site before shipping to the site for installation. This study proposes a generative design approach that utilizes the optimization of the drywall installation layout to improve overall project efficiency. The framework includes a decision support module that considers environmental, cost, and aesthetic aspects to identify the optimal layout. The framework's practical applicability has been successfully demonstrated through a case study.

## 1. Introduction
Prefabrication takes a manufacturing style to produce building components off-site and ship them to the installation site. In the North American housing industry, residential houses are often constructed using wood products. Gypsum and plywood sheathing materials come in standard sizes, and their installation often involves cutting material into smaller pieces, generating scrap waste. Prefabricated construction provides opportunities to improve the sheathing installation practice through controlled environments and BIM-based optimization.

## 2. Methodology
The research methodology consists of four analytical modules and one visualization module:
1.  **Data Extraction:** Geometrical information (wall frame coordinates) and material properties are extracted from the BIM 3D model (Revit).
2.  **Simulation-Based Design Algorithm:** Uses parameterized inputs to generate multiple feasible layout alternatives.
3.  **Heuristic Optimization Algorithm:** A greedy algorithm is used to locally optimize material waste for each design alternative by reusing cuts.
4.  **Decision-Making Support:** A fuzzy Analytical Hierarchy Process (AHP) methodology is implemented to rank design alternatives based on environmental, cost, and aesthetic criteria.
5.  **Visualization:** Results are returned to Dynamo for visualization in the BIM environment.

### Table 1: Sample cost information for drywall material and productivity (Canadian market)
| Item | Cost/Price | Units | Source |
| :--- | :--- | :--- | :--- |
| Drywall (4x8 ft) | $13 | $CAD/unit | Home Depot |
| Installation | $50 | $CAD/hr | Industry partner |
| Finishing | $70 | $CAD/hr | Industry partner |
| Landfill fee | $28 | $CAD/tonne | Fundy Recycles |

## 3. Implementation and Case Study
A two-story wood residential house (53 wood frames) was used as a case study. Thirty simulation cycles were initiated to generate drywall layouts based on different sizes (4x8, 4x10). Design rules included vertical/horizontal orientation checks, staggering seams (1/8 in. gap), and avoiding joints at high-stress areas like door/window openings.

## 4. Results and Discussion
The study achieved the following improvements compared to the simulation median:
*   **Environmental:** 37.5% reduction in material waste (achieving a 10% minimum waste percentage).
*   **Cost:** 7% reduction in total project cost (CAD 5,580 median vs optimized).
*   **Aesthetic:** 54% reduction in drywall seam length (231 lin. ft. median vs optimized).

### Table 6: Final fuzzy AHP scores (Top 5 scenarios)
| Top 10 | Scenario | Aesthetic | Environmental | Total Cost | Final Fuzzy AHP Score |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | s25 | 3 | 2 | 2 | 2.66 |
| 2 | s65 | 3 | 2 | 2 | 2.66 |
| 3 | s62 | 2 | 3 | 3 | 2.34 |
| 4 | s88 | 2 | 3 | 3 | 2.34 |
| 5 | s117 | 2 | 3 | 3 | 2.34 |

## 5. Conclusions
The framework provides a systematic way to explore multiple design alternatives. The research demonstrated that the "best" design layout is conditional on the prioritization of management criteria (e.g., waste vs. aesthetics). The contributions include generative design for prefabrication planning and the integration of fuzzy AHP for results evaluation.