# House Price Prediction Model

## Overview
This project predicts house prices using machine learning techniques in Python. It utilizes regression models from scikit-learn and visualizes results using matplotlib.

## Features Used
The model considers the following features to predict house prices:
- `GrLivArea`: Above grade (ground) living area square feet.
- `BedroomAbvGr`: Number of bedrooms above ground.
- `FullBath`: Number of full bathrooms above ground.
- `HalfBath`: Number of half bathrooms above ground.

## Methodology
1. **Data Preprocessing**:
   - Missing values were handled using median imputation.
   - Polynomial features up to the second degree were created to capture non-linear relationships.

2. **Model Selection**:
   - Evaluated models include Linear Regression, Ridge Regression, and Lasso Regression.
   - Hyperparameters were optimized using grid search with cross-validation.

3. **Evaluation**:
   - Performance metrics include Root Mean Squared Error (RMSE) and R² score on a test set.

4. **Visualization**:
   - Scatter plot visualizes predicted vs. actual house prices, with a reference line for perfect predictions.

## Installation
To run the project locally:
1. Clone the repository:
<code>git clone [https://github.com/your_username/house-price-prediction.git](https://github.com/Varshamishra56/PRODIGY_TrackCode_TaskNumber.git)</code>
<code>cd house-price-prediction</code>

2. Install dependencies:
<code>pip install -r requirements.txt</code>

3. Run the code:
<code>python house_price_prediction.py</code>


## Dependencies
- Python 3.x
- scikit-learn
- matplotlib
- pandas
- numpy

## Contributing
Contributions are welcome! Please fork the repository and create a pull request for any improvements or fixes.



