# Penguin Species Clustering Analysis 🐧

![Penguin Illustration](https://imgur.com/orZWHly.png)

*Source: @allison_horst https://github.com/allisonhorst/penguins*

## Project Overview

This project supports a team of researchers who have been collecting data about penguins in Antarctica. Using unsupervised machine learning techniques, we help identify different penguin species groups in the dataset through clustering analysis.

## Dataset Information

**Origin**: Data were collected and made available by Dr. Kristen Gorman and the Palmer Station, Antarctica LTER, a member of the Long Term Ecological Research Network.

The dataset (`penguins.csv`) consists of 5 columns:

| Column | Description |
|--------|-------------|
| culmen_length_mm | Culmen length (mm) |
| culmen_depth_mm | Culmen depth (mm) |
| flipper_length_mm | Flipper length (mm) |
| body_mass_g | Body mass (g) |
| sex | Penguin sex |

## Problem Statement

The researchers have not been able to record the species of penguin, but they know that there are **at least three** species that are native to the region: **Adelie**, **Chinstrap**, and **Gentoo**. 

**Goal**: Apply data science skills to help identify groups in the dataset using clustering techniques.

## Methodology

1. **Data Preprocessing**: Clean and prepare the data by removing non-numeric columns and handling missing values
2. **Feature Scaling**: Standardize features using StandardScaler for optimal clustering performance
3. **Optimal Cluster Selection**: Use the Elbow Method with second differences to find the optimal number of clusters
4. **K-Means Clustering**: Apply K-Means algorithm to group penguins into species clusters
5. **Analysis**: Generate cluster statistics to understand the characteristics of each group


## Results

The analysis identifies distinct penguin groups based on physical characteristics, providing insights into the species composition of the Antarctic penguin population studied.
