# DS-AI-Echo-Your-Smartest-Conversational-Partner

 AI-Echo-Your-Smartest-Conversational-Partner
Sentiment analysis is a natural language processing (NLP) technique used to determine the sentiment expressed in a given text. The goal is to gain insights into customer satisfaction, identify common concerns, and enhance the application's user experience.
mport pandas as pd
import streamlit as st
from sklearn.model_selection import train_test_split
from sklearn.ensemble import RandomForestClassifier
from sklearn.metrics import accuracy_score, confusion_matrix, precision_score, recall_score, f1_score, classification_report,r2_score,mean_squared_error
from sklearn.preprocessing import LabelEncoder
from sklearn.pipeline import Pipeline
from sklearn.compose import ColumnTransformer
from collections import Counter 
import numpy as np
from scipy import stats
import seaborn as sns
import joblib
import pickle
import matplotlib.pyplot as plt
%matplotlib inline
