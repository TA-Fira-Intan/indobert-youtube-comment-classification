# IndoBERT-Based Classification of Indonesian YouTube Comments

Comparative evaluation of six IndoBERT variants and text processing strategies for classifying Indonesian YouTube comments based on indications of risk related to the Indonesian Electronic Information and Transactions Law (UU ITE).

## 1. Research Overview

This research investigates the performance of IndoBERT models in classifying Indonesian YouTube comments into five annotation categories. It evaluates different IndoBERT variants and text processing strategies to identify their effects on classification performance.

The study focuses on informal Indonesian language, contextual expressions, and the challenges of distinguishing neutral comments, criticism, offensive content, and potentially harmful expressions.

## 2. Research Objectives

- Compare the performance of six IndoBERT model variants.
- Identify the optimal model variant and maximum sequence length.
- Evaluate the effect of hyperparameter optimization.
- Investigate the impact of contextual embedding and text processing strategies.
- Analyze classification performance using standard evaluation metrics.
- Examine incorrect predictions through model error analysis.

## 3. Classification Categories

The dataset uses five research annotation categories:

| Label | Category |
|---|---|
| C0 | Neutral |
| C1 | Negative Criticism or Opinion |
| C2 | Offensive Content |
| C3 | Indications of Insults or Hate |
| C4 | Ambiguous Expressions |

These categories represent research annotation labels and do not constitute legal determinations of UU ITE violations.

## 4. IndoBERT Model Variants

Six IndoBERT variants are evaluated:

- IndoBERT Lite P1
- IndoBERT Lite P2
- IndoBERT Base P1
- IndoBERT Base P2
- IndoBERT Large P1
- IndoBERT Large P2

## 5. Experimental Scenarios

The experiments are organized into the following stages:

1. IndoBERT variant and maximum sequence length experiments.
2. IndoBERT Large variant comparison.
3. Maximum sequence length selection for IndoBERT Large P2.
4. Hyperparameter optimization.
5. Contextual embedding experiment.
6. Text chunking experiment.
7. Text slicing experiment.
8. Minimal preprocessing experiment.
9. Final fine-tuning and model error analysis.

## 6. Repository Structure

```text
indobert-youtube-comment-classification/
├── dataset/
│
├── notebooks/
│   ├── 01_EDA_Dataset_Anotasi_Pakar.ipynb
│   ├── 02_Balancing_Dataset.ipynb
│   ├── 03_Preprocessing_Dataset.ipynb
│   ├── 04_IndoBERT_Variants_and_Max_Length_Experiments.ipynb
│   ├── 05_IndoBERT_Large_Variants_Experiments.ipynb
│   ├── 06_IndoBERT_Large_P2_Max_Length_Selection.ipynb
│   ├── 07_Hyperparameter_Optimization.ipynb
│   ├── 08_Contextual_Embedding_Experiment.ipynb
│   ├── 09_Text_Chunking_Experiment.ipynb
│   ├── 10_Text_Slicing_Experiment.ipynb
│   ├── 11_Preprocessing_Minimal_IndoBERT.ipynb
│   ├── 12_Minimal_Preprocessing_Experiment.ipynb
│   └── 13_Final_Fine_Tuning_and_Error_Analysis.ipynb
│
├── results/
│   ├── final_large_p2_max256/
│   ├── optimization_large_p2/
│   └── optimization_minimal_preprocessed/
│
├── .gitignore
├── README.md
└── requirements.txt
```

## 7. Evaluation Metrics

Model performance is evaluated using:

- Accuracy
- Precision
- Recall
- Macro-F1 Score

Macro-F1 is used to assess classification performance across all categories.

## 8. Limitations

The classification results are intended for research and preliminary identification purposes. Model predictions should not be interpreted as definitive legal judgments or proof of violations of applicable laws.

## 9. Reproducibility

The Jupyter notebooks document the dataset preparation, model training, experimental procedures, and final evaluation process.

The `requirements.txt` file lists the Python libraries required to reproduce the research environment.

Experimental evaluation outputs, including classification reports, confusion matrices, and model metrics, are provided in the `results/` directory.

Dataset availability is documented in the `dataset/` directory, subject to applicable data-sharing and privacy considerations.
