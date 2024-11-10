#  Data Generation and Visualization

This Jupyter notebook demonstrates how to generate synthetic data using the `make_blobs` function from `sklearn.datasets`, create a pandas DataFrame, and visualize the generated data with a scatter plot using `matplotlib`.

## Contents

### 1. Data Generation
- **Libraries Used**:
  - `numpy`: For numerical operations.
  - `sklearn.datasets`: To generate synthetic datasets.
  
- **Key Parameters**:
  - `n_samples`: Total number of samples to generate (set to 3500).
  - `n_classes`: Number of classes (set to 5).
  - `centers`: Locations of the cluster centers.

### 2. DataFrame Creation
- A pandas DataFrame is created from the generated data, which includes:
  - `x1` and `x2`: Features of the data points.
  - `target`: Class labels corresponding to each data point.

### 3. Data Visualization
- The data is visualized using a scatter plot:
  - Each class is represented by a different color.
  - Axes are labeled, and a legend is included for clarity.

## How to Run the Notebook
1. Ensure you have the required libraries installed:
   ```bash
   pip install numpy pandas matplotlib scikit-learn