# EasyStats

EasyStats is a beginner-friendly R package created for basic data cleaning, summary statistics, and simple visualization. This package was created as a final project for LIS4370 to show how an R package is structured, documented, built, and shared through GitHub.

## Functions

This package includes three main functions:

1. `summary_stats()`  
   Calculates the mean, median, minimum, maximum, and standard deviation of a numeric vector.

2. `remove_missing()`  
   Removes missing values from a vector.

3. `simple_scatter()`  
   Creates a basic scatter plot using two numeric vectors.

## Installation

You can install this package directly from GitHub using `devtools`:

```r
install.packages("devtools")
library(devtools)

install_github("WesleyHuang7/EasyStats")
