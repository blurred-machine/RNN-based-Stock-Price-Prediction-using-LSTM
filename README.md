# RNN-based-Stock-Price-Prediction-using-LSTM
This repository will consist of a **Long Short-Term Memory** implementation of a **Recurrent Neural Network** used to predict the stock prices of Google Stocks for the next working day based on their past few days opening price trends.
</br>

## Project Description
### About
- The project is the implementation of _Stock Market Price Predicion_ using a Long Short-Term Memory type of Recurrent Neural Network with **4 hidden layers of LSTM** and each layer is added with a **Droupout** of **0.2** and tested on various values in the Experimentations.
- The Preprocessing involves the Normailzation of the data using **MinMaxScaler** 
-  Training set was built considering the past **60 days** data of opening stock value as the learning parameters for the LSTM to predict the next day market opening stock value.
- The Data set used in the project is google's stock market data for 5 years starting from **January 2012** till **December 2016** consisting of various features of stocks like opening value and closing values, etc. which can be downloaded from [TRAIN DATA](https://github.com/paras009/RNN-based-Stock-Price-Prediction-using-LSTM/blob/master/Google_Stock_Price_Train.csv) and [TEST DATA](https://github.com/paras009/RNN-based-Stock-Price-Prediction-using-LSTM/blob/master/Google_Stock_Price_Test.csv).
- Various plots for different experimentations are shown below to understand how the model behaves over the given data showing various parameters dependence.

### Experimentations
#### Experiment-1 (60 days, 10 epochs)
- The first experiment was run for **10 epochs** and learned over past **60 days** of data to analyze how the model will perform on the data and what could be the kind of predictions we can expect from the low epoch values. 
- Below is the screenshot of the real vs the predicted regression for the test dataset.</br>

![60 Days, 10 epochs](https://github.com/paras009/RNN-based-Stock-Price-Prediction-using-LSTM/blob/master/images/60d-10eP.PNG)

#### Experiment-2 (60 days, 25 epochs)
- The first experiment was run for **25 epochs** and learned over past **60 days** of data to analyze how the model will perform on the data and what could be the kind of predictions we can expect from the low epoch values. 
- Below is the screenshot of the real vs the predicted regression for the test dataset.</br>

![60 Days, 25 epochs](https://github.com/paras009/RNN-based-Stock-Price-Prediction-using-LSTM/blob/master/images/60d-25eP.PNG)

#### Experiment-3 (60 days, 35 epochs, increasing Droupouts)
- The first experiment was run for **35 epochs** and learned over past **60 days** and also increasing the droupouts to be **0.05, 0.10, 0.15 and 0.20** for each layer respectively of data to analyze how the model will perform on the data and what could be the kind of predictions we can expect from the low epoch values. 
- Below is the screenshot of the real vs the predicted regression for the test dataset.</br>

![60 Days, 35 epochs, inc epochs](https://github.com/paras009/RNN-based-Stock-Price-Prediction-using-LSTM/blob/master/images/60d-35eP-d.PNG)

#### Experiment-4 (60 days, 50 epochs)
- The first experiment was run for **50 epochs** and learned over past **60 days** of data to analyze how the model will perform on the data and what could be the kind of predictions we can expect from the low epoch values. 
- Below is the screenshot of the real vs the predicted regression for the test dataset.</br>

![60 Days, 50 epochs](https://github.com/paras009/RNN-based-Stock-Price-Prediction-using-LSTM/blob/master/images/60d-50eP.PNG)

#### Experiment-5 (60 days, 100 epochs)
- The first experiment was run for **100 epochs** and learned over past **60 days** of data to analyze how the model will perform on the data and what could be the kind of predictions we can expect from the low epoch values. 
- Below is the screenshot of the real vs the predicted regression for the test dataset.</br>

![60 Days, 100 epochs](https://github.com/paras009/RNN-based-Stock-Price-Prediction-using-LSTM/blob/master/images/60d-100eP.PNG)

#### Experiment-6 (120 days, 100 epochs)
- The first experiment was run for **100 epochs** and learned over past **120 days** of data to analyze how the model will perform on the data and what could be the kind of predictions we can expect from the low epoch values. 
- This is the final experimentation till now before any hyper parameter tuning, as the model is fitting pretty better over the test data.
- Below is the screenshot of the real vs the predicted regression for the test dataset.</br>

![120 Days, 100 epochs](https://github.com/paras009/RNN-based-Stock-Price-Prediction-using-LSTM/blob/master/images/120d-100eP.PNG)



## Analysis and Accuracy
- I have achieved an overall loss of around **(~0.15%)** which is 0.0015 validation loss over 120 days past data training running for 100 epochs, calculated as Root mean squared error calculation.
- Future Scope: The loss can still be optimized based on the **Hyper Parameter Tuning** to fit the model much better over the testing data.

![Accuracy Python Console](https://github.com/paras009/RNN-based-Stock-Price-Prediction-using-LSTM/blob/master/images/loss.PNG)

## Contribution
- The project is built completely by Paras Varshney.</br>
![Owner](https://avatars1.githubusercontent.com/u/25752028?s=60&u=76513c2a9c298b71a67a5e8712fc5319c4c2b9bd&v=4)

Connect on [LinkedIn](https://www.linkedin.com/in/pv009)</br>
Follow on [Medium](https://medium.com/@pv009)</br>
Follow on [Github](https://github.com/paras009)</br>

#### Thank You!
