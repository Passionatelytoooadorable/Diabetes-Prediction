# Diabetes Prediction

## Overview
This project aims to develop a machine learning model to predict the likelihood of diabetes in patients. By analyzing a dataset of medical information, we train a model that can classify individuals as diabetic or non-diabetic based on specific health parameters.

## Dataset
We use the **PIMA Indians Diabetes Database**, which includes the following features:
- **Pregnancies**: Number of times pregnant
- **Glucose**: Plasma glucose concentration
- **BloodPressure**: Diastolic blood pressure (mm Hg)
- **SkinThickness**: Triceps skinfold thickness (mm)
- **Insulin**: 2-Hour serum insulin (mu U/ml)
- **BMI**: Body mass index (weight in kg/(height in m)^2)
- **DiabetesPedigreeFunction**: Diabetes pedigree function (a function that scores likelihood of diabetes based on family history)
- **Age**: Age (years)
- **Outcome**: Binary variable indicating diabetes (1) or not (0)

## Requirements
- Python 3.x
- Libraries:
  - `pandas` for data manipulation
  - `numpy` for numerical operations
  - `scikit-learn` for machine learning algorithms
  - `matplotlib` and `seaborn` for data visualization

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/username/diabetes-prediction.git

2. Navigate into the project directory:
   ```bash
   cd diabetes-prediction

3. Run the main script:
   ```bash
   python main.py

### Model Training

1. Data Preprocessing:
   - Handle missing values, if any.
   - Feature scaling to standardize input data.

2. Model Selection:
   - Experiment with algorithms such as Logistic Regression, Decision Trees, and Random Forest.

3. Evaluation:
   - Evaluate using metrics such as accuracy, precision, recall, and F1-score.


## Results
The best model achieved an accuracy of X% on the test data. Additional metrics:
 -   Precision: Y%
 -  Recall: Z%
 -   F1 Score: A%

## Contributing
Contributions are welcome! Feel free to submit issues or pull requests.

## License
This project is licensed under the MIT License.
