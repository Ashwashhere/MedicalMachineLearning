# Pneumonia Detection & Classification Study

This repository contains a machine learning investigation focused on identifying pneumonia in patients using clinical data and X-ray features. The project is structured as a comparative study to evaluate the effectiveness of various classification algorithms in a medical diagnostic context.

## Project Overview

The objective of this investigation is to build, evaluate, and compare multiple machine learning models to determine which provides the most accurate prediction for pneumonia. The study moves from initial data preparation through to ensemble methods and hyperparameter tuning.

## Dataset Features

The project utilizes the `pneumonia_raw.csv` dataset, which includes the following attributes:

* **Demographics**: Patient ID, Age, and Gender.
* **Imaging Metrics**: X-ray Brightness, X-ray Contrast, and Silhouette Sign.
* **Clinical Indicators**: Max Consolidation Width/Height, Cavity Presence, Fluid Level, and Air Bronchograms.
* **Target Variable**: `Pneumonia` (Binary: yes/no).

## Technical Pipeline

The workflow is divided into logical sections within a Python notebook:

1. **Data Preparation**: Mounting Google Drive and loading data using `pandas`.
2. **Validation Strategy**: Implementing a simple 60/40 holdout approach with shuffling.
3. **Model Evaluation**: Testing multiple classification models, including:
* Decision Trees
* k-Nearest Neighbors (k-NN)
* Naive Bayes


4. **Optimization**: Exploring hyperparameters and ensemble techniques to improve performance.

## Requirements

To run this notebook, you will need:

* **Python 3**
* **Libraries**: `pandas`, `numpy`, `scikit-learn`
* **Platform**: Optimized for **Google Colab**.
