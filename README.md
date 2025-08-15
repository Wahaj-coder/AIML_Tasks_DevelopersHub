# 📊 Machine Learning Tasks – DevelopersHub
This repository contains multiple data analysis and machine learning projects demonstrating end-to-end workflows — from loading datasets, exploring data, preprocessing, model building, to evaluation and visualization.

## 📁 Projects Included

### Task 1 : Iris Dataset Classification
Goal: Classify iris flowers into three species (Setosa, Versicolor, Virginica) based on flower measurements.
Dataset:
Source: UCI Machine Learning Repository, Iris
Records: 150 samples
Features: Sepal length, Sepal width, Petal length, Petal width
Target: Flower species (3 classes)
Workflow:
Data loading & exploration – Viewed dataset structure, statistics, and first few rows.
Visualization : Plots showing feature distribution, pairwise relationships, and species separation.
Model training : Applied classification algorithms (e.g., Logistic Regression, KNN, Decision Tree).
Evaluation – Checked accuracy and compared results across models.
Key Insights from Plots:
Petal length and petal width are strong separators for Setosa vs other species.
Some overlap exists between Versicolor and Virginica.
Result:
Achieved high accuracy (above 95%) in classifying the flowers.

### Task 2 : Customer Segmentation
Goal: Segment mall customers into distinct groups based on their purchasing behavior.
Dataset:
Source: Mall Customer Dataset
Records: 200 customers
Features: Customer ID, Gender, Age, Annual Income, Spending Score
Target: Not predefined (unsupervised learning)
Workflow:
Data inspection : Checked dataset shape, feature types, and missing values.
Exploratory Data Analysis (EDA) – Plotted distributions of age, income, and spending score; visualized relationships between variables.
Clustering : Applied K-Means and DBSCAN algorithms to group customers.
Model tuning : Used the Elbow method and Silhouette score to determine the optimal number of clusters.
Visualization : 2D scatter plots showing customer clusters and their distribution in income–spending score space.
Key Insights from Plots:
Clear segmentation observed between high-spending and low-spending customers.
DBSCAN helped identify noise/outlier points not belonging to main groups.
Result:
Identified meaningful customer groups to assist in targeted marketing strategies.

### Task 3 – Heart Disease Prediction
Goal: Predict whether a patient has heart disease based on clinical and demographic data.
Dataset:
Records: 920 patients
Features: Age, Sex, Chest pain type, Blood pressure, Cholesterol, Max heart rate, etc.
Target: 0 for No heart disease, 1 for Heart disease present
Workflow:
Data inspection – Checked shape, missing values, and data types.
Preprocessing – Filled missing values, encoded categorical variables, scaled numerical features.
Exploratory Data Analysis (EDA) – Visualized target distribution, feature relationships, and correlations.
Model training – Used Logistic Regression for binary classification.
Evaluation – Measured accuracy, precision, recall, F1-score, and plotted confusion matrix.
Key Insights from Plots:
Target distribution is fairly balanced.
Certain features (e.g., chest pain type, max heart rate) show clear patterns between classes.
Confusion matrix confirms balanced model performance.
Results:
Accuracy: 88.5%
Precision & Recall: 0.88–0.89 for both classes.
The model generalizes well for both positive and negative predictions.

🛠 Technologies Used
Python (Core programming)
Pandas, NumPy (Data manipulation)
Scikit-learn (Machine learning models & evaluation)
Matplotlib, Seaborn (Data visualization)
