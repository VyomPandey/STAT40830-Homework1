# STAT40830 - Homework 1

**Author:** Vyom Pandey (24203476)  
**Course:** STAT40830  
**Date:** 18 June 2025  

---

## Overview

This repository contains the Quarto analysis for **Homework 1**, which investigates the relationship between **temperature** and **ozone concentration** using R's built-in `airquality` dataset. The objective is to demonstrate proficiency in:

- Data cleaning and exploration  
- Statistical summarization  
- Data visualization  
- Version control with Git and GitHub

---

## Dataset Description

The `airquality` dataset includes **daily air quality measurements in New York City** from **May to September 1973**. Key variables analyzed:

- **Ozone**: Ozone concentration (ppb)
- **Temp**: Temperature (°F)

---

## Analysis Highlights

- Removal of missing values using `na.omit()`
- Summary statistics (mean, standard deviation, count) for Ozone and Temperature
- Scatterplot with **linear regression line** to visualize correlation
- Pearson **correlation coefficient** between temperature and ozone
- Missing data summary table for transparency

---

## Tools & Packages Used

- `dplyr` for data summarization
- `ggplot2` for plotting
- `knitr` for tables
- `base R` for correlation and data inspection

---

## Key Insight

There is a **strong positive correlation** between temperature and ozone levels in the dataset. Higher temperatures are associated with increased ozone concentrations, highlighting the importance of monitoring air quality during hot weather—especially in the context of **climate change**.


