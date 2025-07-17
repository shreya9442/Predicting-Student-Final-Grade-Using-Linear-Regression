# Predicting-Student-Final-Grade-Using-Linear-Regression

### Objective:
To predict students' final grade (G3) using Linear Regression based on various academic and personal attributes.

### Steps Followed:
Loaded and cleaned the dataset (student-mat.csv)

Handled categorical variables using appropriate encoding: 

Binary columns (e.g., sex, internet) -- Label Encoding

Nominal multi-category columns (e.g., Mjob, Fjob, reason) -- One-Hot Encoding

### Trained a Linear Regression model

### Evaluated the model using regression metrics

### Model Performance (Linear Regression):
Metric	Value
MAE	1.33
RMSE	2.11
R² Score	0.78

### Interpretation:
The model explains 78% of the variance in student's final grades.
On average, predictions are off by about 1.33 marks, which is fairly accurate.

### Visualization:
The scatter plot between actual and predicted G3 shows most predictions fall near the ideal line.

The model slightly underperforms for very low or very high scores, but overall follows a linear trend.

### Insights:
This model can help schools identify students who may need early support based on patterns in the data.
