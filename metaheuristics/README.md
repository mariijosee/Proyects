# Metaheuristics: Solving NP-Hard Optimization Problems

This module contains the implementation and empirical analysis of various optimization algorithms designed to navigate complex search spaces where exhaustive search is computationally infeasible. The focus is on balancing **exploration (diversification)** and **exploitation (intensification)**.


### Trajectory-Based Metaheuristics (Analisys)
Implementation of local search and trajectory algorithms applied to time-series segmentation and function optimization.
* **Algorithms:** Random Search, Hill Climbing (Steepest Ascent), and **Simulated Annealing**.
* **Key Focus:** Neighborhood management, local optima avoidance, and cooling schedule tuning.
* **Results:** Benchmarked convergence rates, where Simulated Annealing proved superior in escaping local optima in high-variance landscapes.

### Genetic Algorithms & Hyperparameter Tuning
Application of evolutionary computing to automate the fine-tuning of machine learning models.
* **Algorithms:** Genetic Algorithm (GA), Random Search, and Grid Search.
* **Key Focus:** Design of genetic operators (crossover, mutation, and selection), population dynamics, and computational cost analysis.
* **Results:** GA consistently found high-quality hyperparameter configurations faster than exhaustive Grid Search in high-dimensional spaces.

### Advanced Population Metaheuristics & Decision Boundaries
Utilizing advanced population-based methods to interpret "black-box" models and solve complex boundary detection problems.
* **Algorithms:** Evolved Genetic Algorithms and **Bayesian Optimization (via Optuna)**.
* **Key Focus:** Boundary detection through external classifier queries, multi-objective optimization, and elite coverage analysis.
* **Results:** Developed a methodology to approximate critical decision regions without internal model access, significantly improving model interpretability.

## 🛠️ Tech Stack
* **Languages:** Python (Jupyter Notebooks) / C++
* **Core Libraries:** NumPy, Pandas, Scikit-Learn, Optuna, Matplotlib/Seaborn.
* **Methodology:** Rigorous statistical validation using non-parametric tests (Wilcoxon/Friedman) and Big O complexity analysis.


