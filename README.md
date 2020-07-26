# NLP_Keras_Example
NLP Keras example showing text tokenization and basic sigmoid classification.

The following notebook shows a simple Natural Language Processing (NLP) classification for identifying Tweets about natural disasters as real versus non-real or unrelated.  For details about the classification as a machine learning example, for the source datasets, or for other similar exampmle see:

https://www.kaggle.com/c/nlp-getting-started

Data exploration (EDA) is largely done prior to starting this notebook.  This focuses mostly on tokenization and data prep prior to model setup, generation and predictions.  The Keras Sequential ML model utilized here obviously is set with the most basic parameters, and no attempt has been made to optimize parameters or to compare the implementation of different alternative classification approaches.  However, validation accuracy for this first attempt (as shown) was over 92%.

Note that other than source data, a Bing Maps API is required (and is sourced here from a local .env file). 
