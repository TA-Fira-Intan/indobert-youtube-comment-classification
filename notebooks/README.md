# Research Notebooks

This directory contains Jupyter notebooks used to document the dataset preparation, IndoBERT model experiments, and final model evaluation for Indonesian YouTube comment classification.

## Notebook Structure

### 1. Dataset Preparation

| Notebook | Description |
|---|---|
| `01_EDA_Dataset_Anotasi_Pakar.ipynb` | Exploratory data analysis of the expert-annotated dataset, including label distribution and data characteristics. |
| `02_Balancing_Dataset.ipynb` | Dataset balancing process to obtain an equal number of samples across the five annotation categories. |
| `03_Preprocessing_Dataset.ipynb` | Text preprocessing and preparation of the balanced dataset for model training. |

### 2. IndoBERT Model Experiments

| Notebook | Description |
|---|---|
| `04_IndoBERT_Variants_and_Max_Length_Experiments.ipynb` | Initial experiments to compare IndoBERT variants and maximum sequence lengths. |
| `05_IndoBERT_Large_Variants_Experiments.ipynb` | Further evaluation of IndoBERT Large variants. |
| `06_IndoBERT_Large_P2_Max_Length_Selection.ipynb` | Selection of the optimal maximum sequence length for IndoBERT Large P2. |
| `07_Hyperparameter_Optimization.ipynb` | Experiments to evaluate different hyperparameter configurations. |
| `08_Contextual_Embedding_Experiment.ipynb` | Evaluation of contextual embedding strategies. |
| `09_Text_Chunking_Experiment.ipynb` | Evaluation of text chunking as a strategy for processing comments. |
| `10_Text_Slicing_Experiment.ipynb` | Evaluation of text slicing strategies. |
| `11_Preprocessing_Minimal_IndoBERT.ipynb` | Implementation of minimal preprocessing for IndoBERT. |
| `12_Minimal_Preprocessing_Experiment.ipynb` | Evaluation of model performance using minimal text preprocessing. |

### 3. Final Model Evaluation

| Notebook | Description |
|---|---|
| `13_Final_Fine_Tuning_and_Error_Analysis.ipynb` | Final fine-tuning of the selected model configuration and analysis of incorrect model predictions. |

## Notes

- The notebooks are organized according to the research workflow.
- Each notebook documents the corresponding experimental procedure and results.
- Final evaluation outputs are available in the `results/` directory.
