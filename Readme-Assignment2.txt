Using principal component analysis.

1. Data Exploration:
    a. Load the diabetes dataset using scikit-learn.
    b. Explore the dataset's features and target variable (provide mean, range and standard deviation for each).  What are the names of each feature and what is the target feature? 
2. Data Preprocessing:
    a. Standardize the features using StandardScaler.
    b. Split the dataset into training and testing sets.
3. Linear Regression Without PCA:
    a. Build a linear regression model without using PCA.
    b. Calculate the model's performance using mean squared error.
4. Apply PCA:
    a. Apply PCA to the standardized training set.  Maintain at least 95% of the variance.
    b. Plot a scree plot to visualize the explained variance ratio.  Comment on this plot.
    c. Build a linear regression model using PCA.
    d. Calculate the model's performance using mean squared error.
5. Comparison:
    a. Compare the mean squared errors of both models.   Comment on the result.
    b. Visualize the predictions with scatter plots for both models on the same plot.  Use different colours to differentiate the two models.  Plot the predicted values on the Y axis and the true values (targets from the dataset) on the X axis.  Comment on the results.