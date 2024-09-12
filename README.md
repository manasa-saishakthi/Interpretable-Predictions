# Crime Prediction and Interpretability Using XGBoost and Random Forest

## Project Overview

Crime encompasses activities that violate laws and regulations and can range from minor infractions to serious offenses. Understanding crime patterns and trends is vital for developing effective law enforcement strategies. This project explores crime category predictions using XGBoost and Random Forest models on a dataset of San Francisco crime data spanning 12 years. Compared to other models like k-Nearest Neighbors (KNN), Stochastic Gradient Descent (SGD), and Naïve Bayes, XGBoost and Random Forest demonstrate superior predictive performance, as evidenced by competitive log-loss scores. Additionally, this project employs Local Interpretable Model-agnostic Explanations (LIME) and SHapley Additive exPlanations (SHAP) to enhance the interpretability of these models, providing deeper insights into the factors influencing crime predictions.

## Methodology

### Data

- **Dataset**: San Francisco crime data covering 12 years.
- **Target Feature**: Crime categories.

### Models

- **XGBoost**: An optimized gradient boosting algorithm known for its predictive accuracy.
- **Random Forest**: An ensemble method utilizing multiple decision trees for improved classification performance.

### Comparison Models

- **k-Nearest Neighbors (KNN)**
- **Stochastic Gradient Descent (SGD)**
- **Naïve Bayes**

### Interpretability Techniques

- **LIME**: Local Interpretable Model-agnostic Explanations provide explanations for individual predictions by approximating the model locally with an interpretable model.
- **SHAP**: SHapley Additive exPlanations offer a unified measure of feature importance based on game theory, providing insights into the contributions of each feature to the model's predictions.

### Evaluation Metrics

- **Log-Loss**: A metric for classification models, where lower values indicate better performance. The project achieved log-loss scores of 2.277761 (XGBoost) and 2.283956 (Random Forest).

## Installation

To set up the project environment, follow these steps:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/crime-prediction.git
   cd crime-prediction
