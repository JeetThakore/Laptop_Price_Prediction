# Laptop_Price_Prediction


## Overview

This project implements an interactive web application using Streamlit, allowing users to predict laptop prices based on specific specifications. The application provides a user-friendly interface with dropdown menus for inputting laptop details.

## Features

- **Interactive Interface:** Utilizes Streamlit to create an interactive and user-friendly web application.
- **Data Pre-processing:** Conducts rigorous data pre-processing and feature engineering to enhance the dataset's quality.
- **Granular Feature Extraction:** Implements granular feature extraction by bifurcating specifications to optimize model performance for accurate predictions.
- **Machine Learning Models:** Utilizes various ML models, including Decision Trees, Ridge and Lasso Regression, KNN, SVM, and a Voting Ensemble (Random Forest, Gradient Boosting, Extra Trees).
- **Model Performance:** Achieves the highest performance with the Voting Regressor algorithm, resulting in an R2 score of 89% and a Mean Absolute Error (MAE) of 0.15%.

## How to Use

1. **Dropdown Menus:** Select laptop specifications such as brand, type, RAM, weight, touchscreen, IPS, screen size, resolution, CPU, HDD, SSD, GPU, and OS through dropdown menus.
2. **Predict Price:** Click the "Predict Price" button to obtain the predicted price for the specified laptop configuration.

## Code Structure

- `app.py`: Contains the Streamlit application code for user interaction and price prediction.
- `pipe.pkl`: Pickle file containing the trained machine learning model.
- `data.pkl`: Pickle file containing processed data.

## Dependencies

- Streamlit
- NumPy
- Scikit-learn

## Usage

1. Clone the repository.
2. Run the Streamlit application using the command `streamlit run app.py`.
3. Input laptop specifications through the dropdown menus.
4. Click the "Predict Price" button to view the predicted price.

## Contribution

Contributions to enhance the application's functionality, optimize models, or improve code efficiency are welcome. Feel free to open issues or pull requests.



