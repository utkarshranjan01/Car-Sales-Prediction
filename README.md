# Car Price Prediction with Machine Learning

A regression model to predict car prices based on multiple variables including technical specifications, fuel efficiency, and market factors.

## Overview

This project implements a machine learning solution for accurately pricing cars by analyzing diverse variables like brand, specifications, and usage history. By leveraging data-driven methods, we aim to create a reliable model for estimating fair market values.

## Key Findings

- Present price and selling price show strong positive correlation
- City is the most listed car model, followed by Corolla Altis and Verna
- 2015 was the peak year for car purchases in the dataset
- Petrol vehicles dominate the market, followed by diesel
- Dealer sales channels handle majority of transactions 
- Manual transmission vehicles are more common
- Single owner vehicles generally fetch better prices

## Models Evaluated

Multiple regression models were tested including:
- Linear Regression
- Lasso Regression
- Random Forest Regression 
- Gradient Boosting Regression

The Random Forest model achieved the best performance:
- Training accuracy: 98%
- Testing accuracy: 93%
- Low mean squared error
- Good generalization on unseen data

## Features Analyzed

The dataset includes:
- Car make and model
- Year of manufacture
- Present price
- Selling price 
- Kilometers driven
- Fuel type
- Seller type
- Transmission
- Number of owners

## Data Processing

- Handled outliers using IQR and capping methods
- Applied power transformation for better distribution
- Feature scaling using StandardScaler
- Train-test split with 70-30 ratio
- Cross-validation and hyperparameter tuning

## Requirements

- Python 3.7+
- Scikit-learn
- Pandas 
- NumPy
- Matplotlib
- Seaborn
- XGBoost

## Usage

```bash
# Install dependencies
pip install -r requirements.txt

# Run the Jupyter notebook
jupyter notebook main.ipynb
```

## Key Files

- `main.ipynb`: Main Jupyter notebook with analysis and models
- `car_data.csv`: Dataset used for training and testing
- `requirements.txt`: Python package dependencies

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author

Utkarsh Ranjan

## Acknowledgments

- Dataset provided by Oasis Infobyte
- Project completed as part of Task 3 for internship program