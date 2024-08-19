# CreditGuard

**CreditGuard** is a machine learning project aimed at credit risk analysis using various classification models. This repository contains a Jupyter Notebook (`main.ipynb`) that demonstrates the implementation, evaluation, and comparison of different machine learning models, including XGBoost, Decision Tree, Random Forest, and Logistic Regression.

## Project Overview

### XGBoost Model
- **Implementation**: The notebook includes an XGBoost model for classification, with a focus on hyperparameter tuning.
- **Hyperparameters Tested**: The model iteratively tests combinations of hyperparameters such as `colsample_bytree` and `learning_rate`.
- **Outputs**: Training and testing accuracy are recorded for each hyperparameter combination to fine-tune the model for better performance.

### Performance Comparison
- **Models Compared**: XGBoost is compared with Decision Tree and Random Forest models.
- **Findings**: XGBoost generally outperforms the other models, with suggestions for further improvements through feature engineering and scaling.

### Logistic Regression
- **Implementation**: A Logistic Regression model is also included for comparison.
- **Note**: The model's accuracy is reported, along with a convergence warning indicating that the maximum number of iterations was reached.

### Model Evaluation
- **Metrics**: The notebook evaluates models using various metrics such as accuracy, recall, precision, and F1-score.
- **Significance**: Each metric is computed and discussed to understand the performance and reliability of the models.

### Further Analysis
- **Future Work**: Recommendations for further enhancement include additional feature engineering and scaling to optimize the performance of the XGBoost model.

## Getting Started

To get started with this project, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/CreditGuard.git
   cd CreditGuard


<h1>Dependencies</h1><br/>
Python 3.x<br/>
Jupyter Notebook<br/>
XGBoost<br/>
scikit-learn<br/>
pandas<br/>
numpy<br/><br/>
Ensure you have the above dependencies installed. You can find the full list of required packages in requirements.txt.
<br/>
<h3>License</h3>
This project is licensed under the MIT License. See the LICENSE file for details.
<br/>
<h3>Acknowledgments</h3>
XGBoost: For its efficient and scalable implementation of gradient boosting.<br/>
scikit-learn: For providing a range of machine learning algorithms and evaluation metrics.
