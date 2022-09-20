# CAPoly: Bayesian Cluster Analysis of Polygons via a Double Dirichlet Mixture Model

## Introduction
`CAPoly` is an R package for landmark-based Bayesian clustering of closed polygonal chains, relying on intrinsic shape features (i.e. relative interior angles and relative side lengths). The algorithm accepts a matrix, list, or dataframe containing the coordinates of closed polygonal chains, extracts the aforementioned inherent shape features, and clusters them by approximating posterior distributions using a Markov chain Monte Carlo method.

## Installation
Execute one of the following commands in R, depending on your preference:

```R
# Install from The Comprehensive R Archive Network (CRAN)
install.packages("CAPoly")

# Install from GitHub
if (!require("devtools")) install.packages("devtools")
devtools:install_github("kevinwjin/CAPoly")
```
## Usage
*(under development)*

## Arguments
*(under development)*

## Contents
* `code/main.R` - Execution script
* `code/model.R` - Implementation of the model in R
* `code/model.cpp` - Faster implementation of the model in C++ *(recommended)*
* `code/shape_generation.R` - Functions for generating simulated data
* `data/` - Real-world datasets

## Prerequisites
* `Rcpp` - Faster MCMC approximation
* `sf` - Polygon handling when generating simulated data

## Examples
*(under development)*

## Contributors
* [Qiwei Li](https://profiles.utdallas.edu/qiwei.li)
* [Kevin Jin](https://www.linkedin.com/in/kevin-w-jin/)
* [Huimin Li](https://www.linkedin.com/in/huimin-li-19789248)
