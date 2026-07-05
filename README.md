# ML Training with Noisy Datasets

University project developed for the **Data Architectures** course of the Master's Degree in Computer Science at the University of Milano-Bicocca (A.Y. 2025/2026).

## Overview

The project studies how noise in training data affects the performance of machine learning models. Three binary-classification datasets are analyzed:

- Liver Patient Dataset
- Teen Mental Health Dataset
- Adult Income Dataset

Noise is progressively introduced into numerical, categorical, and ordinal features of the training sets. The experiments compare the robustness of three models: **Decision Tree**, **Neural Network**, and **Support Vector Machine**. Accuracy, balanced accuracy, precision, recall, and F1-score are used for evaluation.

## Repository contents

- `liverDataSet.ipynb`, `teenDataset.ipynb`, `AdultIncomeDataset.ipynb`: dataset analysis and experiments
- `graficiConfronto.ipynb`: comparison charts
- `Datasets/`: datasets used in the experiments
- `Relazione/`: complete report and results
- `Presentazione/`: project presentation

## Setup

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Authors

Tommaso Baggio, Samuele Bergamin, Andrea Ciacci.
