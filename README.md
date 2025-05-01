# ElevateLabs-task5
# Objective:
The aim of this project is to understand and implement tree-based machine learning models — Decision Trees and Random Forests — for classification using the Heart Disease Dataset.

# Tools & Libraries Used:
1. Python
2. Pandas
3. NumPy
4. Scikit-learn
5. Matplotlib
6. Seaborn

# Dataset:
The dataset used is the Heart Disease Dataset which contains various medical attributes such as age, sex, cholesterol, blood pressure, etc., used to predict whether a person has heart disease.

# Project Steps:
1. Data Preprocessing
  -Loaded the heart disease dataset.
  -Split the data into features (X) and target (y).
  -Performed a train-test split (70-30 ratio).
2. Decision Tree Classifier
  -Trained a Decision Tree Classifier using scikit-learn.
  -Predicted on test data.
  -Evaluated performance using Accuracy, Precision, Recall, and F1-Score.
  -Visualized the trained tree using plot_tree().
3. Overfitting Analysis
  -Trained Decision Trees with different max depths (1 to 15).
  -Plotted Train vs Test accuracy to analyze overfitting and determine optimal tree depth.
4. Random Forest Classifier
  -Trained a Random Forest Classifier.
  -Evaluated it similarly using classification metrics.
  -Compared accuracy with the Decision Tree model.
5. Feature Importance
  -Extracted and visualized the feature importances from the Random Forest model using a bar chart.
  -Identified the most influential features for heart disease prediction.
6. Cross-Validation
  -Applied 5-fold cross-validation to both Decision Tree and Random Forest models.
  -Compared mean cross-validation scores to assess model generalization.

# Results:

Decision Tree (Accuracy): 97.07
Random Forest (Accuracy): 98.05

# Key Takeaways:
  -Decision Trees are easy to interpret but prone to overfitting.
  -Random Forests improve performance by using ensemble learning and feature averaging.
  -Controlling tree depth helps reduce overfitting in decision trees.
  -Cross-validation provides a better estimate of model performance on unseen data.

