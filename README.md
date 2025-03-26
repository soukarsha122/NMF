# Neural Matrix Factorization for Recommendation Systems

## Overview
This project implements **Neural Matrix Factorization (NMF)** for collaborative filtering-based recommendation systems. The approach combines **Generalized Matrix Factorization (GMF)** and **Multi-Layer Perceptron (MLP)** to learn user-item interactions efficiently. The implementation is based on the **MovieLens dataset** and uses **NDCG** and **HR@K** as evaluation metrics.

## Features
- Implements **Generalized Matrix Factorization (GMF)** and **MLP** models.
- Uses the **optimal embedding from GMF and MLP** to train the **NMF model**.
- Supports **NDCG (Normalized Discounted Cumulative Gain)** and **HR@K (Hit Ratio at K)** as performance evaluation metrics.
- Includes **hyperparameter tuning** for improved model performance.
- Utilizes **implicit feedback data** for collaborative filtering.

## Dataset
The project uses the **MovieLens dataset**, which contains user-item interaction data (movie ratings). The ratings are transformed into implicit feedback where interactions are marked as either **observed (1)** or **unobserved (0)**.

## Evaluation
The models are evaluated using **NDCG** and **HR@K**, which measure ranking quality and hit ratio at a given threshold.

## Hyperparameter Tuning
Hyperparameters such as **embedding size, number of layers, batch size, and learning rate** are tuned to optimize performance.

## Results
- The best-performing model was **Neural Matrix Factorization (NMF)**, which combines **GMF and MLP embeddings**.
- Hyperparameter tuning led to significant performance improvements.
- NMF outperformed traditional **Matrix Factorization** techniques.

## References
- [Neural Collaborative Filtering Paper](https://arxiv.org/abs/1708.05031)
- MovieLens Dataset: [https://grouplens.org/datasets/movielens/](https://grouplens.org/datasets/movielens/)

## Author
Developed by **Soukarsha Moulik**, based on the **Neural Collaborative Filtering** framework.

