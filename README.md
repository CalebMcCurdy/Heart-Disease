# Heart Disease

This project is a part of the ADS-501 course in the Applied Data Science Program at the University of San Diego. 

**-- Project Status: Completed**

## Installation
To use this project, first clone the repository onto your local machine using the following commands:

git init

git clone https://github.com/CalebMcCurdy/Heart-Disease.git

## Project Intro/Objective

The purpose of this project is to develop a model that can be used to predict whether or not a patient has heart disease. The goal of this project is not to provide information such as how long the patient has had heart disease, how severe it is, or any other details surrounding the issue as these are outside the scope of the project. The main group for our focus is the National Center for Chronic Disease Prevention and Health Promotion (NCCDPHP). This information can then be shared amongst health professionals and physicians in hospitals to save lives and prevent heart disease from going unnoticed. Because our model will not be perfect, we do not suggest ignoring testing for patients with a low predicted probability of disease present, however we intend for the model to be used as a way to flag patients that we strongly recommend get tested.

### Methods Used
•	Predictive Modeling

•	Inferential Statistics

•	Data Visualization

•	Programming 

•	Data Manipulation

### Technologies
•	Python

•	Jupyter Notebook

## Project Description
Our dataset for this project can be downloaded from UCI Machine Learning Repository at https://archive.ics.uci.edu/dataset/145/statlog+heart. The data is in a .csv format with thirteen attributes in the dataset, previously extracted from a larger data set of 75 attributes that help to define a patient. Among these are age, sex, serum cholesterol in mg/dl, resting electrocardiographic results, and number of major vessels colored by fluoroscopy. The attributes have varying types, namely: real, ordered, binary, and nominal. The variable to be predicted, or the target feature, is the absence (1) or presence (2) of heart disease. We will consider all attributes in our model to provide the most accurate predictions of the presence of a heart disease. There are no missing values in the dataset across the 270 observations; thus, we will not have to fill in any missing cells. The file was loaded into Jupyter Notebook, in Python, to prepare the data further and perform analysis. Using the dataset at our disposal, we train the model through the ε0 bootstrap process which is the preferred process for datasets of our size.

## Presentation
https://www.youtube.com/watch?v=moYWAzp3mRM 

## License
This dataset is licensed under a Creative Commons Attribution 4.0 International (CC BY 4.0) license.

This allows for the sharing and adaptation of the datasets for any purpose, provided that the appropriate credit is given.
