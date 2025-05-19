# Comparative Analysis of Univariate and Bivariate Estimation of Distribution Algorithms (EDAs)

This repository contains the implementation and experimental evaluation of several Estimation of Distribution Algorithms (EDAs), including the Univariate Marginal Distribution Algorithm (UMDA) and MIMIC, as well as a baseline Genetic Algorithm (GA), applied to classical binary optimization problems.

## 📌 Project Overview

This project aims to investigate the performance and structural differences between univariate and bivariate EDAs when solving benchmark combinatorial problems such as OneMax and Knapsack. The goal is to assess convergence speed, population diversity, and solution quality, as well as to visualize the probabilistic models learned by each approach.

## 🧪 Methodology

- **Algorithms Implemented**:
  - UMDA (Univariate Marginal Distribution Algorithm)
  - MIMIC (Mutual Information Maximizing Input Clustering)
  - A baseline Genetic Algorithm (GA)

- **Problems Solved**:
  - [x] OneMax
  - [x] Knapsack
  - [ ] MaxSAT (planned for future extension)

- **Metrics Evaluated**:
  - Convergence generation
  - Average and standard deviation of fitness
  - Structural analysis of learned distributions

- **Technologies Used**:
  - Python 3
  - Numpy, Matplotlib, Pandas

## 📊 Results Summary

The results show that:
- **UMDA** is highly efficient in separable problems like OneMax, achieving rapid convergence with simple models.
- **MIMIC** performs robustly across both separable and structured problems, due to its ability to capture conditional dependencies.
- **GA** improves more slowly and lacks explicit probabilistic modeling.

A detailed explanation of the results, together with visualizations (heatmaps, convergence plots), can be found in the report.

## 📁 Repository Structure
📦 Comparative-EDAs/

├── data/

│ └── ... # CSV files with recorded generations, fitness, etc.

├── figures/

│ └── ... # Plots for convergence and model structure

├── src/

│ ├── eda_umda.py

│ └── ga_baseline.py

├── documentation/

│ ├── eda_experiments_onemax.html

│ └── knapsack_experiment_local.html

├── report/

│ ├── Seminar_7.pdf

│ └── Seminario_7.pdf

├── README.md

└── requirements.txt


## 📄 Report

A detailed explanation of the methodology, theoretical background, and interpretation of results is available in the Spanish version [project report](./report/Seminario_7.pdf) and a shorter version in English [project report](./report/Seminar_7.pdf). The report includes a comparison of EDAs in terms of convergence behavior, diversity, and learned distribution models.


## 🔁 Reproducibility

All experiments are fully reproducible. Notebooks scripts are provided to re-run the training and generate plots. The full set of experiments and evaluation results are available in this GitHub repository:  
📎 [https://github.com/luciamartinnunez/Analisis-Comparativo-de-EDAs](https://github.com/luciamartinnunez/Analisis-Comparativo-de-EDAs)^[GitHub repository with full code and experiments].

## 📚 References

[Bonet et al., 1996] Bonet, J. S. D., Jr., C. L. I., and Viola, P. A. (1996). MIMIC: Finding
Optima by Estimating Probability Densities. In Mozer, M., Jordan, M. I., and Petsche, T.,
editors, Advances in Neural Information Processing Systems 9, NIPS, Denver, CO, USA,
December 2-5, 1996, pages 424–430. MIT Press.

[Krejca and Witt, 2020] Krejca, M. S. and Witt, C. (2020). Lower bounds on the run time
of the Univariate Marginal Distribution Algorithm on OneMax. Theoretical Computer
Science, 832:143–165. Theory of Evolutionary Computation.

[Larra˜naga and Lozano, 2002] Larrañaga, P. and Lozano, J. A., editors (2002). Estimation
of Distribution Algorithms. Genetic Algorithms and Evolutionary Computation. Springer.

[M¨uhlenbein and Paaß, 1996] M¨úhlenbein, H. and Paaß, G. (1996). From recombination of
genes to the estimation of distributions I. Binary parameters. In Voigt, H.-M., Ebeling,
W., Rechenberg, I., and Schwefel, H.-P., editors, Parallel Problem Solving from Nature —
PPSN IV, pages 178–187, Berlin, Heidelberg. Springer Berlin Heidelberg.

[M¨uhlenbein, 1997] M¨uhlenbein, H. (1997). The Equation for Response to Selection and Its
Use for Prediction. Evolutionary Computation, 5(3):303–346.

[Soloviev et al., 2024] Soloviev, V. P., Larrañaga, P., and Bielza, C. (2024). EDAspy: An
extensible python package for estimation of distribution algorithms. Neurocomputing,
598:128043.


## 📌 License

This project is distributed under the MIT License.

