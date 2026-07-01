#  Car Price Prediction Using Machine Learning

##  Project Overview

This project predicts the selling price of used cars using Machine Learning. A **Linear Regression** model is trained on historical car data to estimate the selling price based on features such as manufacturing year, present price, kilometers driven, fuel type, transmission, selling type, and ownership.

This project was completed as part of my **CodeAlpha Data Science Internship**.

---

##  Dataset

The dataset contains information about used cars, including:

- Car Name
- Year
- Selling Price (Target)
- Present Price
- Driven Kilometers
- Fuel Type
- Selling Type
- Transmission
- Number of Previous Owners

---

##  Technologies Used

- Python
- Google Colab
- Pandas
- Matplotlib
- Scikit-learn

---

##  Libraries Used

```python
import pandas as pd
import matplotlib.pyplot as plt

from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.metrics import mean_absolute_error, r2_score
```

---

##  Project Workflow

### 1. Import Required Libraries

Imported the necessary Python libraries for data analysis, visualization, model training, and evaluation.

### 2. Load the Dataset

Loaded the dataset using Pandas.

### 3. Explore the Data

- Displayed the first few rows
- Checked column names
- Viewed dataset information
- Verified missing values

### 4. Data Preprocessing

Converted categorical values into numerical values.

- Fuel Type
- Selling Type
- Transmission

### 5. Feature Selection

Selected input features (X) and target variable (Selling Price).

### 6. Train-Test Split

Split the dataset into:

- 80% Training Data
- 20% Testing Data

### 7. Train the Model

Used the **Linear Regression** algorithm to train the model.

### 8. Make Predictions

Predicted the selling prices for the test dataset.

### 9. Model Evaluation

Evaluated the model using:

- Mean Absolute Error (MAE)
- R² Score

### 10. Visualization

Plotted **Actual Price vs Predicted Price** using a scatter plot.

---

##  Model Performance

Evaluation Metrics:

- **Mean Absolute Error (MAE):** 1.22
- **R² Score:** 0.85 (approximately)

The model provides good prediction accuracy for the given dataset.

---

##  Output

The project displays:

- Predicted car prices
- Actual vs Predicted comparison table
- Scatter plot of Actual Price vs Predicted Price
