# Model Transition Notes

This document outlines the steps and rationale behind transitioning from a logistic regression model to decision tree for the loan eligibility predictor project.

## Initial Approach: Logistic Regression

1. **Model Selection**: Chose logistic regression for its simplicity and initial suitability for binary classification of loan eligibility.
2. **Feature Engineering**: Conducted initial feature selection and engineering, including preprocessing of data.
3. **Model Evaluation**: Used k-fold cross-validation to assess model performance, achieving an accuracy of approximately 79%.
4. **Analysis**: Identified that coefficients in the heatmap indicated a weak linear relationship between dependent and independent variables.

## Transition to Decision Tree

1. **Rationale**: Opted for decision tree to explore non-linear relationships and improve classification accuracy.
2. **Implementation**: Implemented decision tree algorithm (specifically, [mention specific algorithm or parameters used]).
3. **Advantages**: Decision tree algorithms are well-suited for capturing non-linear relationships and are effective for classification tasks.
4. **Performance**: Achieved significant accuracy improvement, with the decision tree model reaching an accuracy of 97.89%.
5. **Comparison**: Compared performance metrics and decision boundaries between logistic regression and decision tree models.
6. **Final Model Selection**: Selected decision tree as the preferred model due to superior performance and its ability to handle non-linear relationships.

## Conclusion

This document provides a comprehensive overview of the model selection process, detailing the transition from logistic regression to a decision tree based on iterative experimentation and performance evaluation. The poor linear relationship indicated by heatmap coefficients underscored the suitability of decision tree algorithms for this classification task. Future enhancements may involve ensemble methods or additional feature engineering to further enhance predictive accuracy.

