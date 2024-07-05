#### Loan-Eligibility-Predictor

### Overview
This project implements a machine learning model to predict the eligibility of loan applications based on various features. Initially, a Logistic Regression model was used, achieving 79% accuracy with k-fold cross-validation. Subsequently, the model was refined using Decision Tree Algorithm, resulting in an accuracy improvement to 97.89%.


### Features
* Predicts loan eligibility based on applicant information.
* Utilizes supervised learning techniques to classify loan applications.


### Models
## Model 1: Logistic Regression
# Notebook: logistic_regression_model.ipynb
# Accuracy: 79%
# Details: 
           * Implemented using Logistic Regression with k-fold cross-validation.
           * Explored feature importance and initial hyperparameter tuning.
           * Despite efforts, accuracy plateaued, prompting exploration of more complex models.

## Model 2: Decision Tree Algorithm
# Notebook: decision_tree_algorithm_model.ipynb
# Accuracy: 97.89%
# Details: 
           * Implemented using Decision Tree Algorithm
           * Significant accuracy improvement observed over logistic regression.

### Contents
* # logistic_regression_model.ipynb : Jupyter Notebook for the logistic regression model.
* # decision_tree_algorithm_model.ipynb : Jupyter Notebook for the decision tree algorithm model.
* # loan_approval_dataset.csv : Sample dataset used for training and testing.
* # requirements.txt : List of Python libraries required to run the notebooks

### Conclusion
This project showcases the iterative process of model development and improvement for loan eligibility prediction. By starting with logistic regression and transitioning to a more advanced decision tree algorithm, significant accuracy gains were achieved. Future enhancements could involve integrating additional data sources, exploring advanced feature engineering techniques, or deploying models in production environments to validate real-world performance.
