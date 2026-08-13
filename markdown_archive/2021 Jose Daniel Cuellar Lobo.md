# Building Information Modelling- (BIM-) Based Generative Design for Drywall Installation Planning in Prefabricated Construction

**Journal:** Advances in Civil Engineering  
**Volume:** 2021, Article ID 6638236  
**Authors:** Jose Daniel Cuellar Lobo, Zhen Lei, Hexu Liu, Hong Xian Li, SangHyeok Han  
**DOI:** 10.1155/2021/6638236

## Abstract
In prefabricated construction, building components are manufactured off-site before shipping. This study proposes a generative design (GD) approach utilizing BIM and analytical algorithms to optimize drywall installation layouts. The framework includes a decision support module considering environmental, cost, and aesthetic aspects. Practical implementation showed improvements of 37.5% (environmental), 7% (cost), and 54% (aesthetics) for the best design alternatives.

## 1. Introduction
Prefabrication takes a manufacturing style to produce building components off-site, applying to residential, commercial, and heavy industrial sectors. In North American housing, wood panels are used where interior faces are covered with sheathing (gypsum/plywood). Cutting these materials generates significant scrap waste. BIM and GD offer potential to optimize layouts to minimize waste and improve efficiency.

## 2. Methodology
The research methodology consists of four analytical modules and one visualization module:
1. **Data Extraction:** Extracting geometric coordinates from BIM 3D models (Revit).
2. **Simulation-Based Design Algorithm:** Formalizing design and installation rules to generate multiple feasible layout alternatives.
3. **Heuristic Optimization:** Using a greedy algorithm to locally minimize material waste for each alternative.
4. **Decision-Making Support:** Implementing a fuzzy Analytical Hierarchy Process (AHP) to rank alternatives based on management criteria (Environmental, Cost, Aesthetics).
5. **Visualization:** Returning results to Dynamo/BIM for visual evaluation.

### Table 1: Sample cost information for drywall material (Canadian market)
| Item | Cost/Price | Units | Source |
| :--- | :--- | :--- | :--- |
| 1/2 in x 4 ft. x 8 ft. panel | $13 | $CAD/unit | Home Depot |
| 1/2 in x 4 ft. x 10 ft. panel | $16 | $CAD/unit | Home Depot |
| 1/2 in x 4 ft. x 12 ft. panel | $19 | $CAD/unit | Home Depot |
| Landfill tipping fee (NB) | $28 | $CAD/tonne | Fundy Recycles |

## 4. Evaluation of Results and Discussion
The best design layout solutions achieved significant reductions compared to the statistical median:
- **Environmental:** 37.5% reduction in material waste.
- **Cost:** 7% reduction in total cost.
- **Aesthetic:** 54% reduction in total drywall joint length.

## 5. Conclusions
The BIM-based generative design approach effectively provides optimized layouts for prefabricated scenarios, benefiting planning and waste reduction. The contributions include generative design for planning, incorporation of randomness in simulation, and fuzzy AHP for evaluation.