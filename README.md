## Roller Coaster EDA Analysis

## Overview

This project explores a dataset of roller coasters from around the world, focusing on exploratory data analysis (EDA) to uncover patterns and insights. The dataset contains information such as coaster names, locations, manufacturers, speeds, heights, inversions, and more. Through visualizations and statistical summaries, we aim to analyze key features and trends in the roller
coaster industry.

## Features

    The analysis covers:
    Data cleaning and preprocessing (e.g., handling missing values, duplicates).
    Summary statistics of numerical attributes (e.g., speed, height).
    Trends in coaster introductions over the years.
    Relationships between various attributes (e.g., speed vs. height).
    Location-based analysis of coaster characteristics.
    Visualization of distributions and correlations.

## Dataset

    The dataset coaster_db.csv includes the following columns:
    coaster_name: Name of the roller coaster.
    Location: Geographical location of the coaster.
    Status: Operational status (e.g., Operating, Closed).
    Manufacturer: Manufacturer of the roller coaster.
    year_introduced: Year the coaster was introduced.
    latitude & longitude: Geographical coordinates.
    Type_Main: Main type of roller coaster (e.g., Steel, Wooden).
    opening_date_clean: Cleaned opening date of the coaster.
    speed_mph: Speed in miles per hour.
    height_ft: Height in feet.
    Inversions_clean: Number of inversions.
    Gforce_clean: G-force experienced on the coaster.

## Preprocessing

    Steps performed:
       Column Selection: Extracted relevant columns.
       Renaming Columns: Improved readability of column names.
       Data Type Conversion: Converted opening_date_clean to datetime.
       Missing Value Analysis: Checked for and documented missing values.
       Duplicate Removal: Identified and removed duplicates using specific subsets.

## Exploratory Analysis

    Visualizations
       Bar Chart: Top years when coasters were introduced.
       Histogram: Distribution of coaster speeds.
       Kernel Density Estimation (KDE): Speed distribution visualization.
       Scatter Plots:
        Speed vs. Height.
        Speed vs. Height with Year_Introduced hue.
       Pair Plot: Multivariate relationships across numerical features.
       Heatmap: Correlation between numerical attributes.
       Horizontal Bar Chart: Average speed by location.

## Insights

    Identified peak years for coaster introductions.
    Visualized the distribution and relationships of speed, height, inversions, and G-force.
    Highlighted correlations between attributes.
    Analyzed average speeds based on geographical locations.

## Tools & Libraries

    Python Libraries:
      pandas: Data manipulation and cleaning.
      numpy: Numerical computations.
      matplotlib: Basic visualizations.
      seaborn: Advanced statistical visualizations.
      Plotting Style: Used ggplot for consistent styling.

    Getting Started
    Prerequisites
    Ensure you have the following Python libraries installed:

    pandas
    numpy
    matplotlib
    seaborn
