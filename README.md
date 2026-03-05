
# Features of the Model

- total_bill: total bill in dollars including tax (float)
- tip: tip given to waiter in dollars (float)
- sex: gender of the person paying the bill (0 = Female, 1 = Male)
- smoker: whether the person smoked or not (0 = No, 1 = Yes)
- day: day of the week (converted to dummy variables: day_Fri, day_Sat, day_Sun; 1 = this day, 0 = other day)
- time: lunch or dinner (0 = Lunch, 1 = Dinner)
- size: number of people at the table (int)

# Model Choice

LinearRegression was used because:
- the data had few features
- it was necessary to predict a number, not a category


# Model Evaluation

Model evaluation metrics
- R² (R-squared score): 0.47
- MAE (Mean Absolute Error): 0.79$
- Average predicted tip on test set: 2.93$