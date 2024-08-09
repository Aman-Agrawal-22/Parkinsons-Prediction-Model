# Parkinson's Telemonitoring using Machine Learning

This project utilizes various machine learning algorithms to analyze the Parkinson's Telemonitoring dataset, aiming to predict Parkinson's Disease progression and estimate UPDRS (Unified Parkinson's Disease Rating Scale) scores.

## Key Features

- Implemented machine learning models including **Linear Regression**, **Support Vector Regressor (Grid Search CV)**, **Decision Tree (Grid Search CV)**, **Gradient Boost**, **Ada Boost (Decision Tree)**, and **TensorFlow Keras Dense (5 layers)**.
- Optimized feature space using Principal Component Analysis (PCA) to reduce multicollinearity and dimensionality.

## Performance Metrics

The following table summarizes the performance of various algorithms used in this project for both training and testing phases:

### Comparison Table for Used Algorithms

| No. | Algorithm | MSE (Mean Squared Error) | R² Score | MAE (Mean Absolute Error) |
| --- | --------- | ------------------------ | -------- | ------------------------- |
| 1   | **Linear Regression** | Training: 55.73 | Training: 0.16 | Training: 6.31 |
|     |                           | Testing: 56.01 | Testing: 0.12 | Testing: 6.31 |
| 2   | **Support Vector Regressor (Grid Search CV)** | Training: 0.80 | Training: 0.99 | Training: 0.22 |
|     |                           | Testing: 13.29 | Testing: 0.79 | Testing: 0.22 |
| 3   | **Decision Tree (Grid Search CV)** | Training: 0.99 | Training: 0.99 | Training: 0.40 |
|     |                           | Testing: 5.31 | Testing: 0.92 | Testing: 0.40 |
| 4   | **Gradient Boost** | Training: 0.37 | Training: 0.99 | Training: 0.42 |
|     |                           | Testing: 1.85 | Testing: 0.97 | Testing: 0.42 |
| 5   | **Ada Boost (Decision Tree)** | Training: 0.16 | Training: 1.00 | Training: 0.24 |
|     |                           | Testing: 0.75 | Testing: 0.99 | Testing: 0.24 |
| 6   | **TensorFlow Keras Dense (5 layers)** | Training: 0.49 | Training: 0.99 | Training: 0.39 |
|     |                           | Testing: 1.36 | Testing: 0.98 | Testing: 0.39 |

## Conclusion

The project demonstrates the efficacy of machine learning models, particularly ensemble methods and deep neural networks, in improving the accuracy of Parkinson's Disease detection and progression prediction. The results indicate that these models can serve as powerful tools in clinical settings for the telemonitoring of Parkinson's Disease.

## References

Detailed performance metrics and methodology can be found in the related research papers.
