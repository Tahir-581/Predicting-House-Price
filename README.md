# Predicting-House-Price
This repository demonstrates a project aimed at predicting housing prices using a Linear Regression model. The project follows a complete machine learning workflow, starting with loading and preprocessing a real-world dataset. Missing values in the dataset are addressed by removing incomplete rows to ensure clean data. The target variable, median_house_value, is separated from the features, and categorical features are converted into numerical values using one-hot encoding for compatibility with the model. The dataset is then split into training and testing sets, with 80% used for training and 20% for evaluation, to ensure the model's performance is tested on unseen data.
The Linear Regression model is trained on the prepared training data and evaluated using standard regression metrics. The Mean Squared Error (MSE) quantifies the average squared difference between actual and predicted prices, while the R-squared (R²) metric indicates how well the model explains the variability in housing prices. To visually interpret the results, a scatter plot is generated, comparing actual and predicted housing prices, with a regression line added for reference.
The project is implemented in Python, utilizing libraries such as pandas for data manipulation, scikit-learn for model training and evaluation, and matplotlib for creating visualizations. This end-to-end implementation provides a simple yet effective workflow, making it an excellent resource for beginners looking to understand machine learning pipelines. Users can clone the repository, update the dataset file path, and run the script to reproduce the results. Contributions and suggestions to enhance the project are welcome.
