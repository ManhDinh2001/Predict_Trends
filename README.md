# Predicting Trends in the Vietnam Index (VNI)

## Project Overview

The goal of this project is to analyze and predict future trends of the Vietnam Index (VNI) using historical data. The VNI is an important indicator of the performance of the Ho Chi Minh City Stock Exchange, and accurate predictions can provide valuable insights for investors and policymakers. This project employs advanced data analysis techniques and machine learning models to forecast the VNI trends, enabling informed decision-making in financial markets.

## Objectives

1. **Data Collection and Preprocessing**:
   - Gather historical data of the VNI.
   - Clean and preprocess the data to ensure it is suitable for analysis.

2. **Exploratory Data Analysis (EDA)**:
   - Perform EDA to understand the underlying patterns and trends in the VNI data.
   - Visualize the data to identify key characteristics and anomalies.

3. **Model Development**:
   - Develop time series forecasting models to predict future values of the VNI.
   - Utilize Prophet, a forecasting tool developed by Facebook, to model the VNI trends.

4. **Model Evaluation and Validation**:
   - Evaluate the performance of the forecasting models using appropriate metrics.
   - Validate the models to ensure their reliability and accuracy.

5. **Visualization and Interpretation**:
   - Visualize the actual and predicted values of the VNI.
   - Interpret the results to provide actionable insights for stakeholders.

## Methodology

1. **Data Collection**:
   - The historical VNI data is collected from reliable financial databases and sources.
   - The data is then loaded into a pandas DataFrame for analysis.

2. **Data Preprocessing**:
   - Handle missing values and outliers to ensure the data quality.
   - Convert the data into a format suitable for time series analysis.

3. **Exploratory Data Analysis**:
   - Plot the time series data to visualize trends, seasonality, and noise.
   - Compute summary statistics to understand the distribution and variability of the data.

4. **Model Development**:
   - Split the data into training and testing sets to evaluate the model performance.
   - Use the Prophet library to create a forecasting model.
   - Fit the model to the training data and make predictions for the test set.

5. **Model Evaluation**:
   - Assess the accuracy of the predictions using metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).
   - Compare the predicted values with the actual values to evaluate the model's performance.

6. **Visualization**:
   - Plot the actual, predicted, and future predicted values of the VNI.
   - Use matplotlib to create visualizations that illustrate the model's predictions and the actual VNI trends.

## Results

The results section includes detailed plots showing the actual VNI values, the model's predictions on historical data, and the future forecasted values. The visualizations help in understanding the model's accuracy and the expected future performance of the VNI.

## Conclusion

This project successfully demonstrates the use of time series forecasting techniques to predict the trends of the Vietnam Index. The developed model provides valuable insights that can aid investors and policymakers in making informed decisions. Future work can include incorporating additional external factors to further improve the model's accuracy and robustness.

## Tools and Technologies

- **Python**: The programming language used for the entire project.
- **Pandas**: For data manipulation and analysis.
- **Prophet**: For time series forecasting.
- **Matplotlib**: For data visualization.
- **Jupyter Notebook**: For organizing and documenting the analysis process.

## Future Work

- Incorporate more sophisticated models such as LSTM (Long Short-Term Memory) for potentially better accuracy.
- Include macroeconomic indicators and other relevant external factors in the forecasting model.
- Explore ensemble methods to combine predictions from multiple models.
