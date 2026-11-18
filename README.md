# Econ_3916_PS4

The model predicts monthly store revenue using factors such as floor area, foot traffic, local median income, and years open. After comparing different models, I selected the degree 2 polynomial model because it performed the best during cross-validation.

The model had an average cross-validation RMSE of 39,702.78. The testing RMSE was 35,757.03, with an approximate 95% confidence interval of 30,850.23 to 40,067.36. However, since I already examined the testing errors when comparing models in Step 3.1, this is not a completely independent estimate of the model's performance.

There are two main situations where the model might not perform as well. First, the model could make less accurate predictions for very large stores because the variation in revenue increases with store size. Second, the model might struggle if the relationship between store characteristics and revenue changes over time, since it was trained using data from one simulated dataset.

For the next version, I would focus on improving the model's predictions for larger stores and testing it on new monthly revenue data. I would also consider adding more useful predictors and continuing to use cross-validation to make sure the model performs well on new data.
