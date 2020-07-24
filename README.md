
# DeepBuffett
Applying Deep Learning techniques to build neural networks for automated fundamental analysis of equities from quarterly (10-Q) and annual (10-K) financial reports.

Read the full report here: [Final Project Report](https://github.com/rtkg12/DeepBuffett/blob/master/Project%20Report.pdf)

### Abstract

The modern stock market is a critical foundation of the global economy. Making the most ideal decisions on when to buy, hold, or sell certain stocks are the key to earning returns on investments in the stock market. In order to make decisions, investors must know when a stock for a company is overvalued or undervalued compared to the company’s true value. Analyzing the fundamental financial data of a company enables investors to determine a company’s true value. 

Our aim for this project is to use fundamental financial data of corporations to train deep learning models which output decisions on whether to buy or sell a certain corporation’s stock, based on whether the stock is overvalued or undervalued. We used 143 input features, all of which are fundamental data from financial statements of publicly traded companies in the U.S. The output of our aggregated network is a buy (1) or a sell (0) decision. We trained several neural network models using this data. Initial results for all models were poor, but with hyperparameter tuning and optimization, we were able to increase accuracy. We found that Multi-layer Perceptrons with 3 hidden layers, ReLU activations and dropout after each layer work well. Further, we use multiple trained models to make a prediction in a method inspired by Random Forests, which improves accuracy and provides more reliable results for our end goal. Overall, the results seem promising but need further testing and validation on a bigger and better dataset, with different network architectures and with more models in our Random Neural Network Forest. However, the current outputs provide a general indication of whether a certain stock is undervalued or overvalued, which is a valuable piece of information for investors.
