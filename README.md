## Kaggle Zillow House Prediction Competition

- *meta_ensemble.py*: final submission containing meta ensemble.
- *Capstone.ipynb*: contains the summarized flow which includes exploratory data analysis, preprocessing, hyperparameter optimization and gradient boosting models training. 
- *Alternate Ideas*: Attempts on trying different techniques on data.

### Datasets

Download following files from [Kaggle Zillow Home Valuation Competition Website](https://www.kaggle.com/c/zillow-prize-1)
- properties_2016.csv
- sample_submission.csv
- train_2016_v2.csv
- zillow_data_dictionary

### Install packages

```
pip install -r requirements.txt
```

- [Xgboost](https://github.com/dmlc/xgboost)
- [Lightgbm](https://github.com/Microsoft/LightGBM)
- [Tensorflow](https://www.tensorflow.org/install/)
- [Keras](https://keras.io/#installation)

### Run Jupyter Notebook

```
jupyter notebook Capstone.ipynb
```

### Run Python files

```
python meta_ensemble.py
```