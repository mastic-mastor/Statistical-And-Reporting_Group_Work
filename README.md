# Comparative Analysis of Statistical Computing Paradigms: Python, Julia, and R

## 📄 Project Abstract

This repository serves as a **comprehensive academic resource** and a deliverable for the group project in **Statistical Computing and Reporting (BIT4131)** at **Mount Kenya University**. The project comprises a parallel implementation of fundamental to advanced statistical computing algorithms across three prominent programming languages: **Python, Julia, and R**.

The core objective is to provide a rigorous, cross-language comparison of syntax, performance characteristics, and best practices for key statistical domains, including **linear modeling, optimization, simulation (Monte Carlo, MCMC), resampling techniques (Bootstrap, Cross-Validation), and Bayesian inference**. The repository contains **57 fully documented scripts** (19 per language) demonstrating equivalent methodological implementations.

-----

## 1\. Introduction and Research Scope

Modern data science relies heavily on diverse software environments. This project directly addresses the need for a comparative understanding of three primary languages used in statistical analysis and reporting:

  * **Python:** Valued for its general-purpose ecosystem and robust libraries (NumPy, SciPy, pandas).
  * **Julia:** Recognized for its high performance in numerical and scientific computing, leveraging its native support for multiple dispatch.
  * **R:** The established environment for statistical computing, renowned for its extensive package ecosystem and graphic capabilities (e.g., ggplot2).

The repository covers an integrated curriculum across **18 distinct statistical and computational topics**, providing a reference for practitioners and students seeking to understand language-specific implementations of core statistical methods.

-----

## 2\. Methodological Implementation and Comparative Topics

The project is structured around a curriculum of 18 statistical concepts, with each concept being implemented and validated in Python, Julia, and R.

### 2.1. Core Statistical and Computational Modules

The implementations range from foundational data structures to advanced statistical modeling:

| Module Index | Topic | Key Statistical Concept Demonstrated |
| :---: | :--- | :--- |
| **01-05** | **Foundational Computing** | Data types, control flow, functional programming, visualization. |
| **06-07** | **Parametric Methods** | Linear Regression (GLM), Probability Distributions, Hypothesis Testing. |
| **08-09** | **Numerical Optimization** | Unconstrained and Constrained Optimization techniques (e.g., gradient descent). |
| **10-12** | **Resampling and Simulation** | Monte Carlo Simulation, **Bootstrap** methods, Markov Chain Monte Carlo (MCMC I). |
| **13-15** | **Model Validation & Inference** | **Cross-Validation**, Non-parametric Density Estimation, **Bayesian Statistics**. |
| **16-19** | **Advanced Topics** | Advanced MCMC (MCMC II), Permutation Tests, Database Integration. |

### 2.2. Language-Specific Comparative Summary

| Feature | Python (General-Purpose) | Julia (Scientific Computing) | R (Statistical Analysis) |
| :--- | :--- | :--- | :--- |
| **Indexing** | **0-based**. Relies on **NumPy** for array manipulation. | **1-based**. Optimized for high performance, utilizing **multiple dispatch**. | **1-based**. Optimized for vector and matrix operations. |
| **Vectorization** | Achieved via **NumPy Broadcasting** (explicit). | Native **`.` operator** (explicit). | **Implicitly vectorized** by default. |
| **DataFrames** | **pandas** (`DataFrame` object). | **DataFrames.jl** package. | **Native** (`data.frame` or `tibble`). |
| **Performance** | Excellent for matrix ops when utilizing vectorized NumPy code. | **Superior** for general numerical and scientific computation. | Highly effective and **optimized** for statistical routines. |
| **Visualization** | **Matplotlib/Seaborn** (layered grammars). | **Plots.jl** (flexible backend system). | **Base Graphics** and the **ggplot2** Grammar of Graphics. |

-----

## 3\. Repository Structure and Navigation

The repository is logically partitioned by programming language to facilitate cross-reference and direct comparison of source code.

```
Statistical-And-Reporting-Group-Work/
├── README.md                          # Primary documentation and project overview
├── LICENSE                            # Project license
├── Python-files/                      # Python implementations (.py)
├── Julia-files/                       # Julia implementations (.jl)
└── R-files/                           # R implementations (.R)
```

**All files adhere to a consistent numbering scheme (`01_...` to `19_...`) to ensure topic-to-topic traceability across the three languages.**

-----

## 4\. Replication Environment and Setup

Replication of the analyses is straightforward, requiring the installation of the three environments and their respective statistical packages.

### 4.1. Prerequisites

A functional environment requires: **Python $\ge 3.8$, Julia $\ge 1.6$, and R $\ge 4.0$.**

### 4.2. Dependency Installation

The following packages are essential for running the scripts:

| Language | Key Packages | Installation Command Examples |
| :--- | :--- | :--- |
| **Python** | `numpy`, `pandas`, `scipy`, `scikit-learn` | `pip install numpy pandas scipy scikit-learn` |
| **Julia** | `DataFrames`, `Plots`, `GLM`, `Distributions`, `Optim` | `Pkg.add(["DataFrames", "Plots", "GLM", "Distributions", "Optim"])` |
| **R** | `ggplot2`, `dplyr`, `rstan`, `caret`, `RSQLite` | `install.packages(c("ggplot2", "dplyr", "rstan", "caret"))` |

### 4.3. Execution

Scripts can be executed directly from the command line within their respective directories:

```bash
# Example: Executing the Linear Models implementation
python Python-files/06_getting_data_and_linear_models.py
julia Julia-files/06_getting_data_and_linear_models.jl
Rscript R-files/06_getting_data_and_linear_models.R
```

-----

## 5\. Team Composition and Contribution Record

This project was a collaborative effort. The **18 core statistical modules** were distributed equally among the three contributors, with each member responsible for implementing their assigned modules across **Python, Julia, and R**.

### 5.1. Contributors

| Name | Registration Number | Primary Role / Expertise | Assigned Modules (Files) |
| :--- | :--- | :--- | :--- |
| **Faith Waihenya** | BSCCS/2023/57327 | Team Lead / Foundational & Modeling | Modules 1-6 (Files 1-6) |
| **Makena Debra** | BSCCS/2023/61880 | Statistical Modeling & Simulation | Modules 7-12 (Files 7-12) |
| **Thomas Obiri** | BSCCS/2023/60210 | Validation & Advanced Techniques | Modules 13-18 (Files 13-19) |


### 5.2. Project Status

The project is **100% complete** across all assigned modules. All 57 scripts have been verified and comply with the defined coding standards for clarity, documentation, and academic rigor.

**Status:** ✅ Ready for Final Submission

-----

## 6\. Acknowledgments and Licensing

This work was prepared for **Dennis Kaburu**, Course Instructor for **Statistical Computing and Reporting (BIT4131)** at **Mount Kenya University**.

The contents of this repository are provided solely for educational and non-commercial academic purposes. All rights are reserved by the listed contributors.
