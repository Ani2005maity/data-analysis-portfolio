Iris Dataset Analysis & Preprocessing

Project Overview
This project performs Exploratory Data Analysis (EDA) and data preprocessing on the classic Iris dataset. The goal was to clean the data, handle missing values, and visualize relationships between features to understand species distribution.

Technologies Used
Python
Pandas: For data manipulation and handling missing values (imputation).
Seaborn/Matplotlib: For generating heatmaps, histograms, and scatter plots.
Scikit-Learn: For Label Encoding and data scaling.

Key Techniques
1. Data Cleaning: Handled missing values using `SimpleImputer` (mean strategy for numerical, most_frequent for categorical).
2. Transformation: Applied `LabelEncoder` to target variables and `StandardScaler` for feature normalization.
3. Visualization: Created correlation heatmaps and pairwise scatter plots to identify clusters.

Results
Observed strong correlation between petal length and petal width.
Successfully prepared the dataset for future machine learning classification models.
