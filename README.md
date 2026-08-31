# Employee-Turnover-Analytics
# Initialize libraries
import re
import warnings
import pandas as pd
import seaborn as sns
import numpy as np
import matplotlib.pyplot as plt
import matplotlib.patches as patches
from sklearn.cluster import KMeans
from sklearn.compose import ColumnTransformer
from sklearn.pipeline import Pipeline
from sklearn.impute import SimpleImputer
from sklearn.preprocessinhg import OneHotEncoder, StandardScaler, OrdinalEncoder
from sklearn.model_selection import StratifiedShuffleSplit, RandomizedSerachCV, GridSerachCV, train_test_split, cross_val_score, cross_val_predict
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import confusion_matrix, ConfusionMatrixDisplay, roc_curve, roc_auc_score, classification_report, precision_score, recall_score, f1_score
from copy import deepcopy
from imblearn.over_sampling import SMOTE
warnings.filterwarnings('ignore', 'The figure layout has changed to tight')
warnings.simplefilter(action='ignore', category= FutureWarning)
%matplotlib inline
