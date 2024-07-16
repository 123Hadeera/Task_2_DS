# Task_2_DS
Heart Disease Prediction:  Predicting heart disease using machine learning techniques. Implemented feature selection methods (filter, wrapper, embedded) to enhance model accuracy. Dataset sourced from Kaggle's Heart Disease UCI repository.
Task Description: Feature Selection Techniques Exploration and Evaluation

Objective:
Explore various feature selection techniques—filter, wrapper, and embedded methods—using a dataset sourced from Kaggle that contains a minimum of 15 features. The goal is to understand the impact of feature selection on model performance in a classification context.

Steps Involved:

Data Exploration and Preprocessing:

Choose a suitable dataset from Kaggle with at least 15 features.
Perform data preprocessing steps including handling missing values, encoding categorical variables if necessary, and scaling numerical features.
Baseline Model Construction:

Build a baseline classification model using K-Nearest Neighbors (KNN) without applying any feature selection techniques.
Evaluate the model performance using metrics such as accuracy, precision, recall, and F1-score.

Feature Selection Techniques:

Filter Method: Select relevant features based on statistical measures such as correlation coefficients, chi-square test, or ANOVA F-values.
Wrapper Method: Use iterative techniques like recursive feature elimination (RFE) with cross-validation to select the optimal subset of features.
Embedded Method: Employ techniques like Lasso regularization (L1 regularization) or decision tree-based feature importance to select features during model training.

Model Rebuilding and Evaluation:

Rebuild the KNN classification model using the features selected from each method.
Evaluate the performance of each feature-selected model using the same metrics as the baseline model.

Comparison and Analysis:

Compare the performance metrics (accuracy, precision, recall, F1-score) of the baseline model versus the models with feature selection.
Discuss the impact of each feature selection technique on model performance, highlighting improvements or trade-offs observed.
Documentation and Submission:

Document the entire process, including code implementation, results summary, and analysis findings, in a well-structured GitHub repository.
Create a short demo video demonstrating your process, key findings, and conclusions drawn from the experiment.

Deliverables:

Code implementation showcasing baseline model construction, feature selection techniques, and model evaluation.
Results summary comparing model performance with and without feature selection.
Detailed analysis discussing the effectiveness of each feature selection technique.
Well-documented GitHub repository with clear README.md including project overview, setup instructions, usage guidelines, and conclusions.
Demo video presenting the project workflow, findings, and conclusions in a concise manner.
