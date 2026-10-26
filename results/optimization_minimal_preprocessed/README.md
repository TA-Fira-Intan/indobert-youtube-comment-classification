# IndoBERT Large P2 – Minimal Preprocessing Experiment

## Overview

This directory contains the evaluation results of the IndoBERT Large P2 model using a minimal text preprocessing strategy for Indonesian YouTube comment classification.

This experiment investigates the effect of reducing text preprocessing operations on classification performance while retaining the contextual information contained in the original comments.

## Files Description

| File | Description |
|---|---|
| `final_minimal_metrics.csv` | Summary of the model evaluation metrics. |
| `final_minimal_classification_report.csv` | Classification performance, including precision, recall, F1-score, and support for each class. |
| `final_minimal_confusion_matrix.csv` | Numerical confusion matrix showing actual and predicted class distributions. |
| `final_minimal_config.json` | Configuration details used in the minimal preprocessing experiment. |

## Evaluation Metrics

The model is evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- Macro-F1 Score

## Purpose

The results are used to analyze the impact of minimal text preprocessing on IndoBERT Large P2 classification performance and compare it with other text processing strategies evaluated in this research.
