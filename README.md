# **Stock Price Prediction using Prophet**

## Overview
This project utilizes Facebook's Prophet library to forecast stock prices based on historical data. 
Prophet is particularly effective for time series forecasting tasks due to its ability to handle seasonality and outliers.

## Installation
To run this project, ensure you have Python installed. 
- Use the package manager pip to install the required dependencies:  
```python
pip install pystan prophet pandas matplotlib
```
- For jupyter notebooks:  
```python
!pip install pystan prophet pandas matplotlib
```
## Usage
### 1. Clone the Repository:  
```python
git clone <repository_url>
cd <repository_name>
```
### 2. Install Dependencies:
Ensure all required packages are installed as per the installation instructions.

### 3. Run the Project:
Modify the input data path and configurations as needed. Execute the script to train the Prophet model and generate forecasts.  
```python
python stock_prediction.ipynb
```

## Data Preparation
- Input Data: Ensure your CSV data file (`goldstock.csv` in this case) is properly formatted with columns 'Date' and 'Close' for Prophet input.

## Model Training
- Prophet model is trained using historical stock price data to learn patterns and seasonal trends.

## Results
- Forecasting: The model predicts future stock prices (`yhat`) along with upper and lower bounds (`yhat_upper`, `yhat_lower`).

## Visualization
- Plots: Visualizations of forecasted stock prices and components (trend, seasonality) are generated using Matplotlib.

![plot1](https://github.com/Dhanaa98/Gold-Price-Forecasting-with-Prophet/assets/171159250/a4a5c43f-4128-4ad8-a992-bdb7868e862f)

You can check out the Prophet library here: https://facebook.github.io/prophet/

For any questions or further assistance, please feel free to contact me.

Dhananjaya Mudunkotuwa  
dhananjayamudunkotuwa1998@gmail.com
