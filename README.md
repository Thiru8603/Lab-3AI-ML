# Student Clustering Analysis

This project performs clustering analysis on student data to identify patterns in student performance based on their studied credits and number of previous attempts.

## Overview

The analysis includes the following steps:

1. Reading student data from a local CSV file.
2. Performing dimensionality reduction with Principal Component Analysis (PCA).
3. Scaling the data and computing the explained variance.
4. Clustering the data using KMeans and Hierarchical clustering.
5. Visualizing clusters using scree plot and dendrogram.
6. Exploring the distribution of students within clusters for both KMeans and hierarchical clustering.
7. Considering the interpretability of the features associated with each principal component.

## Prerequisites

- R installed on your machine.
- Required R packages: `cluster`, `ggplot2`.

## Getting Started

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your_username/student-clustering-analysis.git
    ```

2. Navigate to the project directory:

    ```bash
    cd student-clustering-analysis
    ```

### Usage

1. Run the R script `student_clustering_analysis.R`.

    ```bash
    Rscript student_clustering_analysis.R
    ```

2. Check the output visualizations and analysis.

## File Structure

- `student_clustering_analysis.R`: R script for performing clustering analysis.
- `studentInfo.csv`: CSV file containing student data.
- `README.md`: This file.

## Contributing

Contributions are always welcome! Please create an issue or pull request if you find any problems or have suggestions for improvements.

