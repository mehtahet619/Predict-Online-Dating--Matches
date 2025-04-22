# Predict Online Dating Matches

This project predicts whether a person will purchase a VIP membership on an online dating platform based on their personal attributes and activity. The model uses features such as gender, income, age, attractiveness, and number of matches to make predictions. The app is built with **XGBoost** for prediction and **Gradio** for the interactive web interface.

## Features

- **Gender**: Male/Female
- **PurchasedVIP**: Whether the user purchased a VIP membership (Yes/No)
- **Income**: User's income in dollars
- **Children**: Number of children the user has
- **Age**: User's age
- **Attractiveness**: User's self-reported attractiveness (scale from 0 to 10)
- **Matches**: Number of matches the user has made

The model predicts whether a user is likely to purchase a VIP membership based on the above features.

## Requirements

Before running the application, ensure that you have the following installed:

- Python 3.x
- Required Libraries:
  - `gradio`
  - `xgboost`
  - `pandas`
  - `scikit-learn`
  - `numpy`

To install the required libraries, run the following command:

```bash
pip install gradio xgboost pandas scikit-learn numpy
