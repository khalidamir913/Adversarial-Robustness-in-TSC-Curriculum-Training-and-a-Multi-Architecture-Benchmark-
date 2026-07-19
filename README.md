# Adversarial-Robustness-in-TSC-Curriculum-Training-and-a-Multi-Architecture-Benchmark-
Author Khalida Mir Alam
# CurAT-LSTM-FCN: Curriculum Adversarial Training for Time Series Classification

Code accompanying the paper "Adversarial Robustness in Time Series Classification: 
Curriculum Training, Recurrent Resilience, and a Multi-Architecture Benchmark."

## Contents
- `CurAT_LSTM_FCN_experiments.ipynb` — full training and evaluation pipeline
  (ResNet, FCN, LSTM, LSTM-FCN Vanilla, CurAT-LSTM-FCN) across 15 UCR datasets
  and 4 adversarial attacks (FGSM, BIM, PGD, C&W).
- `Results_By_Attack.xlsx` — raw clean and adversarial accuracy per model/dataset/attack.
- `Statistical_Results.xlsx` — Friedman, Wilcoxon (Holm-corrected), and average-rank results.

## Requirements
TensorFlow 2.20.0, NumPy 2.0.2. Developed and tested on Google Colab (T4 GPU).

## Usage
Datasets must be downloaded separately from the UCR Time Series Archive
(https://www.cs.ucr.edu/~eamonn/time_series_data_2018/) and placed in the
paths specified in the notebook.
