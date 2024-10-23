# LA-Crime-Data-Analysis-and-Forecasting
This repository contains a Python-based project that analyzes and predicts crime occurrences across various locations using time series forecasting techniques. The project employs several libraries for data manipulation, visualization, and model building.

## Technologies and Libraries Used

### 1. **Python**
   - The main programming language used for the project, leveraging its robust ecosystem for data analysis and machine learning.

### 2. **Libraries**

#### a) **Pandas**
   - **Purpose**: Data manipulation and preparation.
   - **Key Functions**:
     - `pd.read_csv()`: Load CSV files into a DataFrame.
     - `.loc[]`, `.iloc[]`: Select and filter specific data in the DataFrame.
     - `pd.concat()`: Concatenate DataFrames for merging predictions.

#### b) **Matplotlib**
   - **Purpose**: Basic data visualization.
   - **Key Functions**:
     - `plt.plot()`: Plot line graphs.
     - `plt.figure()`: Define the figure size.
     - `plt.show()`: Display the plot.

#### c) **Seaborn**
   - **Purpose**: Statistical data visualization (advanced plots).
   - **Key Functions**:
     - `sns.heatmap()`: Visualize correlation matrices.
     - `sns.countplot()`: Create bar plots for categorical data.
     - `sns.boxplot()`: Detect outliers.
     - `sns.histplot()`: Plot histograms for frequency distribution.

#### d) **Scikit-learn (sklearn)**
   - **Purpose**: Machine learning tasks (regression modeling).
   - **Key Functions**:
     - `LGBMRegressor()`: The LightGBM regressor for predicting future values in time series.

#### e) **LightGBM**
   - **Purpose**: High-performance gradient boosting framework.
   - **Key Functions**:
     - `LGBMRegressor()`: Gradient boosting model for efficient regression tasks.

#### f) **Skforecast**
   - **Purpose**: Time series forecasting with autoregressive models.
   - **Key Functions**:
     - `ForecasterAutoreg()`: Builds autoregressive forecasting models.
     - `forecaster.fit()`: Trains the model using historical data.
     - `forecaster.predict()`: Predicts future time series data based on trained models.

## Project Overview

This project forecasts crime data based on historical data points, such as crime types and locations, leveraging time series analysis and machine learning.

### Steps Involved:
1. **Data Loading and Preparation**: Using Pandas to clean and manipulate the dataset.
2. **Data Visualization**: Using Matplotlib and Seaborn for understanding trends, correlations, and distributions.
3. **Time Series Modeling**: Using the Skforecast library along with the LightGBM model to make predictions about future crime occurrences.
4. **Evaluation**: Predictions are visualized and evaluated based on the forecasted data for specific areas and crime types.

