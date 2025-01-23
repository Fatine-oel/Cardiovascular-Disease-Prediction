# Cardiovascular-Disease-Prediction
Cardiovascular Disease Prediction: A machine learning project that predicts heart disease risk using various classification algorithms and data preprocessing techniques. Includes data analysis, visualization, and model evaluation
This project aims to predict the presence of cardiovascular diseases based on various health features. It uses a dataset containing information about individuals' health and lifestyle, and the goal is to predict whether an individual has cardiovascular disease or not. The machine learning model is trained on this data to classify individuals into two categories: those with cardiovascular disease (`cardio = 1`) and those without it (`cardio = 0`).

## Dataset

The dataset used in this project contains multiple health-related attributes that are linked to the presence of cardiovascular disease. Below is a brief description of the dataset:

| Column        | Description |
|---------------|-------------|
| **id**        | Unique identifier for each individual. |
| **age**       | Age of the individual. |
| **gender**    | Gender of the individual (1 = Male, 2 = Female). |
| **height**    | Height of the individual (in cm). |
| **weight**    | Weight of the individual (in kg). |
| **ap_hi**     | Systolic blood pressure (mmHg). |
| **ap_lo**     | Diastolic blood pressure (mmHg). |
| **cholesterol** | Cholesterol level (1 = Normal, 2 = Elevated, 3 = Very High). |
| **gluc**      | Glucose level (1 = Normal, 2 = Elevated, 3 = Very High). |
| **smoke**     | Smoking status (1 = Yes, 0 = No). |
| **alco**      | Alcohol consumption (1 = Yes, 0 = No). |
| **active**    | Physical activity level (1 = Active, 0 = Inactive). |
| **cardio**    | Presence of cardiovascular disease (1 = Yes, 0 = No). (Target variable) |

## Installation

To run this project locally, you need to clone the repository and install the necessary dependencies.

# 1. Clone the repository:
   git clone https://github.com/Fatine-oel/Cardiovascular-Disease-Prediction.git

# 2. Navigate into the project directory:
  cd Cardiovascular-Disease-Prediction
# Install the required Python packages:
  pip install -r requirements.txt

## Model
The model used in this project is a Classification Model, which aims to predict the likelihood of cardiovascular disease. The model was trained using various algorithms such as logistic regression, K-Means clustering , Random Forest , KNN , and support vector machines (SVM).

## Key Steps:
# Data Preprocessing:
  Cleaning the data by handling missing values, encoding categorical variables, and scaling numerical values.

# Model Training:
  Training the model on the training set and validating it using the testing set.

# Model Evaluation:
  Evaluating the model's performance using metrics like accuracy, precision, recall, and F1-score.

# Prediction:
  Making predictions on data.

License
This project is licensed under the MIT License - see the LICENSE file for details.
