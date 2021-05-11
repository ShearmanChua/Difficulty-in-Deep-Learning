# Difficulty-in-Deep-Learning
## NTU SCSE Final Year Project- Difficulty of Learning of Deep Learning Models for Fintech Applications
### Abstract

The application of Artificial Intelligence models in the domain of Financial technology, more commonly known as Fintech, has been widely studied by researchers throughout the years. With Deep Neural Networks gaining traction in the field of Artificial Intelligence, the use of Deep Neural Networks, or Deep Learning models, for Fintech applications has become more prevalent in recent years. One of the most widely studied application of Deep Learning models for Fintech, is the utilization of Deep Learning models for tasks surrounding the trading and investing of financial instruments such as Stocks or Forex. Some of these tasks include the prediction of next-day stock prices, stock portfolio management, valuation of assets, etc.
Although past research have tackled stock market prediction tasks using Deep Learning models, much of these research conducted, allow the Deep Learning models to learn by training on a large amount of training data, without full understanding of the underlying data that is used to train these models from a financial perspective. Past research also often do not take into consideration if the data used to train the Deep Learning models fully captured the various variations and economic trends present in stock data, which is necessary for the Deep Learning models to learn the stock market prediction task and enable them to generalize better and make more accurate predictions.
In addition, minimal work has been done to study how variations present in the training data used to train the Deep Learning models, affect the ability of the Deep Learning models to learn the stock market prediction task, as well as if the introduction of specific variations to the training data(based on knowledge of stock trends and factors affecting stock prices) used to train the Deep Learning models, will allow them to be able to better learn and make predictions on stocks with certain characteristics(bullish stocks, small-cap stocks etc.).
Therefore, there is a need to study how different variations introduced to the training data of the Deep Learning models affects the learning ability of the Deep Learning models for learning the task of stock market prediction, or in other words, how different variations introduced to the training data of the Deep Learning models affects the difficulty of learning of these models to learn the task of stock market prediction.
This paper proposes a novel study on the effects of introducing different variations to the training data used to train Deep Learning models(CNN and LSTM models), towards the ability of these models to learn the task of stock trading action prediction. The variations were introduced to the training data in a manner that allowed us to better understand how various variations present in the training data used for stock trading action prediction affect the ability of Deep Learning models to learn the task of stock trading action prediction. The variations introduced to the training data also took into consideration stock market specific factors likely to affect stock prices and movement.
From the results obtained from the study, we were able to better understand the effects of the introduction of certain types of data variation towards the ability of Deep Learning models to learn the task of stock trading action prediction. In addition, we also learnt which variations, when introduced to the training data used to train the Deep Leaning models, are beneficial towards helping Deep Learning models better overcome the difficulty of learning from the training data during training, to enable them to solve the task of stock trading action prediction. The results of the study will be of assistance towards future studies conducted on the use of Deep Learning models for stock market prediction tasks, by providing insights on how to improve the training of Deep Learning models for stock market prediction tasks with the use of training data introduced with variations beneficial towards helping the Deep Learning models better overcome the difficulty of learning from the training data during training.

# Difficulty of Learning of Deep Learning Models for Fintech Applications Experiments

The code that are used for the Final Year Project's main Experimental Investigation can be found in the Difficulty in Learning folder, in the folders 'New variation 1 Experiments' up till 'New variation 6 Experiments'

The detailed project findings can be found in the Final Year Report titled 'SHEARMAN CHUA_U1820058D_FYP Final Report_SCSE20-0507'.

The official Final Year Project Report for this Final Year Project can be also found in the NTU Digital Repository under the following link:
https://hdl.handle.net/10356/148075

## Variation 1 Experiments

For this set of experiments conducted, we varied the dimensionality and presentation of the training data to the two Deep Learning models, in order to observe if the two Deep Learning models are able to better overcome the difficulty of learning the task of stock trading action prediction for one form of data input, when compared to another.

### Image Representation
![Image of image representation](https://github.com/ShearmanChua/Difficulty-in-Deep-Learning/blob/main/images/image.jpg)
### Time-Series Representation
![Image of Application](https://github.com/ShearmanChua/Difficulty-in-Deep-Learning/blob/main/images/time-series.jpg)
## Variation 2 Experiments

For this set of experiments conducted, we varied the number of past trading days to be used as the lookback period for the training data of the 4 technical indicators used to train the Deep Learning models. The number of days used as lookback period for this set of experiments are, 5, 10, 15, 20, and 25 days. These experiments were conducted in order to investigate how the number of time-steps, or
lookback period, for time-series data, affects the ability of Deep Learning models to identify stock trading cycles in the input data sequences and make accurate stock trading action predictions from them.

![Image of v2](https://github.com/ShearmanChua/Difficulty-in-Deep-Learning/blob/main/images/variation%202.png)

## Variation 3 Experiments

For this set of experiments conducted, we varied the ratio of the number of training samples within the training dataset for each class( “buy” class, “sell” class, “hold class), in order to observe if the ratio of the number of training samples for each class in the training dataset, affects the difficulty in learning of the task of stock trading action prediction for Deep Learning models.

![Image of v3](https://github.com/ShearmanChua/Difficulty-in-Deep-Learning/blob/main/images/variation%203.png)

## Variation 4 Experiments

For this set of experiments conducted, we varied the stock cycle phase in which to extract stock data from, to build the training datasets, to build variant training dataset with stock data extracted only from a particular phase of the stock cycle. From this set of experiments, we would like to observe if a model trained only with a training dataset built using only one particular stock cycle phase is able to achieve high prediction accuracies for making predictions on the test dataset built using data only from the same stock cycle phase, as well as how well will the model perform when making predictions on test datasets built with data from other phases of the stock cycle.

![Image of v4](https://github.com/ShearmanChua/Difficulty-in-Deep-Learning/blob/main/images/variation%204.jpg)

## Variation 5 Experiments

For this set of experiments conducted, we introduced to the training data used to train the Deep Learning models for the task of stock trading action prediction, the inclusion of the stock price data of another stock from the same business sector, in addition to the data of the original four technical indicators of the particular stock being used to train the Deep Learning models, when training the Deep Learning models on a particular stock. From the experiments, we would like to observe if the inclusion of stock price data of the market leader stock in the same business sector, to the training data of the stock we are using to train the Deep Learning models, will aid the Deep Learning models in terms of the difficulty of learning the task of stock trading action prediction.

![Image of v5](https://github.com/ShearmanChua/Difficulty-in-Deep-Learning/blob/main/images/variation%205.png)

## Variation 6 Experiments

For this set of experiments conducted, we varied the category of the Market Capitalization of the stocks used to build the training datasets for training the Deep Learning models, in order to observe if the type of Market Capitalization of the underlying stocks used for the building the training datasets used to train the Deep Learning models, affect their performance in the task of stock trading action prediction, or in other words their ability to learning the stock trading action prediction task.

![Image of v6](https://github.com/ShearmanChua/Difficulty-in-Deep-Learning/blob/main/images/variation%206.png)
