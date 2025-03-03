# Implementing_Linear_regression
This repository contains a Jupyter Notebook implementing Single Variable Linear Regression using Python and scikit-learn. The model predicts house prices based on the area in square feet.

Features Covered in the Notebook
📚 Libraries Used
📦 pandas – For data manipulation
🔢 numpy – For numerical operations
📈 matplotlib – For data visualization
🤖 sklearn.linear_model – For implementing Linear Regression

2. 📂 Dataset
The dataset is read from a CSV file (Areas_demo.csv)
Contains two columns:
🏠 Area (size of the house in square feet)
💰 Price (price of the house in dollars)

3. 📊 Data Visualization
Plots a scatter plot of Area vs. Price using matplotlib

4. 🏗️ Linear Regression Model
Creates an instance of LinearRegression() from sklearn
Trains the model using the dataset (fit() function)
Visualizes the regression line
Makes predictions for new values

5. 🎯 Model Prediction
Predicts house prices for a given area (e.g., 3300 sqft)
Displays the predicted price
