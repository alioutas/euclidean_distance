# Euclidean Distance of 3D Point Cloud Clustered data

This repository contains an interactive analysis of Euclidean distance calculations, performance benchmarking between pure Python and NumPy, and a 2D projection visualization of a 3D point cloud dataset with centroid distance calculations.

## Project Structure

*   `euclidean_distance.ipynb`: The main interactive Jupyter notebook containing:
    1.  Mathematical definition and formulation of Euclidean distance.
    2.  Pure Python vs. vectorized NumPy implementations.
    3.  Execution benchmarking comparisons.
    4.  2D distance gradient simulations.
    5.  3D Point Cloud data load and 2D spatial visualization (preserving coordinate proportions).
    6.  Pairwise cluster centroid distance matrices.
*   `point_cloud_dataset.csv`: The 3D point cloud coordinate dataset containing cluster labels (`0` to `21`) and noise (`-1`).
*   `.gitignore`: Prevents committing local system caches and checkpoints.

## Installation & Setup (Conda Environment)

To run the notebook locally with all the necessary dependencies, set up a Conda environment using:

```bash
# 1. Create a new Conda environment named 'distance_env' with Python 3.12
conda create -n distance_env python=3.12 -y

# 2. Activate the environment
conda activate distance_env

# 3. Install dependencies via conda-forge
conda install -c conda-forge numpy pandas scipy matplotlib notebook ipykernel -y
```

Alternatively, you can install the packages using `pip` within your environment:

```bash
pip install numpy pandas scipy matplotlib notebook ipykernel
```

## Running the Notebook

Once your environment is active, start the Jupyter Notebook server:

```bash
jupyter notebook
```

Open `euclidean_distance.ipynb` in the browser and run all cells to reproduce the analysis.
