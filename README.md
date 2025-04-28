# Task_5
## Titanic Survival Prediction
A machine learning project aimed at predicting the survival of passengers aboard the Titanic using the famous Titanic dataset.

## 🛠 Project Overview
This project involves building a predictive model that determines whether a passenger survived the Titanic shipwreck based on features like:

Passenger Class (Pclass)

Gender (Sex)

Age

Fare

Embarked Port

Number of Siblings/Spouses aboard (SibSp)

Number of Parents/Children aboard (Parch)

We perform data cleaning, exploratory data analysis (EDA), feature engineering, and apply machine learning models to make predictions.

## 📂 Project Structure
bash Copy Edit ├── titanic_data.ipynb # Jupyter notebook containing full code ├── README.md # Project documentation ├── insights.txt

## 📊 Technologies Used
Python

Jupyter Notebook

Libraries:

pandas

numpy

matplotlib

seaborn

scikit-learn (for modeling)

## ⚙️ Workflow
Data Loading: Load Titanic dataset using pandas.

Data Preprocessing:
Handle missing values.

Encode categorical variables.

Feature engineering (creating new useful features).

Exploratory Data Analysis (EDA):

Visualize patterns and relationships among features.

Model Building:
Train machine learning models (e.g., Logistic Regression, Decision Tree, Random Forest).

Evaluate performance using accuracy score, confusion matrix, etc.

Prediction and Conclusion:

Predict survival on new/unseen data.

## 🚀 How to Run
Clone this repository:

git clone https://github.com/your-username/titanic-survival-prediction.git
cd titanic-survival-prediction

Install required libraries:

pip install -r requirements.txt

Open the Jupyter Notebook:

jupyter notebook titanic_data.ipynb
