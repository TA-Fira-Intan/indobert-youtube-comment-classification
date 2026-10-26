# Final IndoBERT Large P2 (Max Length 256)

## Overview
This directory contains the final evaluation results of the IndoBERT Large P2 model using a maximum sequence length of 256 tokens for Indonesian YouTube comment classification.

The model configuration was selected based on the initial model variant and maximum sequence length experiments, followed by final fine-tuning and evaluation.

## Files Description

| File | Description |
|---|---|
| `final_metrics.csv` | Summary of the final model evaluation metrics. |
| `classification_report.csv` | Precision, recall, F1-score, and support for each classification category. |
| `confusion_matrix.csv` | Numerical confusion matrix showing actual and predicted classes. |
| `confusion_matrix.png` | Visualization of the confusion matrix. |
| `test_predictions.csv` | Model predictions on the test dataset. |

## Model Configuration
- Model: IndoBERT Large P2
- Maximum sequence length: 256 tokens
- Task: Five-class Indonesian YouTube comment classification

## Evaluation
The model was evaluated using accuracy, precision, recall, and Macro-F1 score. The detailed results are provided in the corresponding CSV files.

## Notes
These files represent the final evaluation outputs for the IndoBERT Large P2 model with a maximum sequence length of 256.
