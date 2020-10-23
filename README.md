# Credit Scoring - default prediction among credit card holders in Python
### Author: Adrian Żelazek

In this project was used dataset which contains 30000 observations as well as 24 variables. The main target of this project was to build predictive medels to determine the Probability of Default (PD) of clients hold credit card. This project can be called Credit Scoring, although this case is slightly different from the classic definition. To predict the targer variable 3 Logistic Regression models have been built.

The project includes Exploratory Data Analysis, grouping, visualization, splitting the training and testing data, tuning of hyperparameters by GridSearchCV method, predictions as well as Model Evaluation. Furthermore, results of training and test datasets were compared with each other to exclude possible of overfitting. 

This project was developed for the purpose of practicing machine learning and data mining in Python.
##### It is preferred to run/view the project via Jupyter Notebook (.ipynb), sometimes it is required to press "Reload" to load the file, than via a browser (HTML). To see the HTML version you first need to download the HTML file and then run it in your browser.

### Programming language and platform
* Python version is 3.7.4
* Jupyter Notebook

### Libraries
* Pandas version is 0.25.1
* Scipy version is 1.5.2
* Scikit-learn is 0.22.2.post1
* Statsmodels is 0.10.1
* Numpy version is 1.16.5
* Matplotlib version is 3.1.2
* Seaborn version is 0.9.0

### Algorithms
* Logistic Regression
* Information Value (IV)
* GridSearchCV
* Normaltest (hypothesis about normal distribution)
* Spearman's correlation coefficient
* Crammer's V coefficient
* z-score
* Dummy Coding
* Odds Ratio
* Marginal Effects
* Forward variables selection
* Backward variables selection

### Methods of model evaluation
* Gini
* AUC
* ROC
* Confusion Matrix
* Classification Report and indicators: Accuracy, Recall, Precision, F1

### Results
Model 2 after forward variables selection presents the best results, among others:
* percentage of correct forecasts = 0.81
* Gini index = 0.38
* area under the roc curve = 0.69


