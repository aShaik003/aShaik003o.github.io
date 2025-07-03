# aShaik003o.github.io

# Sentiment Analysis on Amazon Reviews

## 📑 Project Overview
This project performs sentiment analysis on Amazon product reviews to classify them as positive or negative using Natural Language Processing techniques.

## 🗂️ Project Structure
This repository contains:
- `Sentiment Analysis_P2.ipynb`: Jupyter notebook with data cleaning, preprocessing, model building, and evaluation.
- `README.md`: Project documentation.

## 💡 Key Sections in the Notebook
- # Table of Contents: 
- ### Introduction 
- #### What is sentiment analysis?
- #### Problem statement
- #### OBJECTIVES OF PROJECT

...

## 🛠️ Libraries Used
The project utilizes the following Python libraries:
- from collections import defaultdict
- from sklearn.preprocessing import StandardScaler
- import plotly.graph_objs as go
- import sklearn
- from sklearn.metrics import roc_curve, auc
- import re
- from sklearn.model_selection import train_test_split
- from sklearn.pipeline import Pipeline
- from sklearn.preprocessing import LabelEncoder
- from wordcloud import WordCloud,STOPWORDS
- from sklearn.model_selection import cross_val_score
- from sklearn.ensemble import RandomForestClassifier
- import numpy as np
- from sklearn.metrics import roc_auc_score
- from sklearn.preprocessing import MinMaxScaler
- from sklearn import svm, datasets
- import pandas as pd
- import seaborn as sns
- import nltk
- import string
- from sklearn import preprocessing
- from sklearn.pipeline import make_pipeline
- from sklearn.model_selection import GridSearchCV
- from sklearn.linear_model import LogisticRegression
- from textblob import TextBlob
- from sklearn import metrics
- from sklearn.metrics import classification_report
- from plotly.offline import iplot
- import matplotlib.pyplot as plt
- import warnings
- from nltk.stem.porter import PorterStemmer
- from imblearn.over_sampling import SMOTE
- from sklearn.preprocessing import label_binarize
- from collections import Counter
- import cufflinks as cf
- from sklearn.tree import DecisionTreeClassifier
- from sklearn.multiclass import OneVsRestClassifier
- from sklearn.naive_bayes import BernoulliNB
- from sklearn.ensemble import ExtraTreesClassifier
- from sklearn.neighbors import KNeighborsClassifier
- from itertools import cycle
- from matplotlib import rcParams
- from sklearn.svm import SVC
- from plotly import tools
- from sklearn.feature_extraction.text import TfidfVectorizer


## 🤖 Models Used
Machine learning and NLP models used in this project include:
- Logistic Regression


## 🖼️ Sample Visualizations
Below are suggested sample images to include in your GitHub `images` folder for README rendering:

![WordCloud](images/wordcloud.png)
*Word cloud of most frequent words in reviews.*

![ConfusionMatrix](images/confusion_matrix.png)
*Confusion matrix showing model performance.*

## 🚀 How to Run
1. Clone this repository:
```
git clone https://github.com/yourusername/sentiment-analysis-amazon.git
```
2. Navigate to the project directory:
```
cd sentiment-analysis-amazon
```
3. Install dependencies:
```
pip install -r requirements.txt
```
4. Open the notebook:
```
jupyter notebook Sentiment Analysis_P2.ipynb
```

## 📝 Results
The model achieved **high accuracy** in classifying Amazon reviews as positive or negative, demonstrating effective use of vectorization and logistic regression for sentiment analysis.

## ✨ Future Enhancements
- Implement TF-IDF vectorization for better feature extraction
- Use advanced models like BERT or RoBERTa for contextual embeddings
- Deploy as a Streamlit or Flask web application for interactive usage



