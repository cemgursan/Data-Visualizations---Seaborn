# Seaborn Visualizations Repository

This repository provides a collection of data visualization examples using Seaborn along with related Python libraries. The project is organized into three main views, each demonstrating different techniques and datasets.

## Overview

The repository includes:

1. **Flights Data Visualization:**  
   - Uses the built-in "flights" dataset from Seaborn.
   - Demonstrates data pivoting to create a matrix for heatmaps.
   - Showcases various heatmap customizations, including annotations, centering, and clustermaps.
   - Combines bar plots and heatmaps in subplots to compare yearly flight data.

2. **Tips Data Regression and Distribution Analysis:**  
   - Utilizes the "tips" dataset to explore relationships between total bill, tip, and other variables.
   - Implements linear regression plots (`lmplot`) with customization options such as scatter markers, regression lines, order, and lowess smoothing.
   - Creates additional plots like violin plots to visualize the distribution of tips as a percentage of the total bill.

3. **Random Data Analysis:**  
   - Generates random datasets to illustrate histogram plotting with different normalization options.
   - Displays joint plots (both scatter and hexbin) to analyze bivariate distributions.
   - Provides a hands-on example of using Seaborn alongside Matplotlib for exploratory data analysis.

## Features

- **Heatmaps and Clustermaps:** Visualize matrix data with annotations, color mapping, and clustering.
- **Regression Analysis:** Use Seaborn's `lmplot` for exploring linear relationships and applying lowess smoothing.
- **Distribution Analysis:** Create histograms and joint plots to understand data distributions.
- **Customizations:** Examples of customizing plots with color palettes, marker styles, and subplot arrangements.

## Requirements

The project requires Python 3 and the following packages:

- numpy
- pandas
- scipy
- matplotlib
- seaborn

## Installation

Install the required packages using the provided `requirements.txt` file:

```bash
pip install -r requirements.txt
