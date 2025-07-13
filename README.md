## **Housing Price Prediction**

This repository contains a machine learning project focused on predicting housing prices using linear regression. The project follows a structured pipeline that includes data loading, preprocessing, exploratory data analysis, model training, and evaluation.



## **Project Objective**

The objective of this project is to develop a regression model capable of accurately predicting housing prices based on various features present in the dataset.



Technologies Used
	•	Python
	•	Pandas
	•	NumPy
	•	Matplotlib
	•	Seaborn
	•	Scikit-learn



## **Project Structure**

```
Housing-Price-Prediction/
│
├── housing.csv              # Dataset used for model training
├── Set_5_juhaina.ipynb      # Jupyter Notebook containing the full workflow
├── README.md                # Project documentation
```



Workflow Summary

1. Data Loading and Inspection
	•	Load the dataset using pandas
	•	Examine dataset shape, column names, data types, and sample rows

2. Exploratory Data Analysis (EDA)
	•	Visualize feature distributions and relationships
	•	Identify correlations with the target variable

3. Data Preprocessing
	•	Handle missing values
	•	Encode categorical variables (if present)
	•	Split the dataset into training and testing sets

4. Model Development
	•	Train a Linear Regression model using scikit-learn

5. Model Evaluation
	•	Evaluate model performance using metrics such as R² Score and Mean Squared Error
	•	Visualize the comparison between predicted and actual values



## How to Run the Project

### 1. Clone the Repository
```bash
git clone https://github.com/Juhainayasmin09/Housing-Price-Prediction.git
cd Housing-Price-Prediction
```

### 2. Install Required Packages
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 3. Run the Jupyter Notebook
```bash
jupyter notebook Set_5_juhaina.ipynb 
```


### Results

•	The model was successfully trained on the dataset using Linear Regression.

•	Evaluation metrics such as R² Score and MSE were used to assess model accuracy.

•	Visual analysis confirmed the model’s general performance and limitations.



### Potential Improvements
•	Experiment with more advanced regression models (e.g., Ridge, Lasso, XGBoost)
•	Incorporate feature scaling and outlier detection
•	Apply k-fold cross-validation for robust evaluation
•	Perform hyperparameter tuning to optimize model performance



## Author

*Juhaina Yasmin*
