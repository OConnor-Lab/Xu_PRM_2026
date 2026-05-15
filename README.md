# Xu_PRM_2026
### Publication repository for Xu &amp; O'Connor, PRM (2026)

This repository contains the scripts and data necessary for generating plots for the associated manuscript.

### Repository Structure
Analysis_Plots.ipynb: A Jupyter Notebook that provides a guided analysis workflow, including data processing and visualization.

data/: A directory containing the processed data files required for generating plots. Note: Raw simulation data files are not included due to space constraints.

### LAMMPS Version and Required Packages

This analysis is based on LAMMPS version lammps-22Dec2022. The following LAMMPS packages are required:

MOLECULE

KSPACE

EXTRA-PAIR

EXTRA-MOLECULE

SHOCK

NETCDF

### Requirements

The scripts require the following Python packages:

numpy

matplotlib

scipy

jupyter

pip install numpy matplotlib scipy jupyter

### Usage Guide

Prepare Data: Ensure the processed data files are placed inside the data/ folder.

Run the Notebook: Open and execute Analysis_Plots.ipynb to generate the figures for the manuscript.

### Notes

The Jupyter notebook provides step-by-step guidance on the analysis process.

Modify paths in the notebook if necessary to match your directory structure.

For any questions or issues, please contact the project maintainer.

### Citation

If you use this code or data in your research, please cite the following manuscript:
https://doi.org/10.1103/p577-s387
