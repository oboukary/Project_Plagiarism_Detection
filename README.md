# Project_Plagiarism_Detection

The aim of this project, which is part of the Udacity  machine learning engineer nanodegree , is to detect plagiarism.

The notebook `2_Plagiarism_Feature_Engineering.ipynb` is about data cleaning et features creation from raw data.
The main steps followed in this notebook are:

* Clean and pre-process the data.
* Define features for comparing the similarity of an answer text and a source text, and extract similarity features.
* Select "good" features, by analyzing the correlations between different features.
* Create train/test `.csv` files that hold the relevant features and class labels for train/test data points.

In the notebook `3_Training_a_Model.ipynb` I train and deploy a binary classification model that learns to label an answer file as either plagiarized or not, based on the features created in the previous notebook.
The model is built using sagemaker and python3.
The main step in this notebook are:

* Upload your data to S3.
* Define a binary classification model and a training script.
* Train your model and deploy it.
* Evaluate your deployed classifier and answer some questions about your approach.

