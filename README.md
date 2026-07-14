# Multidimensional Knapsack Problem — Investment Optimization

Optimization model for selecting investment projects under multiple resource constraints, implemented using Gurobi and Python.

## Problem Description

Selection of optimal investment portfolio across 16 projects considering:
- Multi-period budget constraints
- Cardinality limits (maximum number of projects)
- Mutual exclusion between conflicting projects
- Project dependencies
- Linearized synergies between complementary projects

## Objectives

- Maximize total return on selected projects
- Respect budget constraints across multiple periods
- Model real-world investment decision complexity

## Technologies

- Python
- Gurobi Optimizer
- Google Colab
- Pandas · NumPy · Matplotlib

## Files

- `Taller_Knapsack_Multidimensional_DR.ipynb` — Main notebook with model formulation and results
- `knapsack_proyectos.csv` — Project data (returns, costs, dependencies)
- `knapsack_capacidades.csv` — Budget capacity constraints per period

## Key Results

Model successfully identifies optimal project selection maximizing ROI while respecting all constraints across budget periods.

## Author

Daniela Rodríguez — [LinkedIn](www.linkedin.com/in/daniela-rodríguez-data-science-bi2004)
