# TOPSIS Method Implementation for Pre-trained Models

This repository contains an implementation of the **TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution)** method applied to model selection. The TOPSIS method is a multi-criteria decision-making technique that helps in ranking and selecting the best alternative based on multiple criteria.

## Task Overview

In this task, the TOPSIS method is applied to evaluate different machine learning models based on the following criteria:
- **Model Size (MB)**: The size of the model in megabytes.
- **Inference Time (s)**: The time taken by the model for inference (lower is better).
- **Fluency (BLEU Score)**: The fluency score of the model based on the BLEU metric (higher is better).

The models are ranked based on these criteria, and the ideal and worst case scenarios are computed. The best model is selected based on the **TOPSIS score**.

## Files

- `predictive_lab3.ipynb`: The Python script that implements the TOPSIS method.

## Libraries Used

- **numpy**: For matrix operations and numerical calculations.
- **pandas**: For data manipulation and storage.
- **matplotlib, seaborn**: For visualizing the results.
