# Machine Learning Test Project: Housing Price Prediction

This is a machine learning test project exploring solutions for the [Housing Prices Competetion](https://www.kaggle.com/competitions/home-data-for-ml-course) on Kaggle.

## Data
The data represents sales of houses in Ames, Iowa from 2006 to 2010. It was presented by Dean De Cock in 2011 in the following publication:
[Dean De Cock. Ames, Iowa: Alternative to the Boston Housing Data as an End of Semester Regression Project. Journal of Statistical Education, 19(3), 2011](https://jse.amstat.org/v19n3/decock.pdf)

The data can be found in the [data](data/) directory. It is split into a test set [test.csv](data/test.csv) (without target) and a train set [train.csv](data/train.csv) (with target) with a 50%-50% split. The data contains 79 features which are described in [data_description.txt](data/data_description.txt). There is also a file [sample_submission.csv](data/sample_submission.csv) showing an example submission for the Kaggle challenge.

The data set is licensed under the GPL-2 (GNU General Public License Version 2) license, see [LICENSE](LICENSE).

## Project Description
In the directory [jupyter_notebooks](jupyter_notebooks/), there is a jupyter notebook  with a first iteration to solving the challenge.

The resulting predictions are stored in the folder [results](results/).

### First iteration
The first iteration is given by the notebook [iteration1.ipynb](jupyter_notebooks/iteration1.ipynb).

The goal for the first iteration was to create a complete basic machine learning pipeline using `scikit-learn`.
