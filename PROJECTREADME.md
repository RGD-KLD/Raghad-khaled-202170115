
   # Gold Price Prediction

   This project aims to predict the price of gold for the next day based on historical price data and relevant economic metrics. The code utilizes linear regression to model the relationship between various features and the target variable.

   ### Table of Contents
   - [Suppressing Warnings](#suppressing-warnings)
   - [Libraries](#libraries)
   - [Dataset](#dataset)
   - [Initial Data Exploration](#initial-data-exploration)
   - [Correlation Heatmap](#correlation-heatmap)
   - [Predicting Gold Price Tomorrow](#predicting-gold-price-tomorrow)
   - [Model Evaluation](#model-evaluation)

   ### Suppressing Warnings
   To maintain a clean output and avoid unnecessary warnings during execution, we suppress warning messages in the code.



   ### Libraries
   The following libraries are imported to facilitate data manipulation, visualization, and modeling:

   - `pandas`: For data manipulation and analysis
   - `numpy`: For numerical computations
   - `matplotlib.pyplot`: For creating visualizations
   - `seaborn`: For statistical data visualization
   - `sklearn`: For machine learning functionalities, including model training and evaluation



   ### Dataset
   The dataset is loaded from a CSV file that contains historical gold prices and various economic metrics. Ensure the file path is correctly specified.


   ### Initial Data Exploration
   To understand the structure of the dataset, the first few rows are displayed.


   ### Correlation Heatmap
   A correlation heatmap is created to visualize the relationships between numerical features in the dataset. Only numeric columns are selected for this analysis.



   ### Predicting Gold Price Tomorrow
   Next, we prepare the data for modeling by dropping rows with missing values in the target variable, `Price Tomorrow`. Features are defined based on historical prices and relevant metrics.


   ### Model Evaluation
   The dataset is split into training and testing sets, and a linear regression model is initialized and trained. Predictions are made, and the model's accuracy is evaluated using Mean Squared Error (MSE) and R-squared (R²) scores.

   

   ### Conclusion
   This project provides a foundational approach to predicting gold prices using linear regression. Further improvements can be made by exploring other machine learning models, feature engineering, and hyperparameter tuning.
   