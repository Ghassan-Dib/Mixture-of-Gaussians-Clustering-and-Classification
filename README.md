# Mixture of Gaussians: Clustering and Classification

This repository focuses on implementing and analyzing the Mixture of Gaussians (MoG) model for clustering and classification problems, including the use of the Expectation-Maximization (EM) algorithm and phoneme classification.

## Key Features

### 1. **Clustering with MoG**
- Implemented MoG to cluster phoneme data.
- Analyzed cluster evolution with different initializations and parameters.
- Visualized clusters using features such as F1 and F2.

### 2. **Phoneme Classification**
- Built a classifier using the Maximum Likelihood (ML) criterion.
- Achieved classification accuracies:
  - **95.07%** for 3 clusters.
  - **96.05%** for 6 clusters, demonstrating improved data modeling.
- Explored decision boundaries for different cluster configurations.

### 3. **Error Handling**
- Addressed singular covariance matrix errors during EM steps.
- Applied regularization techniques by adding noise to the covariance matrix diagonal.
- Improved stability and ensured invertibility of covariance matrices.

## Results
- **Clustering Analysis**: Explored the impact of different cluster numbers (`k`) on data modeling and classification accuracy.
- **Classification Matrix**: Visualized decision boundaries and their complexities for various `k` values.
- **Regularization**: Prevented singular matrix errors using techniques like diagonal noise addition.

## Requirements
- Python 3.x
- NumPy
- Matplotlib
- SciPy
