# ml
Machine Learning installs and model selections.

First install the Python module scikit-learn.  The documentation [site](https://scikit-learn.org/stable/).

Generate random data sets to establish baselines for chi-squared type tests.


The Mushroom example dataset analysis by Niraj Verma on [Kaggle](https://www.kaggle.com/nirajvermafcb/comparing-various-ml-models-roc-curve-comparison)] is used to evaluate common machine learning tests.

The seaborn [notebook](https://nbviewer.jupyter.org/github/worker-bee-micah/ml/blob/master/00_mt_ml_catagorical_seaborn_core_build.ipynb) is a rewrite of the above mentioned kernel and mixed with code from a Pluralsight course by [Janani Ravi](https://www.pluralsight.com/courses/seaborn-visualizing-statistical-data). You will need to import seaborn, pandas and matplotlib to follow along. This is a good example of a dataset that does not contain any numerical columns, these Python modules make it easy to perform math on categorical data.


Paste the notebook URLs into NBviewer on the Python.org site if your browser is not rendering it properly or do not have Python installed.  Think of this as read only mode, you will not be able to interact with the cells.

In the notebook 01_mt_py_ml_categorial_zscores notebook I have started encoding the data set and show how to compare number values that are related, but on different scales.  The raw data is processed and saved as a file in the interim folder and a new data frame is created.  The interim data files should be read to load into a machine learning model.


