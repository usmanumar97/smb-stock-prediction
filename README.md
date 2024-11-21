# 📈 Stock Price Prediction Using LSTM and EMA

This project involves predicting stock prices using Long Short-Term Memory (LSTM) neural networks and Exponential Moving Average (EMA) as key features. The objective is to predict future stock prices based on historical data, leveraging the power of deep learning and financial analysis.

## 🔍 Project Overview

- **Data Source**: Daily stock data from SMB
- **Goal**: Predict the stock price for the next day using previous historical data
- **Model Used**: LSTM neural network
- **Key Features**: 10-day EMA and 30-day EMA for capturing trends in stock movement

## 📊 Data Preparation

The dataset underwent several preprocessing steps:

1. **Data Cleaning**: Removed unwanted columns and handled missing values.
2. **Date Handling**: Converted the `Date` column into datetime format for easier analysis.
3. **Feature Engineering**: Created new features, including the 10-day and 30-day EMA.
4. **Trend Mapping**: Converted categorical trend data (e.g., "Up-1", "Down-2") into numerical values for better interpretability.

## 🚀 Model Development

- **Model Type**: LSTM neural network
- **Training Features**: The key features used were the 10-day and 30-day EMA, along with other numerical features.
- **Steps**:
  1. **Scaling**: Scaled the data using MinMaxScaler for improved model performance.
  2. **Data Splitting**: Divided the data into training and testing sets.
  3. **Model Training**: Built an LSTM model that learns from the temporal trends in stock prices.

## 📈 Results

- **Visualization**: The plot below compares actual vs. predicted stock prices using the trained LSTM model. The LSTM was able to capture most of the significant trends:
  ![Actual vs Predicted Prices](image_link_here)

- **Performance Metric**: The model's mean squared error (MSE) was 0.89, showing an acceptable level of prediction accuracy.

## 💡 Key Takeaways

- **EMA as a Feature**: Using EMA as a feature helped the LSTM model understand the stock trends better.
- **Importance of Feature Engineering**: Transforming categorical trend columns into numerical values and creating rolling features significantly impacted the model's learning ability.

## 📚 Next Steps

- **Feature Engineering**: Add more sophisticated features like volume indicators or relative strength index (RSI).
- **Model Improvement**: Try different neural network architectures or use ensemble learning to enhance predictions.
- **Hyperparameter Tuning**: Perform a grid search for optimal hyperparameters for the LSTM.

## 🤖 Technologies Used

- **Python**: Data manipulation, model building, and visualization
- **Pandas**: Data processing
- **NumPy**: Numerical operations
- **Scikit-learn**: Data scaling and preprocessing
- **TensorFlow/Keras**: Building and training the LSTM model
- **Matplotlib**: Data visualization

## 🌟 Contributions

Contributions are welcome! If you'd like to improve this project, feel free to open an issue or submit a pull request.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📞 Contact

For questions or feedback, please reach out to **Osman Umar** at **usmanumar92@gmail.com**.

- **LinkedIn**: [Osman Janjua](https://www.linkedin.com/in/osman-janjua/)
