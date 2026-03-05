# Bengaluru House Price Prediction

This project builds a machine learning regression model to predict house prices in Bengaluru using property features such as square footage, number of bathrooms, and balconies.

The project demonstrates a complete machine learning workflow including data preprocessing, model training, evaluation, and prediction.

---

## Dataset

The dataset contains information about Bengaluru properties including:

- Area type
- Availability
- Location
- House size (BHK)
- Total square footage
- Number of bathrooms
- Number of balconies
- House price

Dataset file:

**Bengaluru_House_Data.csv (13,000+ property records)**

### Dataset Preview

| area_type | availability | location | size | total_sqft | bath | balcony | price |
|----------|--------------|----------|------|-----------|------|--------|------|
| Super built-up Area | 19-Dec | Electronic City | 2 BHK | 1056 | 2 | 1 | 39.07 |
| Plot Area | Ready To Move | Chikka Tirupathi | 4 Bedroom | 2600 | 5 | 3 | 120 |
| Built-up Area | Ready To Move | Uttarahalli | 3 BHK | 1440 | 2 | 3 | 62 |

The target variable for the model is **price**.

---

## Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  

---

## Machine Learning Workflow

The project follows a standard machine learning pipeline:

1. Data loading  
2. Data preprocessing  
3. Feature selection  
4. Train/Test split  
5. Feature scaling  
6. Linear Regression model training  
7. Model evaluation  

---

## Evaluation Metrics

Model performance is evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

---

## Visualization

An **Actual vs Predicted Price plot** is used to visualize how well the model predicts house prices.

---

## Example Prediction

Example property:

- Location: Electronic City
- Size: 2 BHK
- Total Sqft: 1056
- Bathrooms: 2
- Balcony: 1

Predicted Price: ~39 Lakhs

The model predicts the estimated price based on property features such as size, square footage, number of bathrooms, and balconies.

---

## Conclusion

The Linear Regression model predicts Bengaluru house prices based on property features such as square footage, number of bathrooms, and balconies.

This project demonstrates how machine learning can support real estate price estimation and data-driven decision making.
