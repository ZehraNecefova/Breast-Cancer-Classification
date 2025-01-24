# Breast-Cancer-Classification
Purpose of project is to classify breast cancer cases as benign or malignant based on biopsy features, using machine learning techniques for accurate diagnosis.

Steps Overview:
Data Preparation:
Cleaned the dataset by renaming columns, dropping irrelevant features, and filling missing values in the Bare Nuclei column.
Standardized the data for consistency.

Exploratory Data Analysis (EDA):
Visualized data distributions and identified outliers using boxplots.
Created a heatmap to explore feature correlations.

Model Development:
Implemented K-Nearest Neighbors (KNN) with initial k=3.
Tested multiple k values (from 4 to 10) to find the optimal one.

Evaluation Metrics:
Accuracy: Training and test set scores computed for different k values.
Confusion matrix and classification report to assess precision, recall, and F1-score.
