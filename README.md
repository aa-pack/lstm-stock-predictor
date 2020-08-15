# LSTM Stock Predictor

![deep-learning.jpg](Images/deep-learning.jpg)

Due to the volatility of cryptocurrency speculation, investors will often try to incorporate sentiment from social media and news articles to help guide their trading strategies. One such indicator is the [Crypto Fear and Greed Index (FNG)](https://alternative.me/crypto/fear-and-greed-index/) which attempts to use a variety of data sources to produce a daily FNG value for cryptocurrency.

In this assignment, I used deep learning recurrent neural networks to model bitcoin closing prices. One model will use the FNG indicators to predict the closing price while the second model will use a window of closing prices to predict the nth closing price.


### Files

[Closing Prices Notebook](Starter_Code/lstm_stock_predictor_closing.ipynb)

[FNG Notebook](Starter_Code/lstm_stock_predictor_fng.ipynb)

### Closing Prices vs Fear and Greed Model Evaluation

Which model has a lower loss?
- The model built on closing prices

Which model tracks the actual values better over time?
- The model built on closing prices

Which window size works best for the model?
- Both 2 and 3 seemed to work well.

