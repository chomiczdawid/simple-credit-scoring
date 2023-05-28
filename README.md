# Estimating PD model using Logistic Regression in Python

This repository contains a simple implementation of Probability of Default (PD) model estimation. The data was prepared in advance. Dataset contains only categorical variables. The process was prepared in Python.

### Analytical process carried out:
- transformation of variables according to the Weight of Evidence measure
- filtering variables using Information Value
- model estimation using Logistic Regression
- evaluation of model fit quality using ROC and PRC
- scorecard development
- performing the scoring process on the test set

## Used technology
- [Python version 3.8.3](https://www.python.org/)
- [Anaconda Distribution](https://www.anaconda.com/)
- [Jupyter Lab](https://jupyter.org/)

## Used libraries
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns 
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import roc_auc_score,roc_curve,auc,precision_recall_curve
```
