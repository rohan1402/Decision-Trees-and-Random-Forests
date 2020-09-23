# Decision-Trees-and-Random-Forests

## The Project
The project predicts the employee churn using decision trees and random forest classifier. Random Forect Classifier is made in a vey interactive mode using the following libraries:-
  * IPython
  * ipywidgets
  * graphviz
  * matplotlib
  * scikit learn

The project includes the following steps:-
  1. Importing libraries
  2. Exploratory data analysis
  3. Encoding categorical values
  4. Visualize class imbalance using Yellowbricks
  5. Creating training and test sets
  6. Building an interactive Decision Tree Classifier
  7. Building an interactive random Forest Classifier
  8. Feature importance and Evaluation metrics
  9. Exploratory Data Analysis

In this project, pandas_profiling package is used for exploration of data. Generates profile reports from a pandas DataFrame. The pandas df.describe() function is great but a little basic for serious exploratory data analysis. pandas_profiling extends the pandas DataFrame with df.profile_report() for quick data analysis.

## Random Forest
A random forest is a meta estimator that fits a number of decision tree classifiers on various sub-samples of the dataset and uses averaging to improve the predictive accuracy and control over-fitting. The sub-sample size is controlled with the max_samples parameter if bootstrap=True (default), otherwise the whole dataset is used to build each tree.

## YellowBricks
Yellowbrick is a suite of visual diagnostic tools called "Visualizers" that extend the scikit-learn API to allow human steering of the model selection process. In a nutshell, Yellowbrick combines scikit-learn with matplotlib in the best tradition of the scikit-learn documentation, but to produce visualizations for your machine learning workflow!

Yellowbrick is compatible with Python 3.4 or later and also depends on scikit-learn and matplotlib. The simplest way to install Yellowbrick and its dependencies is from PyPI with pip, Python's preferred package installer.

    $ pip install yellowbrick
Note that Yellowbrick is an active project and routinely publishes new releases with more visualizers and updates. In order to upgrade Yellowbrick to the latest version, use pip as follows.

    $ pip install -U yellowbrick
You can also use the -U flag to update scikit-learn, matplotlib, or any other third party utilities that work well with Yellowbrick to their latest versions.

If you're using Anaconda (recommended for Windows users), you can take advantage of the conda utility to install Yellowbrick:

    $ conda install -c districtdatalabs yellowbrick
