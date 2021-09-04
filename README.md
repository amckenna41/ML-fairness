# csc4009-FIP-ML
Analysing fairness, bias and privacy in Machine Learning through the census-income dataset for CSC4009 Comp Sci module.

Dataset
-------

The Census-Income dataset is a popular and benchmark dataset for ML, consisting of a series of data collected from the 1993 American census database.
The main objective of the ML tasks is to predict wheter an individuals income will exceed $50k/year based on a series of attribute values. Due to 
the makeup of the dataset as well as the context of the geopolitical landscape during the year of the dataset's collection, a range of fairness, bias 
and privacy metrics can be applied to it to analyse each of the aforementioned. 
The Python notebook in the repository (.pynb) analyses all three of fairness, bias and privacy using a series of techniques and benchmark tests,
reporting the results in a series of visualisations. <br><br>
The dataset is available from the UCI ML Repository at:
http://archive.ics.uci.edu/ml/datasets/Census+Income  

Installation
------------

Install all required dependencies:
```
pip install -r requirements.txt
```

Files
------
* `census-income.ipynb` -  Python notebook for analysing dataset 
* `adult.data` -  census income training data
* `adult.test` -  census income test data
* `adult.names` -  census income attribute label names and descriptions
* `requirements.txt` -  list of required Python library and dependancies
