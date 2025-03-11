# Flight Ticket Price Prediction

## Overview

This project aims to predict flight ticket prices using machine learning models. By utilizing exploratory data analysis (EDA), feature engineering, and hyperparameter tuning, the project intends to deliver a robust predictive model.

## Data

The dataset contains information about flights, including:
- Airline
- Date of Journey
- Source and Destination
- Route
- Departure and Arrival Times
- Duration
- Total Stops
- Additional Info
- Price (target variable)

## Project Steps

1. **Exploratory Data Analysis (EDA)**
   - Analyzed price distribution and relationships with other features.
   - Visualizations included histograms, box plots, and scatter plots.

2. **Data Preprocessing**
   - Converted date and time features into useful formats.
   - One-hot encoded categorical variables like `Source` and `Destination`.
   - Mapped categorical stop information to numerical values.

3. **Feature Engineering**
   - Engineered features such as `Duration_Hours` and `Duration_Mins`.
   - Capped outliers in the `Price` column.

4. **Model Training and Evaluation**
   - Used `RandomForestRegressor` to train predictive models.
   - Hyperparameter tuning performed with `RandomizedSearchCV`.
   - Evaluated models using metrics like R-squared, MSE, MAE, RMSE, and MAPE.

5. **Model Saving and Loading**
   - Saved the trained model using `pickle` for future use.
   - Loaded the model to make predictions on test data.

## Requirements

- Python 3.x
- Required libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

## Usage

1. **Install Required Libraries**:

2. **Run Analysis**:
- Execute the provided Jupyter notebook step-by-step to clean, analyze, and model the data.

3. **Modeling and Prediction**:
- Train the Random Forest model and perform predictions.
- Evaluate the model on test data using performance metrics.

## Results

- The best model achieved an R-squared score of [insert score here].
- Visualizations highlight data trends, distributions, and model predictions.

## Conclusion

This project successfully applied machine learning techniques to predict flight prices, offering insights into factors affecting pricing. Further improvements could involve exploring additional features or using more complex models.

## License

This project is open-source under the MIT License.