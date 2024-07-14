# ML_Project-Gold_Price_Prediction

This project delves into the fascinating realm of gold price prediction using a Random Forest regression model. It leverages the power of Random Forest to uncover patterns in historical gold price data and associated influencing factors, aiming to forecast future gold prices.

### Data
  This directory stores the gold price data in CSV format. It's assumed the dataset contains attributes like:
  
  - Date
  - SPX (is a free-float weighted measurement stock market index of the 500 largest companies listed on stock exchanges in the United States.)
  - GLD (Gold Price)
  - USO (United States Oil Fund)
  - SLV (Silver Price)
  - EUR/USD (currency pair quotation of the Euro against the US)
    
**notebooks**: This directory contains the Jupyter Notebook (`gold_price_prediction.ipynb`) for data exploration, preprocessing, model training, evaluation, and visualization.

### Running the Project
The main script (main.py or similar) typically follows these steps:

1. Load the data: Load the Gold Price dataset using appropriate libraries.
2. Data Preprocessing: Clean and prepare the data for modeling. This might involve handling missing values, scaling numerical features, and potentially encoding categorical features (if present).
3. Split Data: Divide the data into training and testing sets. The training set is used to train the logistic regression model, and the testing set evaluates its performance on unseen data.
4. Model Training: Train the logistic regression model on the training data.
5. Model Evaluation: Evaluate the model's performance on the testing set using metrics like accuracy, precision, recall, and F1-score.
6. (Optional) Model Saving: Save the trained model for future use.

### Additional Notes
 - This project showcases random forest regression using gold price prediction. You can explore other machine learning models and hyperparameter tuning for potentially better results.
 - Feel free to modify the code to experiment with different functionalities, like making predictions for loan status.

### Resources
 - Scikit-learn Random Forest Regression Documentation: [https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html)
 - Kaggle Gold Price Prediction Dataset Description: [https://www.kaggle.com/datasets/aakash013/gold-price-prediction-dataset](https://www.kaggle.com/datasets/aakash013/gold-price-prediction-dataset)

### Customization

- You can modify the Jupyter Notebook to:
    - Experiment with different hyperparameters for the Random Forest model (number of trees, maximum depth, etc.)
    - Try other regression algorithms like Support Vector Regression (SVR) or Gradient Boosting for comparison.
    - Explore advanced feature engineering techniques like time series analysis (e.g., moving averages, seasonality) to capture temporal patterns in gold prices.

By leveraging Random Forest regression, we can gain insights into historical trends and potentially make informed predictions about future gold prices. This project lays the foundation for further exploration in this dynamic domain.
