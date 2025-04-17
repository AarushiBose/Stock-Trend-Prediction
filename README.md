# Stock Trend Prediction

![image](https://github.com/user-attachments/assets/ccec2859-7d42-46d7-bf78-b623fd1a7eb6)



## 📚 Project Overview

The **Stock Trend Prediction** project predicts stock price trends using historical data and deep learning techniques. It provides an interactive web application for users to visualize stock trends and access original vs. predicted price comparisons for informed decision-making.

## 🎯 Project Aim

To build a predictive model for stock price trends by leveraging **deep learning** and **technical analysis**. This application enables users to:

- Visualize historical stock trends.
- Compare original vs. predicted stock prices.
- Interact via a user-friendly web interface.

## 🛠 Features

- **Historical Data Visualization:** Plot historical stock prices and moving averages.
- **Trend Prediction:** Utilize a trained LSTM model to predict stock price trends.
- **Interactive Web App:** Users can input stock tickers to generate dynamic visualizations and predictions.

## 📊 Dataset Description

- **Source:** Yahoo Finance
- **Attributes:**  
  - Open  
  - High  
  - Low  
  - Close  
  - Volume  

Data is retrieved dynamically for a given stock ticker and date range (2010-01-01 to 2023-12-31).

## 🖥️ Technology Stack

### Backend
- **Deep Learning:** TensorFlow (LSTM model)
- **Data Handling:** Pandas, NumPy
- **Data Retrieval:** `pandas_datareader`, `yfinance`
- **Scaling:** MinMaxScaler from Scikit-learn

### Frontend
- **Framework:** Streamlit
- **Visualizations:** Matplotlib

## Usage:
Enter a stock ticker (e.g., AAPL for Apple Inc.).
View data descriptions, trends, and moving averages.
Visualize original vs. predicted stock price trends.

## 📊 Model Performance
The LSTM model was trained using historical stock price data and evaluated on testing data (30% of the dataset). The model demonstrated accurate trend predictions after scaling and transformation.

## 🖼️ Screenshots
![image](https://github.com/user-attachments/assets/9dabbc6d-66a3-444f-aff7-7b52b5ed0020)

![image](https://github.com/user-attachments/assets/f7ece98e-5a96-43d1-a087-645d3873a49b)

![image](https://github.com/user-attachments/assets/e673eaaa-150e-4202-8502-968e49d66af2)

![image](https://github.com/user-attachments/assets/0e650e76-fd97-46ed-b092-6baa93d37368)

![image](https://github.com/user-attachments/assets/a76cb0b3-c288-4f0d-8dad-065d1899314e)


## 💡 Conclusion
The Stock Trend Prediction project showcases the power of deep learning in financial analytics. By providing visualizations and trend predictions through an interactive web app, it simplifies stock market analysis for traders and enthusiasts.








