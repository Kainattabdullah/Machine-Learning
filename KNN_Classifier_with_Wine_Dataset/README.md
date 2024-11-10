# K-Nearest Neighbors Classifier

## Overview

This Jupyter Notebook implements a K-Nearest Neighbors (KNN) classifier using the Wine dataset from the `sklearn.datasets` module. The notebook explores how the choice of `k` (number of neighbors) and the distance metric (`p` value) affect the accuracy of the model.

## Contents

1. **Imports**: Necessary libraries for data manipulation and visualization.
2. **Data Loading**: Loading the Wine dataset and preparing the feature and target variables.
3. **Data Splitting**: Dividing the dataset into training and testing sets.
4. **KNN Implementation**:
   - Testing different values of `k` (from 1 to 25) to find the optimal number of neighbors.
   - Comparing accuracy scores using different `p` values (1, 2, and 3) for distance calculations.
5. **Visualization**: Plotting accuracy against `k` values to visualize performance.

## Requirements

To run this notebook, ensure you have the following Python packages installed:

- numpy
- matplotlib
- scikit-learn

You can install these packages using pip:

```bash
pip install numpy matplotlib scikit-learn