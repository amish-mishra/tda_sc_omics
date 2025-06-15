# Topological Analysis of Immune Cell Subtypes Using Single-Cell RNA-seq

This project demonstrates the application of **Topological Data Analysis (TDA)** and **single-cell RNA-seq analysis** to uncover biologically meaningful insights from high-dimensional omics data. Using the PBMC 3k dataset, we identify immune cell subtypes, visualize their relationships, and explore topological structures using Mapper.

## Features
- Preprocessing and clustering of single-cell RNA-seq data
- Visualization of cell clusters using UMAP
- Differential gene expression analysis to identify marker genes
- Application of Mapper for topological insights into cell-type relationships

## Key Results
- Identification of immune cell subtypes (e.g., NK cells, monocytes)
- Marker gene analysis for biological interpretation
- Mapper graph highlighting topological structures in cell-type space

## Repository Structure
- `sc_analysis.ipynb`: Main analysis notebook
- `data/`: Contains the PBMC 3k dataset (optional)
- `results/`: Includes visualizations and Mapper graph
- `environment.yml`: Conda environment file for reproducibility

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/amish-mishra/tda_sc_omics.git
   cd tda_sc_omics
