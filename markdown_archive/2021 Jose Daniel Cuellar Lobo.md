# Building Information Modelling- (BIM-) Based Generative Design for Drywall Installation Planning in Prefabricated Construction

## Abstract
In prefabricated construction, building components are manufactured off-site before shipping to the site for installation. This study proposes a generative design approach that utilizes the optimization of the drywall installation layout to improve overall project efficiency. The framework includes a decision support module that considers environmental, cost, and aesthetic aspects. The design improvements achieved were 37.5%, 7%, and 54% for environmental, cost, and aesthetic factors, respectively.

## 1. Introduction
The prefabricated construction approach has been widely adopted to improve construction efficiency and productivity. Compared to traditional stick-built construction, prefabrication takes a manufacturing style to produce building components off-site and ship them to the installation site.

## 2. Methodology
The research methodology consists of four analytical modules:
1. **Data Extraction:** Geometric information (wall coordinates) is extracted from the BIM 3D model (Revit).
2. **Simulation-Based Design Algorithm:** Generates multiple feasible design alternatives based on installation rules.
3. **Heuristic Optimization Algorithm:** Uses a greedy algorithm to locally optimize material waste by reusing drywall cuts.
4. **Decision-Making Support:** Implements a fuzzy analytical hierarchy process (AHP) to rank alternatives based on environmental, cost, and aesthetic criteria.

### Table 1: Sample cost information for drywall material and productivity
| Item | Cost/price | Units | Source |
| :--- | :--- | :--- | :--- |
| Drywall materials (4x8 ft) | $13 | $CAD/unit | homedepot.ca |
| Drywall installation | $50 | $CAD/hr | Industry partner |
| Drywall finishing | $70 | $CAD/hr | Industry partner |
| Landfill tipping fee | $28 | $CAD/tonne | fundyrecycles.com |

## 3. Implementation and Case Study
A two-story wood residential house (53 wood frames) was used as a case study. Thirty simulation cycles were initiated to generate drywall layouts. The design rules included vertical/horizontal orientation, alignment with studs, staggered seams, and avoidance of joints near door/window openings.

## 4. Evaluation of the Results and Discussion
The model achieved a minimum of 10% material waste percentage. The results highlight the advantages of BIM-based generative design in exploring multiple design alternatives that vary according to different management criteria.

## 5. Conclusions
The research introduced a generative design approach for drywall layout using fuzzy AHP. The results showed optimal alternatives with 37.5% reduction in waste, 7% in cost, and 54% in joint length compared to the median. This approach can be applied generically to other prefabricated construction scenarios.