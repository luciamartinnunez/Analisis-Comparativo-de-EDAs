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

