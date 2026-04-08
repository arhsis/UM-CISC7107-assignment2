# UM-CISC7107 Assignment 2

A notebook covering **exploratory data analysis (EDA)**, **relation networks**, **graph neural networks**, and **deep learning on CIFAR-10**.

## Datasets

| Dataset | Target | Task |
|---|---|---|
| [World Happiness Report](https://worldhappiness.report/) | Happiness Score (0–8) | Regression / EDA |
| [Lung Cancer](https://www.kaggle.com/) | Cancer Yes/No | Classification / EDA |
| [Cora](https://linqs.org/datasets/#cora) | Paper topic (7 classes) | Node Classification (GNN) |
| [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) | Image class (10 classes) | Image Classification |

## Structure

**Part 1 — EDA & Relation Networks** (tabular data)
- Scatter plots (World Happiness) and box plots (Lung Cancer)
- Relation networks: feature→outcome and feature↔feature correlations in one graph

**Part 2 — Graph Neural Networks** (Cora citation network)
- GCN and GAT trained on node classification
- t-SNE visualization of embeddings across layers
- GAT attention weight visualization
- Confusion matrix and Integrated Gradients analysis

**Part 3 — Deep Learning Pipeline** (CIFAR-10)
- Under the hood: Conv2d, ReLU, MaxPool explained with small numerical examples
- Three architectures built from scratch: plain CNN, residual CNN, Vision Transformer (ViT)
- "What if" experiments: training budget, dropout, model width

## Tutorial

The companion tutorial notebook (`UM-CISC7107-assignment2-tutorial.ipynb`) covers:
1. Colab basics
2. PyTorch fundamentals
3. EDA background
4. Mini CNN walkthrough
5. GNN background — toy graph examples of message passing, GCN vs GAT, and layer stacking

## Quick Start

1. Upload the notebook to [Google Colab](https://colab.research.google.com/)
2. Run all cells — datasets download automatically

## Assignment

See the end of the notebook for the required task and optional bonus challenge. Submit your work to **UM Moodle**.
