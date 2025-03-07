# What's Cooking? - Kaggle Competition

This repository contains code for the Kaggle "What's Cooking?" competition, where the goal is to predict a recipe’s cuisine based on its ingredients.

## Overview

- Data: JSON files with recipes (train/test), each containing "id", "cuisine", and "ingredients".
- Approach: Text-based feature engineering (e.g., TF-IDF) with two distinct models: SVC and XGBoost.

## Repository Structure
Whats_cooking_2.ipynb: Implements an SVC-based approach.
Whats_cooking_2xgb.ipynb: Implements an XGBoost-based approach.

## Notes
Hyperparameters and model settings can be adjusted within each notebook.
Consider cross-validation or other techniques to evaluate and compare model performance.

## License
Provided under the MIT License. See LICENSE file for details.
