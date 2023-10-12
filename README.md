# Machine Learning Test Project: Housing Price Prediction

This is a machine learning test project exploring solutions for the [Housing Prices Competetion](https://www.kaggle.com/competitions/home-data-for-ml-course) on Kaggle.

## Data
The data represents sales of houses in Ames, Iowa from 2006 to 2010. It was presented by Dean De Cock in 2011 in the following publication:
[Dean De Cock. Ames, Iowa: Alternative to the Boston Housing Data as an End of Semester Regression Project. Journal of Statistical Education, 19(3), 2011](https://jse.amstat.org/v19n3/decock.pdf).

The data can be found in the [data](data/) directory. It is split into a test set [test.csv](data/test.csv) (without target) and a train set [train.csv](data/train.csv) (with target) with a 50%-50% split. The data contains altogether 2919 observations and 79 features which are described in [data_description.txt](data/data_description.txt). There is also a file [sample_submission.csv](data/sample_submission.csv) showing an example submission for the Kaggle challenge.

The data set is licensed under the GPL-2 (GNU General Public License Version 2) license, see [LICENSE](LICENSE).

## Project Description
In the directory [jupyter_notebooks](jupyter_notebooks/), there are multiple jupyter notebooks with different approaches for predicting the house prices or analyzing the data set.

The resulting predictions are stored in the folder [results](results/).

### Notebook 1
Given by [01_basic.ipynb](jupyter_notebooks/01_basic.ipynb).

The goal for the first notebook is to create a complete basic solution by building a `scikit-learn` pipeline. It contains all required steps to make predictions. But especially the preprocessing is not very elaborate and specific to the data.

### Notebook 2
Given by [02_automl.ipynb](jupyter_notebooks/01_automl.ipynb).

The goal of the second notebook is to test multiple AutoML libraries and see whether they yield a better performance than the basic solution from the first notebook [01_basic.ipynb](jupyter_notebooks/01_basic.ipynb). The following AutoML libraries are tested:
- TPOT
- Hyperopt-Sklearn

### Notebook 3
Given by [03_exploratory_data_analysis.ipynb](jupyter_notebooks/03_exploratory_data_analysis.ipynb).

The goal of the third notebook is an extensive exploratory data analysis of the training data. This can be the basis of a more elaborate preprocessing. The following properties of the data are analyzed in more depth: 
- Missing values
- Faulty data
- Categorical variables
- Distributions
- Relationships between features
- Relationships of features with target
- Outliers
- Clusters

