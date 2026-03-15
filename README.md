# UM-CISC7107 Assignment 2

A teaching notebook that demonstrates how features relate to outcomes and to each other, building from simple visualizations up to **relation networks** — outcome-centered graphs built from Spearman correlations.

## Datasets

| Dataset | Target | Task | Model |
|---|---|---|---|
| [World Happiness Report](https://worldhappiness.report/) | Happiness Score (0–8) | Regression | XGBoost |
| [Lung Cancer](https://www.kaggle.com/) | Cancer Yes/No | Classification | Decision Tree |
| [NSL-KDD](https://www.kaggle.com/datasets/hassan06/nslkdd) | Attack/Normal | Classification | SVM (RBF) |

## Structure

Each dataset follows the same flow:

1. **Load & explore** — understand the features and target
2. **Hero visualization** — the single plot that best reveals the data's story (scatter plots, box plots, etc.)
3. **Relation network** — a single picture combining feature→outcome and feature↔feature correlations
4. **Modeling** — train a model and evaluate predictions

## Quick Start

1. Upload the notebook to [Google Colab](https://colab.research.google.com/)
2. Run all cells — datasets download automatically
