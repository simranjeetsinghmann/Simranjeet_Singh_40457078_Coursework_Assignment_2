# Lung Cancer Bioinformatics Analysis Project

## Overview

This project contains Python code and datasets for analyzing lung cancer clinical and proteomics data sourced from The Cancer Genome Atlas (TCGA) and Cancer Proteome Atlas (TCPA). The repository includes functionality to merge clinical and protein expression datasets by patient barcode, perform exploratory data analysis, handle missing values, and simulate DNA digestion and prognostic scoring based on biomarker data.

## Contents

- `Simranjeet_Singh_40457078_Coursework_Assignment_2.ipynb`: Jupyter notebook with comprehensive analysis scripts for:
  - Merging clinical and proteomic data using patient barcode
  - Interactive attribute summary and scatter plotting
  - Missing data reporting and filtering
  - DNA digestion simulation with multi-enzyme support
  - Prognostic scoring of cancer patients based on biomarker levels, stage, and age

- `Q3_TCGA_LUAD_Clinical.csv`: Clinical dataset with patient information for lung adenocarcinoma.
- `Q3_TCGA_LUAD_protein.csv`: Protein expression data for overlapping lung cancer patients.
- `chr21.fasta`, `chr22.fasta`: Reference DNA sequences used in digestion simulations.

## Usage Instructions

1. Ensure required Python packages are installed:
    ```
    pip install pandas matplotlib
    ```

2. Open the notebook in JupyterLab or Jupyter Notebook and run the cells to perform the analysis.

3. Follow prompts to explore data summaries, generate plots, and export cleaned datasets.

## Project Description

This project helps integrate heterogeneous biological datasets from clinical and proteomic sources to gain insights into lung cancer. It includes rigorous merging based on unique patient identifiers and detailed handling of missing data. Users can interactively explore relationships among patient attributes with summary statistics and scatter plots.

Additionally, the repository implements a DNA digestion simulation tool for sequences from chromosomes 21 and 22, simulating fragment size distributions from multiple restriction enzymes. A prognostic scoring function stratifies patients based on biomarker expression and clinical stage, supporting translational research efforts.

## Author

Simranjeet Singh – Graduate Researcher in Bioinformatics

