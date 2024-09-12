# **Google Stock Price Prediction with LSTM**

## Project Overview

This project aims to predict Google's stock prices using Long Short-Term Memory (LSTM) networks, one of the deep learning techniques. The model, trained on data ranging from early 2012 to the end of 2016, will forecast the opening price and general market trend (up or down) for January 2017.

### Why LSTM?

- **Time Series Data**: Stock prices are time-dependent. LSTMs excel at capturing long-term dependencies in time series data.
- **Long-Term Memory**: LSTM networks can retain information over long periods, making them suitable for analyzing market trends.
- **Feedback Mechanism**: LSTMs use their previous predictions to make future forecasts, enhancing the model's ability to predict trends.

## Dataset

- **Date Range**: Training period covers from early 2012 to the end of 2016, with January 2017 reserved for testing.
- **Preprocessing**: The dataset will undergo preprocessing steps such as scaling and normalization.

## Model Architecture

- **LSTM Layers**: Multiple LSTM layers are used to increase the model’s learning capacity.
- **Optimization Algorithm**: The Adam optimization algorithm is used for efficient training.

## Training Process

- **Data Split**: The dataset is divided into training and testing sets.
- **Number of Epochs**: Specifies how many times the model will be trained on the entire dataset.
- **Batch Size**: Defines the number of samples the model will process before updating weights during training.

## Evaluation

- **Visualization**: The results will be visualized using graphs and tables to assess the model's performance.

## Libraries

- **TensorFlow/Keras**: For building the deep learning model.
- **NumPy**: For numerical computations.
- **Pandas**: For data analysis and manipulation.
- **Matplotlib**: For visualizing the data and results.

