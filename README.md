# Predicting Google Stock Price

This Jupyter Notebook demonstrates a machine learning approach to predicting Google's stock prices using Recurrent Neural Networks (RNN). The project includes data preprocessing, model creation, and performance evaluation.

## Overview

The notebook covers:
- Loading and exploring stock price data.
- Preprocessing the data using scaling techniques.
- Building and training RNN models to predict stock prices.
- Visualizing predictions and evaluating model performance.

## Requirements

The necessary dependencies are listed in the `requirements.txt` file. To install them, run:

```bash
pip install -r requirements.txt
```

## Datasets

The project uses two datasets:
1. **`Google_Stock_Price_Train.csv`**: Contains historical stock price data used for training the model.
2. **`Google_Stock_Price_Test.csv`**: Contains stock price data used for testing and evaluation.

Ensure these files are in the same directory as the notebook or update the file paths in the code accordingly.

## Structure

1. **Library and Data Loading**
   - Necessary libraries are imported, and the training and testing datasets are loaded for analysis.
   
2. **Data Preprocessing**
   - Functions for transforming data, scaling features, and preparing input-output sequences for the RNN are implemented.
   - Data types are adjusted to optimize memory and compatibility with machine learning models.

3. **Model Building**
   - RNN architecture is defined and built using TensorFlow/Keras.
   - Techniques like data scaling (e.g., `StandardScaler`, `MinMaxScaler`) are used for better model performance.

4. **Training and Evaluation**
   - The model is trained on historical stock prices.
   - Predictions are visualized against actual prices to assess model accuracy.

5. **Conclusion**
   - Summary of the findings and potential future improvements.

## Usage

1. Clone the repository or download the notebook and the datasets.
2. Place `Google_Stock_Price_Train.csv` and `Google_Stock_Price_Test.csv` in the same directory as the notebook.
3. Open the notebook and run all cells sequentially.

```bash
jupyter notebook Predicting\ Google\ Stock\ Price.ipynb
```

4. Observe the predictions and performance metrics.

## Customization

- Modify the scaler in the `data_preprocessing` function to experiment with different scaling techniques.
- Adjust the RNN architecture (e.g., number of layers, neurons, activation functions) to optimize performance.
- Replace the datasets with any other stock data to apply the model to different markets.

## Output

The notebook generates the following:
- A plot comparing predicted stock prices to actual prices.
- Insights into model performance and potential areas for improvement.

## License

This project is licensed under the MIT License. Feel free to use and modify it for educational or commercial purposes.
