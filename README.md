# BEng-Dissertation
## Deep learning model for general stock price movement prediction

<p aligh='justify'> This dissertation takes on the problem of general stockpric emovement prediction based on technical data. Its purpose is to argue if there exist universal price dynamics. The proposed approach involves deep learning techniques, where long short-term memory (LSTM) recurrent neural network is used to predict stock price movement. Unlike many studies in the field, the algorithm is trained and tested on different stock companies to reason about general price dynamics. The dataset consists of over 7k companies listed on NYSE, NASDAQ and NYSEMKT markets providing enough samples to draw relevant conclusions. The architecture of the artificial neural network is established using sequential model-based optimization with tree-structured Parzen estimator. Furthermore, 20m odels are trained and evaluated during the repeatability test. It enables to obtain variability window, and reflect the importance of hyperparameter tuning. Additionally, several data processing operations and feature sets are taken into consideration: raw price history and volume, a percentage change of inputs, denoizing with exponentially weighted moving average, calculating technical indicators, dropping highly correlated features. After finding the most promising configuration, a study is conducted into the impact of the history as well as prediction horizon lengths on the algorithm's accuracy. Finally, the proposed model is trained and tested on the whole dataset to obtain the level of general predictability of the stock prices based on technical data.
</p>
