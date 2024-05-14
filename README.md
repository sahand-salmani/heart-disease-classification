# Heart Disease Classification

This repository contains a classification model for predicting heart disease based on various medical attributes. The dataset includes the following columns:

- Age: Age of the patient
- Sex: Gender of the patient (0 = female, 1 = male)
- ChestPainType: Type of chest pain experienced by the patient (1 = typical angina, 2 = atypical angina, 3 = non-anginal pain, 4 = asymptomatic)
- RestingBP: Resting blood pressure (in mm Hg)
- Cholesterol: Serum cholesterol level (in mg/dL)
- FastingBS: Fasting blood sugar > 120 mg/dL (1 = true, 0 = false)
- RestingECG: Resting electrocardiographic results (0 = normal, 1 = having ST-T wave abnormality, 2 = showing probable or definite left ventricular hypertrophy)
- MaxHR: Maximum heart rate achieved
- ExerciseAngina: Exercise-induced angina (1 = yes, 0 = no)
- Oldpeak: ST depression induced by exercise relative to rest
- ST_Slope: Slope of the peak exercise ST segment (1 = upsloping, 2 = flat, 3 = downsloping)
- HeartDisease: Presence of heart disease (0 = no, 1 = yes)

## Data Preprocessing

Before building the classification models, the dataset underwent cleaning and exploratory data analysis (EDA) including:

- Data cleaning to handle missing values and outliers.
- EDA techniques such as a heatmap to visualize the correlation matrix, histograms to analyze the distribution of heart disease by gender, and pair plots to explore relationships between the heart disease column and other attributes.

## Classification Models

The following classification models were implemented:

1. Logistic Regression
2. Support Vector Machine (SVM)
3. K-Nearest Neighbors (KNN)
4. Random Forest
5. Naive Bayes

## Evaluation Metrics

For each classification model, the following metrics were computed:

- Accuracy score: The proportion of correctly classified instances.
- Classification report: Provides precision, recall, F1-score, and support for each class.

## Contributions

Contributions are welcome! If you have suggestions for improvement or new features, feel free to open an issue or submit a pull request.
