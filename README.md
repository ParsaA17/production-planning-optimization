# Production Planning & Resource Optimization (Operations Research)

## Project Overview
This project formulates and solves a linear programming (LP) problem to optimize product mix and maximize overall operational profitability under resource constraints (labor and machine capacity).

## Mathematical Formulation
- **Objective Function:**
  $$\text{Maximize } Z = 50X_1 + 40X_2 + 70X_3$$
- **Constraints:**
  - Labor: $2X_1 + X_2 + 3X_3 \le 200$ hours
  - Machine: $X_1 + 2X_2 + X_3 \le 150$ hours
  - Non-negativity: $X_1, X_2, X_3 \ge 0$

## Results & Insights
- **Optimal Production:**
  - Product 1: 0 units
  - Product 2: 50 units
  - Product 3: 50 units
- **Maximum Profit:** $5,500
- **Sensitivity Analysis:**
  - Labor Shadow Price: $20/hr (indicates highest value on capacity expansion)
  - Machine Shadow Price: $10/hr
  - Both capacity constraints are binding (100% resource utilization).

## Tools Used
- Microsoft Excel (Solver Add-in, Simplex LP Method)
