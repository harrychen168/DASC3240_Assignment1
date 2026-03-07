# DASC3240_Assignment1

***Welcome to visit my first project on GitHub :) \
This project is about static plots analysis for tree community data in
Hong Kong forest plots.***

## 01. Project Overview 

This repository contains **R code** for analyzing **tree species
composition and abundance** in 28 Hong Kong forest plots. The analysis
includes:

1.  Visualization of total dominant tree species abundance vs forest age
    (**boxplot + jitter plot**).

2.  USe **PCA** and **NMDS** to visualize tree species composition
    across different forest age groups. \

## 02. Data Files 

1.  **`Abbas_2019_TableS4_ed1.csv`:** Metadata of forest plots
    (including AGE_MEDIAN for forest age).

2.  **`Abbas_2019_TableS4_ed2.csv`:** Dominant tree species abundance
    data for each forest plot. \

## 03. Code Description 

The core R script (**`L08_Assignments-1.Rmd`**) implements: Data
preprocessing (transpose & compositional data conversion). Total
abundance calculation and visualization (boxplot + jitter plot).
PCA/NMDS analysis for species composition (Bray-Curtis dissimilarity for
NMDS). \

## 04. Environment Requirements 

Install the required R packages before running the code: *{
`install.packages(c("tidyverse", "vegan"))` }*

##  05. Usage 

Place the CSV data files in a folder (or adjust the file path in the
code). Run the R script/Rmd file to generate the required plots. All
plots follow the assignment requirements.

##  06. License 

This project is licensed under the **`MIT License`**. Please refer to
the LICENSE file for details.

*Thank you for time and support :))*
