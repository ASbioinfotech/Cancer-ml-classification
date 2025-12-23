Cancer Tumor Classification Using Machine Learning

This project focuses on predicting whether a tumor is malignant (0) or benign (1) using machine learning. The dataset contains 50 patients and 12 features related to tumor characteristics, such as radius, texture, perimeter, area, smoothness, concavity, symmetry, and fractal dimension. The main goal is to demonstrate a complete machine learning workflow and gain insights into which tumor features are most important for predicting malignancy.

Workflow:

1. Exploratory Data Analysis (EDA)

   i)Checked the dataset for missing values and calculated summary statistics.
   ii) Visualized the distribution of malignant and benign tumors.
   iii) Plotted correlation heatmaps and class-wise feature distributions to understand patterns and relationships.

2. Data Preprocessing

   i) Separated features (X) and target labels (y).
   ii) Standardized feature values using StandardScaler.
   iii) Split the dataset into training (80%) and testing (20%) sets.

3. Model Training

   i)Trained three machine learning models: Logistic Regression, Random Forest, and Support Vector Machine (SVM).
   ii) Compared their performance on the test set to select the best model.

4. Predictions and Evaluation

   i) Evaluated each model using accuracy, precision, recall, F1-score, and ROC-AUC.
   ii) Plotted confusion matrices and ROC curves for better visualization.
   iii) Random Forest was identified as the best-performing model with balanced metrics.

5. Feature Importance

   i)Used Random Forest to analyze feature importance.
   ii) Found that Radius_mean, Concavity_mean, and Perimeter_mean were the most influential features in predicting tumor malignancy.

6. Hyperparameter Tuning

    Applied GridSearchCV to optimize Random Forest parameters, improving model performance further.

Results and Insights:

i) Random Forest achieved the highest accuracy and overall performance.
ii) Larger radius and higher concavity are indicative of malignant tumors.
iii) The project demonstrates how feature analysis and visualization can support biomedical decision-making and provides practical experience with end-to-end machine learning workflows.

How to Use:

i) Open the notebook cancer_classification.ipynb in Google Colab.
ii) Upload the dataset synthetic_cancer_dataset_50.xlsx.
iii) Run all cells to reproduce the EDA, model training, evaluation metrics, and feature importance analysis.


