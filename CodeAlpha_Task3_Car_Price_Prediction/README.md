Car Price Prediction

## About the Project

This project is about predicting the selling price of used cars using
Machine Learning.

I used a car dataset containing details such as the current price,
kilometers driven, fuel type, transmission, number of previous owners,
and manufacturing year.

The project was completed as part of my CodeAlpha internship.

## Tools and Libraries

For this project, I used:

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Dataset

The dataset contains information about different used cars.

Some of the main columns are:

- Car Name
- Year
- Present Price
- Driven Kms
- Fuel Type
- Selling Type
- Transmission
- Owner
- Selling Price

The `Selling_Price` column is used as the value that the model needs
to predict.

## What I Did

The project was completed in a few steps:

1. Loaded and explored the dataset.
2. Checked the data for missing values and duplicates.
3. Created a new `Car_Age` feature using the manufacturing year.
4. Converted the text-based columns into numerical values.
5. Divided the data into training and testing sets.
6. Trained a Linear Regression model.
7. Used the model to predict car prices.
8. Evaluated the predictions using different evaluation metrics.
9. Created graphs to compare actual and predicted prices.
10. Tested the model with details of a new car.

## Machine Learning Model

I used **Linear Regression** for this project because it is a simple
regression algorithm and is suitable for learning how different car
features can be used to predict a numerical value such as price.

## Model Evaluation

The model was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

These metrics helped me understand how well the model performed on
the test data.

## Files in this Folder

- `CodeAlpha_Car_Price_Prediction.ipynb` - The complete Google Colab
  notebook.
- `car data.csv` - Dataset used for the project.
- `README.md` - Information about the project.

## Conclusion

This project helped me understand the basic workflow of a Machine
Learning regression problem, starting from data preprocessing and
feature engineering to model training and evaluation.

It also shows how Machine Learning can be used in a practical
situation to estimate the price of a used car.
