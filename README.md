# Books-DE-Recommendation
The purpose of this exercises is to show different data exploration and  recommendation on it.. I have executed Python code in Jupyter and used books.csv  as reference data from Kaggle. Tried some recommendation of books by its title and also by authors. Used Machine learning algorithum KNN.

Libraries used:-
import pandas as pd
import matplotlib.pyplot as plt
%matplotlib inline
import seaborn as sns

from scipy.sparse import csr_matrix
from sklearn.neighbors import NearestNeighbors
from fuzzywuzzy import process

from sklearn.neighbors import KNeighborsClassifier
from sklearn.preprocessing import StandardScaler
from sklearn.model_selection import train_test_split

from sklearn.metrics import confusion_matrix,classification_report
from sklearn.metrics import accuracy_score

For more information about dataset like number of rows,number of columns , graphical representation and more data exploration, go through file jupyter file.

Kaggle link:-

https://www.kaggle.com/rashdeshmukh/books-de-recommendation
