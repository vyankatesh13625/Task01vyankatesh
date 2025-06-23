# Task01vyankatesh
# Titanic Dataset - Data Cleaning and Preprocessing

#Task Overview

This task is part of an AI/ML Internship where the objective was to clean and preprocess the Titanic dataset to prepare it for machine learning models.

#Steps Performed

1. Loaded the Titanic dataset using **Pandas**.
2. Explored the dataset using `.info()`, `.describe()`, and visualizations.
3. Handled missing values:
   - Filled missing Age values with the median.
   - Filled missing Embarked values with the mode.
4. Converted categorical features (`Sex`, `Embarked`) into numerical form using one-hot encoding.
5. Scaled numerical features (`Age`, `Fare`) using **StandardScaler** from **scikit-learn**.
6. Detected and removed outliers in `Fare` using the **IQR method** and boxplots.
7. Saved the cleaned dataset as `cleaned_titanic.csv`.

#Files Included

- `titanic_task.ipynb`: Main Jupyter Notebook (Google Colab) with all preprocessing steps.
- `cleaned_titanic.csv`: Final cleaned dataset after preprocessing.
- `README.md`: This file.

#Tools and Libraries Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- scikit-learn

#Dataset Source

- Titanic Dataset from Kaggle: [Link](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

#Submission

Uploaded to GitHub as part of the internship submission.
