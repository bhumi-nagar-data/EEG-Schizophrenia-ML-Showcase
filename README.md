# ML Project Showcase: EEG-Inspired Schizophrenia Analysis

## Overview
This repository offers a portfolio-ready, comprehensive data analysis and machine learning project inspired by EEG-based schizophrenia classification. The goal is to showcase a robust, real-world ML workflow—from data validation and preprocessing to model training and assessment—while deliberately excluding sensitive data and unpublished research materials.

This project showcases both **data analysis** and **machine learning** components of applied healthcare analytics.

## What This Project Shows
- Structured workflows for data validation and cleaning  
- Leakage-free train/test splitting strategy  
- Strategies for feature curation and selection in biomedical signals  
- End-to-end preprocessing with a pipeline-based design  
- Training and comparing multiple classification models  
- Model evaluation using cross-validation and standard performance metrics  
- Basic model interpretation via selected feature analysis  

## High-Level Pipeline (Conceptual)
The complete workflow includes:
1. Data quality checks and cleaning (missing values, duplicates, constants).
2. Careful separation of features and target to prevent data leakage. 
3. The train/test split was done before any scaling or imputation.  
4. Identification of numerical and categorical features.  
5. Preprocessing using a column-wise transformation pipeline.  
6. Feature curation and statistical feature selection.  
7. Training several candidate models.  
8. Model evaluation with stratified cross-validation.  
9. Final model selection and evaluation with standard metrics.  
10. Post-processing and inspecting selected features.  

> Note: This public version intentionally provides a high-level summary of the methodology and does not reveal the full research pipeline.

## Results (High-Level)
This project delivered **robust and consistent classification results** across multiple experimental runs.  
For confidentiality reasons, this repository does not reveal precise final research metrics or figures.  
Sample visualizations and demo results might be placed in the `images/` folder solely for illustration.

## Tech Stack
- Python
- pandas, NumPy
- scikit-learn
- matplotlib / seaborn
- Jupyter Notebook  

## Repository Note
This is a **public showcase repository**. It intentionally excludes:
- Original datasets
- Complete experimental pipelines
- Final research figures and metrics  

A comprehensive and detailed version of this project is kept **privately** for academic collaboration and research publication.

## Repository Structure
- `notebooks/` — Demo notebooks with synthetic or sample data
- `src/` — Template scripts for preprocessing and modeling
- `images/` — Sample visualizations (non-sensitive)
- `docs/` — Additional documentation
