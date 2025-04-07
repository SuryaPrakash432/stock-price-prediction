# 🧠 Stock Market Prediction with Sentiment Analysis

This repository contains two core Jupyter notebooks focused on building a stock price prediction model by incorporating financial news sentiment analysis.

## 📁 Project Structure

- `sentiment analysis to final dataset.ipynb`:  
  Performs sentiment analysis on news headlines using the VADER model and merges the results with stock market data. It uses the Finnhub API to gather real-time news data.

- `final model.ipynb`:  
  Trains an LSTM-based deep learning model to predict stock prices using both market indicators and sentiment scores. Includes feature scaling, PCA for dimensionality reduction, and performance evaluation.

## 📌 Features

- Real-time news sentiment scoring.
- LSTM-based time-series model for stock prediction.
- Evaluation using MAE, RMSE, and R².
- Modular code with clear preprocessing and model evaluation steps.

## 🚀 How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Add your **Finnhub API Key** in the `sentiment analysis` notebook:
    ```python
    api_key = 'your_finnhub_api_key'
    ```

4. Run notebooks in order:
    - `sentiment analysis to final dataset.ipynb`
    - `final model.ipynb`

## 📦 Requirements

- pandas  
- numpy  
- vaderSentiment  
- requests  
- tensorflow  
- scikit-learn  
- matplotlib  
- scipy  

> You can install all dependencies using:  
```bash
pip install pandas numpy vaderSentiment requests tensorflow scikit-learn matplotlib scipy
