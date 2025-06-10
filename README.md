# Understanding Media Driven Misinformation on X Through Topic Classification

**Bachelor Project**  
*Authors: Esben Kloster & Lucas Nicolaisen*

## Overview

This repository contains the complete analysis and results for a bachelor project investigating media-driven misinformation on X (formerly Twitter) through topic classification using BART Large MNLI. The project analyzes misinformation patterns and provides model evaluation across different domains.

## Project Structure

### Topic Classification (Main Project)
The core analysis is contained in `complete_dataset_analysis.ipynb`, which generates:
- **`graphs/`** - All visualizations and performance charts
- **`analysis_results/`** - Statistical analysis and classification reports

Additional analysis folders provide model performance insights:
- `experiment_results/` - Extended experimental data
- `hyperparameter_results/` - Parameter optimization analysis  
- `validation_results/` - Model validation metrics
- `validation_results_with_economics/` - Economics domain validation

### Media Claim Relation (Development Attempts)
Documentation of our development process and unsuccessful attempts at source reliability classification:
training_analysis
- `model_comparison_analysis/` - Various model approaches tested
- `confidence_analysis/` - Confidence evaluation experiments
- `roberta_unreliable_source_tuning/` - RoBERTa fine-tuning experiments
- `metadata_analysis_results/` - Metadata feature exploration attempts


## Key Technologies

- **Primary Model**: BART Large MNLI for zero-shot topic classification
- **Secondary Analysis**: RoBERTa fine-tuning for source reliability
- **Framework**: PyTorch with Hugging Face Transformers

## Main Datasets

- `for_bsc_project.csv` - Primary analysis dataset with merged community ratings
- `*_labeled.xlsx` - Training, validation, and test sets with manual annotations
- `rel_typ.xlsx` - Sample of media-claim manual annotations

*Note: Original large community rating datasets and trained models not included due to GitHub size limitations.
Model training script is available and the rapport contains a link to the Community Notes data*


## Setup

To explore the code or reproduce analysis:
```bash
git clone https://github.com/esbenkloster/Bachelor_Project.git
cd Bachelor_Project
conda env create -f environment.yml
conda activate bachelor_env
