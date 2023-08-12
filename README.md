# Diabetes Prediction Analysis

This Jupyter Notebook contains an analysis of diabetes prediction using the `diabetes.csv` dataset. The dataset contains various health metrics, and the goal is to predict whether an individual has diabetes or not.

## Contents

1. **Introduction**: The notebook starts by loading the required libraries and the dataset (`diabetes.csv`).
2. **Data Overview**: A quick overview of the loaded dataset, including the column names and general information.
3. **Data Cleaning**: Investigating missing values and removing instances with inconsistent values, especially zeros in crucial health metrics.
4. **Exploratory Data Analysis (EDA)**: Analyzing the distribution of variables based on the presence or absence of diabetes.
5. **Data Preprocessing**: Standardizing the variables using the StandardScaler and splitting the dataset into training and test sets.
6. **Perceptron Model**: Training a Perceptron model on the dataset and evaluating its accuracy.
7. **Adaline Model**: Implementation of the Adaline (ADAptive LInear NEuron) model with different learning rates and epoch values.
8. **Conclusion**: A summary of the results obtained from the Perceptron and Adaline models.

## How to Use

1. Install Jupyter Notebook or Jupyter Lab on your system.
2. Clone this repository.
3. Place the `diabetes.csv` file in the same directory as this notebook.
4. Open the notebook using Jupyter Notebook or Jupyter Lab.
5. Run each cell sequentially to reproduce the analysis steps.

## Dataset

The dataset `diabetes.csv` contains various health metrics and whether an individual has diabetes (1) or not (0). The columns in the dataset include:

- Embarazos: Number of pregnancies
- Glucosa: Plasma glucose concentration after 2 hours in an oral glucose tolerance test
- Presión arterial: Diastolic blood pressure (mm Hg)
- Grosor de la piel: Triceps skinfold thickness (mm)
- Insulina: 2-hour serum insulin (mu U/ml)
- BMI: Body Mass Index ((weight in kg)/(height in m^2))
- Función de pedigrí de diabetes: Diabetes pedigree function
- Edad: Age
- Resultado: 1 if diabetes is present, 0 otherwise

## Results

The analysis explores the relationships between health metrics and diabetes presence. It involves data preprocessing, exploratory data analysis, training Perceptron and Adaline models, and evaluating their performance. The best result achieved was an accuracy of 0.722 using the Adaline model with specific hyperparameters.

For detailed insights and code, please refer to the notebook.
