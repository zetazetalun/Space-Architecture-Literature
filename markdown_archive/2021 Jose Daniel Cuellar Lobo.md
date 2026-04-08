# Building Information Modelling- (BIM-) Based Generative Design for Drywall Installation Planning in Prefabricated Construction

**Authors:** Jose Daniel Cuellar Lobo, Zhen Lei, Hexu Liu, Hong Xian Li, and SangHyeok Han  
**Published:** 14 July 2021  
**Journal:** Advances in Civil Engineering, Volume 2021  
**DOI:** 10.1155/2021/6638236

## Abstract
In prefabricated construction, building components are manufactured off-site before shipping to the site for installation. This study proposes a generative design approach that utilizes the optimization of the drywall installation layout to improve overall project efficiency. The framework includes a decision support module considering environmental, cost, and aesthetic aspects. Results showed improvements of 37.5% for environmental, 7% for cost, and 54% for aesthetic factors.

## 1. Introduction
Prefabrication takes a manufacturing style to produce building components off-site and ship them to the installation site. In the North American housing industry, wall panels are covered with sheathing materials (e.g., gypsum). This installation often involves cutting material, generating scrap waste which has negative economic and environmental impacts. BIM and generative design (GD) offer opportunities to optimize these processes through automation and parametrization.

## 2. Methodology
The research methodology consists of four analytical modules and one visualization module:
1. **Data Extraction:** Extracting geometric coordinates and material properties from BIM 3D models (Revit).
2. **Simulation-Based Design Algorithm:** Generating multiple feasible design alternatives for drywall layout.
3. **Heuristic Optimization:** Using a greedy algorithm to locally optimize material waste for each alternative.
4. **Decision-Making Support:** Implementing a fuzzy analytical hierarchy process (AHP) to rank alternatives based on environmental (waste), cost, and aesthetic (joint length) criteria.
5. **Visualization:** Returning results to BIM software (Dynamo) for visualization.

### Table 1: Sample cost information for drywall material and productivity
| Item | Cost/Price | Units | Source |
| :--- | :--- | :--- | :--- |
| CGC sheetrock 1/2 in x 4 ft. x 8 ft. | $13 | $CAD/unit | Home Depot |
| CGC sheetrock 1/2 in x 4 ft. x 10 ft. | $16 | $CAD/unit | Home Depot |
| CGC sheetrock 1/2 in x 4 ft. x 12 ft. | $19 | $CAD/unit | Home Depot |
| Drywall installation productivity | $50 | $CAD/hr | Industry partner |
| Drywall finishing productivity | $70 | $CAD/hr | Industry partner |
| Landfill tipping fee (NB) | $28 | $CAD/tonne | fundyrecycles.com |

## 3. Implementation and Case Study
A two-story wood residential house (53 wood frames) was used as a case study. 30 simulation cycles were initiated. Design rules included vertical/horizontal orientation, alignment with studs, staggered seams (1/8 in. gap), and avoiding seams near door/window openings.

## 4. Evaluation of Results and Discussion
- **Environmental Criterion:** Best design achieved a 37.5% waste reduction compared to the simulation median (16%).
- **Cost Criterion:** Best design achieved a 7% cost reduction compared to the median (CAD 5,580).
- **Aesthetic Criterion:** Best design achieved a 54% reduction in joint length compared to the median (231 lin. ft.).

## 5. Conclusions
The research introduced a generative design approach incorporating fuzzy AHP for drywall layout in prefabricated construction. The development benefits construction teams by reducing waste and shortening schedules through pre-cutting. Future work may include real-time field data and supply chain integration.
