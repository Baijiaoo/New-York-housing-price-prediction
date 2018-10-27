# New-York-housing-price-prediction
This is a prediction project for New York housing price prediction by applying Machine Learning Algorithm


## Requirment
* Installing evritual enviroment on your PC to avoid Python libirary version confliction:
  * **$ pip install virtualenv**
* Setting up vitual enviroment:
  * **$ virtualenv venv**
* Pointing to which version of python you want to use under virtual enviroment:
  * **$ virtualenv -p c:\python2.x\python.exe venv**
* Activating virtual enviroment:
  * **$ activate venv**
* Deactivating virtual enviroment:
  * **$ deactivate venv**
  

## Enviroment
* Windows/Linux
* Python 2.x
* Jupyter/Pycharm


## Project Processing
### Each Step I will list the core idea & codes
* Drawing Dessign(Data Input & Check)
* Digging Foundation(Data Cleaning & Data Tranformation)
  * Data cleaning & type transformation
  * Seperating data to trainin data & testing data
  * Getting rid of abnormal data & making training target data satisfy with normal distribution
* Construction(Data Feature Engineering)
  * Using **$ pandas.get_dummies()** to make all features' data to be numerical
  * Transforming our data normalization
* Completion(Modeling)
  * Appying Ridge_Regression & Cross_Validation to findout the minimum error
  * Applytin Random_Forest & Cross_Validation to findout the minimum error
  * Samply Bagging two models, weighting = 50%/50%
