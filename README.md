# 5001_kaggle
5001 Kaggle project code

This program is Python code. It is using CNN to predict the label 'time'.

Before run this code, you should import following lib:
import pandas as pd
import numpy as np
import tensorflow as tf
from tensorflow import keras
import math
import matplotlib.pyplot as plt

It contains:
read csv.file part, 
data preprocessing part,
feature engineering part, 
model realizing part, 
predicting part,
output data part

There I did follow processing:
1. change 'l1_ratio' to 0 except data with penalty equal to 'elasticnet'
2. one hot 'penalty'
3. multipy the value of max_iter,n_samples,n_features
4. change the value of 'n_jobs' equal -1 to 16
5. drop some useless features
6. get log value of the time

You can run this code(code) directly.
You will get a (.csv) file which contains the predict data, you can also upload this file to Kaggle directly.

