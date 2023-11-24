# Stock Price Prediction Project using Machine Learning

## Introduction

This project aims to predict stock prices using machine learning algorithms. Three different algorithms were used: Logistic Regression, SVC, and XGBClassifier. The accuracy of each algorithm was evaluated, and the best-performing algorithm was selected for use in the final model.

## Data

The data for this project was obtained from the Yahoo Finance website. The data includes the daily opening, high, low, and closing prices of a stock for a period of five years.

## Preprocessing

The data was preprocessed by normalizing the prices and converting the categorical features (e.g., date) into numerical features.

## Feature Engineering

Several features were engineered from the raw data, including moving averages, Bollinger Bands, and relative strength index (RSI).

## Models

Three different machine learning algorithms were used to predict stock prices: Logistic Regression, SVC, and XGBClassifier.

## Results

The accuracy of each algorithm was evaluated using the holdout method. The accuracy of the Logistic Regression model was 0.5702, the accuracy of the SVC model was 0.5330, and the accuracy of the XGBClassifier model was 0.5165.

## Conclusion

The Logistic Regression model was the most accurate of the three algorithms tested. The model was able to achieve an accuracy of 0.5702, which is significantly better than the accuracy of the other two models.

## Next Steps

The next steps for this project will be to improve the accuracy of the model by using a larger dataset and more sophisticated machine learning algorithms.

## Dependencies

The following libraries were used in this project:

* pandas
* numpy
* sklearn
* matplotlib

## Usage

To run this project, you will need to install the following libraries:

* pandas
* numpy
* sklearn
* matplotlib

Once you have installed the libraries, you can run the project by following these steps:

1. Clone the repository to your computer.
2. Open the project in a Python IDE.
3. Run the `main.py` script.

## License

This project is licensed under the MIT License.
