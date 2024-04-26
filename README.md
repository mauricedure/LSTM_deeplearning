# LSTM_deeplearning

# Crypto Fear and Greed Index (FNG) Analysis with Deep Learning Models

Cryptocurrency investors frequently seek to leverage sentiment analysis from social media and news articles to inform their trading decisions. One prominent indicator used for this purpose is the Crypto Fear and Greed Index (FNG), which aims to gauge market sentiment through various data sources and produce a daily FNG value for cryptocurrencies. In this project, I have developed and evaluated deep learning models utilizing both FNG values and simple closing prices to ascertain whether the FNG indicator provides a superior signal for cryptocurrencies compared to traditional closing price data.

## Overview

This repository contains code and resources for building and evaluating deep learning models to analyze cryptocurrency data. The primary focus is on comparing the predictive power of the Crypto Fear and Greed Index (FNG) against simple closing prices in forecasting cryptocurrency prices.

## Features

- **FNG Indicator**: Utilize the Crypto Fear and Greed Index (FNG) as an additional feature for modeling cryptocurrency price movements.
- **Deep Learning Models**: Implement various deep learning architectures, such as recurrent neural networks (RNNs), long short-term memory networks (LSTMs), and convolutional neural networks (CNNs), to model cryptocurrency price data.
- **Model Evaluation**: Evaluate the performance of deep learning models using both FNG values and closing prices as input features.
- **Comparison**: Conduct a comparative analysis to determine whether the FNG indicator provides a better signal for cryptocurrency price prediction compared to traditional closing price data.

## Contents

1. **Data Collection**: Gather historical cryptocurrency price data, including FNG values and closing prices, from relevant sources such as exchanges and data APIs.
   
2. **Data Preprocessing**: Clean and preprocess the cryptocurrency data, including feature engineering and normalization.

3. **Model Development**: Implement deep learning models using libraries such as TensorFlow or PyTorch, incorporating both FNG values and closing prices as input features.

4. **Model Training**: Train the deep learning models on the prepared cryptocurrency dataset, optimizing hyperparameters and validating performance.

5. **Model Evaluation**: Evaluate the trained models using appropriate metrics, comparing the performance of FNG-based models against those using only closing prices.

6. **Results Analysis**: Analyze the results to determine the effectiveness of the FNG indicator in predicting cryptocurrency prices compared to traditional closing price data.

## Usage

1. Clone this repository to your local machine.
2. Install the necessary dependencies specified in the `requirements.txt` file.
3. Prepare the cryptocurrency dataset, ensuring it includes FNG values and closing prices.
4. Execute the provided scripts for data preprocessing, model development, training, and evaluation.
5. Analyze the results and draw conclusions regarding the predictive power of the FNG indicator for cryptocurrency price forecasting.

## Contributions

Contributions to enhance the deep learning models, improve model evaluation techniques, or incorporate additional features are welcome. Fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

Thank you for exploring the Crypto Fear and Greed Index (FNG) analysis with deep learning models! 📈🔍
