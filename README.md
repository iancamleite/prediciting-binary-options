
## Predicting forex binary options using time series data and machine learning

Here we'll get past forex data and apply a model to predict if the market will close red or green in the following timestamps.

I want to credit [@hayatoy](https://github.com/hayatoy) with the project [ml-forex-prediction](https://github.com/hayatoy/ml-forex-prediction) under the [MIT License](https://github.com/hayatoy/ml-forex-prediction/blob/master/LICENSE). I was inspired to use a Gradient Boosting Classifier by this project, which was implemented using Python 2 and Yahoo Finance.


### About the data

* The csv files were extracted from [Dukascopy](https://www.dukascopy.com/swiss/english/marketwatch/historical/). 
* The forex that we try to predict here is USD/CAD. 
* All datetime indexes are in GMT.

### About installation
To run this project, you'll need the following enviroments and libraries:
* Python 3.X
* Jupyter Notebook
* Numpy
* Pandas
* Scipy
* Sklearn
* Matplotlib
