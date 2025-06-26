# AI-ML-Internship-task-3
# Housing Price Prediction using Linear Regression

This project predicts housing prices using **Simple and Multiple Linear Regression** models implemented in Python. It is part of an internship task and demonstrates core machine learning steps like data preprocessing, model training, evaluation, and visualization.

## Dataset

- The dataset is from **Kaggle** and contains features like:
  - `price`, `area`, `bedrooms`, `bathrooms`, `stories`, `mainroad`, `guestroom`, `basement`, `hotwaterheating`, `airconditioning`, `parking`, `prefarea`, `furnishingstatus`
- The target variable is `price` (house price).

## Technologies Used

- Python 3
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

##  Project Structure

- `housing.csv` – The dataset used for training the model
- `housing_price_prediction.ipynb` – Google Colab notebook with full implementation
- `README.md` – Project overview and instructions

##  Steps Performed

1. **Data Import and Preprocessing**
   - Loaded CSV and removed missing values
   - One-hot encoding for categorical columns (if using multiple regression)

2. **Exploratory Data Analysis**
   - Checked distributions, correlations, and summary statistics

3. **Model Training**
   - Trained **Simple Linear Regression** (with `area` as feature)
   - Trained **Multiple Linear Regression** (with all numeric + encoded features)

4. **Model Evaluation**
   - MAE (Mean Absolute Error)
   - MSE (Mean Squared Error)
   - R² Score

5. **Visualization**
   - Scatter plot with regression line

