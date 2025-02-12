# Stock Price Prediction model

- Created for the practical marks fullfilment for my third sem course of **Foundation of Data Science**, This Python based project uses multitude of libraries and various **Concepts** like **Data cleaning, EDA, Feature Engineering and Modelling** which were studied in the course to build a predictive model that predicts the stock price of tesla.

- The libraries used in this project are:
  | SN|Library |
  |----|---|
  |1.|Pandas|
  |2.|Numpy|
  |3.|Seaborn|
  |4.|Matplotlib|
  |5.|Scikit-learn|

- By Leveraging the linear regression model provided by `scikit-learn` , this project predicts the stock prices using the [Tesla.csv_dataset](./tesla.csv)

- This model's accuracy was accessed based on the following metrics: <br>
  |Metric | Train | Test|
  |--------|----------|-----------------|
  |R<sup>2</sup> score | 0.8659 | 0.8611|
  |MSE | 1821.3834 | 1780.9875

- Although not perfect, the **R<sup>2</sup>** and **MSE** scores are by no means inadequate. Incorporating additional features, more advanced models (e.g., polynomial regression or neural networks), or fine-tuning hyperparameters could further improve performance of this model.
