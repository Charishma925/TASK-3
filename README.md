# Task 3: Linear Regression

## Objective
Implement and understand **Simple** and **Multiple Linear Regression** using Python and machine learning libraries.

The goal is to:
- Build regression models
- Evaluate their performance
- Visualize results
- Interpret the model coefficients

---

## Tools and Libraries
- **JupyterNotebook**
- **Pandas** – for data loading and preprocessing
- **Scikit-learn** – for building and evaluating the regression models
- **Matplotlib** – for visualization

---

## Steps to follow
1. **Import and Preprocess the Dataset**
   - Load the dataset into a Pandas DataFrame.
   - Check for missing values and perform any necessary cleaning.
   
2. **Split Data into Train-Test Sets**
   - Use `train_test_split` from `sklearn.model_selection` to divide the data into training and testing sets.

3. **Fit a Linear Regression Model**
   - Use `LinearRegression` from `sklearn.linear_model` to fit the model on the training data.

4. **Evaluate the Model**
   - Evaluate using:
     - Mean Absolute Error (MAE)
     - Mean Squared Error (MSE)
     - R-squared Score (R²)

5. **Plot Regression Line and Interpret Coefficients**
   - For Simple Linear Regression:
     - Plot the data points and the regression line.
   - Interpret the slope and intercept of the model.
## Insights
- TV and Radio advertising have a strong positive effect on Sales.
- Newspaper advertising shows less impact on Sales compared to TV and Radio.
- Linear Regression provides a simple and interpretable baseline model for sales prediction.


