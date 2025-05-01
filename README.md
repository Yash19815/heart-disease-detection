Dataset This project uses the Heart Disease Dataset from Kaggle. The dataset contains information about patients, including medical attributes such as age, cholesterol level, chest pain type, etc., and a target variable indicating the presence of heart disease.

Rows: 303
Features: 13
Target: target (1 = heart disease, 0 = no heart disease)
# Objectives

Train a Decision Tree Classifier and visualize the tree.
Analyze overfitting and control tree depth.
Train a Random Forest and compare its accuracy.
Interpret feature importances using the Random Forest model.
Evaluate both models using cross-validation.
# Tools & Libraries

Python
Pandas, NumPy
Scikit-learn (DecisionTreeClassifier, RandomForestClassifier)
Matplotlib
Graphviz (optional for advanced tree visualization)
Steps Performed

Data Loading & Preparation
Read the dataset from heart.csv.
Separated features and target column.
Performed train/test split (80/20).
Decision Tree Classifier
Trained a DecisionTreeClassifier on the training data.
Evaluated performance on the test set.
Visualized the tree using plot_tree() from scikit-learn.
Overfitting Analysis
Trained multiple decision trees with varying max_depth from 1 to 15.
Plotted training and testing accuracy to understand overfitting behavior.
Random Forest Classifier
Trained a RandomForestClassifier with 100 trees.
Compared its accuracy and classification report with the decision tree.
Random Forest showed improved generalization.
Feature Importance
Extracted and plotted feature importances from the random forest.
Visualized which features contributed most to the model’s decisions.
Cross-Validation
Performed 5-fold cross-validation on both models.
Reported average accuracy for both the decision tree and random forest.
