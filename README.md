# Maximum Coverage Facility Location Problem with Drones (MCFLPD)

This project focuses on solving the Maximum Coverage Facility Location Problem (MCFLP) using a drone-based delivery model. The goal is to select optimal facility locations and assign drone delivery routes to maximize demand coverage within range and capacity constraints.

##  Project Highlights

- Implemented a heuristic solution for MCFLPD using Python.
- Replaced traditional multiple single-demand drone trips with optimized multi-stop routes inspired by the Vehicle Routing Problem (VRP).
- Designed an integrated pipeline for facility selection, drone assignment, and route planning.

##  Methodology

1. **Facility Location Selection** – Facilities are chosen based on their potential to maximize demand coverage within a given radius.
2. **Drone Assignment** – Drones are allocated to selected facilities based on available capacity and coverage range.
3. **Routing Strategy** – Instead of serving one demand per trip, drones follow optimized paths covering multiple nearby demands, improving efficiency and reducing trips.

##  Tools & Libraries Used

- **Python**
- **NumPy**, **Pandas**
- **NetworkX** – for graph modeling
- **Matplotlib** – for visualization
- **PuLP / SciPy** – for optimization
- **Jupyter Notebook**

##  Results

- Efficient multi-demand routing reduces drone trips significantly.
- Improved overall demand coverage with fewer facilities.
- Adaptable approach for different scenarios by adjusting parameters like drone range, capacity, and facility budget.

