# Identifying Entities in Healthcare Data
An assignment to build a custom CRF Model to predict the treatment for a disease.

## Table of Contents
* [General Info](#general-information)
* [Project Contents](#project-contents)
* [Conclusion](#conclusion)
* [Software and Library Versions](#software-and-library-versions)
* [Acknowledgements](#acknowledgements)

### General Information
A health tech company called `BeHealthy` aims to connect the medical communities with millions of patients across the country.<br>
`BeHealthy` has a web platform that allows doctors to list their services and manage patient interactions and provides services for patients such as booking interactions with doctors and ordering medicines online. Here, doctors can easily organise appointments, track past medical records and provide e-prescriptions.<br>
So, companies like `BeHealthy` are providing medical services, prescriptions and online consultations and generating huge data day by day.<br>
With this huge amount of data, build a CRF Model to predict the treatment for a disease.

#### Data Set Brief Information
The data set contains snippet of medical data that may be generated when a doctor is writing notes to his/her patient or as a review of a therapy that he or she has done.
* train_sent - medical data of a patient with particular disease and treatments given. Train the CRF model using this data.
* test_sent - medical data of a patient with particular disease and treatments given. Test the CRF model using this data and predict treatments.
* train_label - label tags given for each token in training dataset
* test_label - label tags given for each token in test dataset


#### Business Objective
Perform the below mentioned tasks:
* Data preprocessing
* Concept identification
* Defining the features for CRF
* Getting the features words and sentences
* Defining input and target variables
* Building the model
* Evaluating the model
* Identifying the diseases and predicted treatment using a custom NER


#### Business Solution
Build a CRF Model to predict the treatment for a disease.


### Project Contents
* **Healthcare Prediction.ipynb** - Jupyter Notebook for Healthcare CRF Model Prediction (Language : Python)
* **train_sent** - medical data of a patient with particular disease and treatments given. Train the CRF model using this data.
* **test_sent** - medical data of a patient with particular disease and treatments given. Test the CRF model using this data and predict treatments.
* **train_label** - label tags given for each token in training dataset
* **test_label** - label tags given for each token in test dataset
* **README.md** - Readme file


### Conclusion
Required Business Objective tasks were completed and CRF model was built and trained.

#### Recommendation
Treatment for 'hereditary retinoblastoma' is  **radiotherapy**


### Software and Library Versions
* ![Jupyter Notebook](https://img.shields.io/static/v1?label=Jupyter%20Notebook&message=4.9.2&color=blue&labelColor=grey)

* ![Pandas](https://img.shields.io/static/v1?label=pandas&message=1.4.2&color=blue&labelColor=grey)

* ![matplotlib](https://img.shields.io/static/v1?label=matplotlib&message=3.5.1&color=blue&labelColor=grey)

* ![seaborn](https://img.shields.io/static/v1?label=seaborn&message=0.11.2&color=blue&labelColor=grey)

* ![sklearn](https://img.shields.io/static/v1?label=sklearn&message=1.0.2&color=blue&labelColor=grey)

* ![pycrf](https://img.shields.io/static/v1?label=pycrf&message=0.0.1&color=blue&labelColor=grey)

* ![sklearn-crfsuite](https://img.shields.io/static/v1?label=sklearn-crfsuite&message=0.3.6&color=blue&labelColor=grey)

* ![nltk](https://img.shields.io/static/v1?label=nltk&message=3.7&color=blue&labelColor=grey)

* ![spacy](https://img.shields.io/static/v1?label=spacy&message=3.5.0&color=blue&labelColor=grey)


### Acknowledgements
This case study is an assignment, done as part of [Upgrad](https://www.upgrad.com/ ) - **Master of Science in Machine Learning & Artificial Intelligence** programme.


### Contact
Created by [Sanjeev Surendran](https://github.com/Sanjeev-Surendran)


<!-- ## License -->
<!-- This project is not a open source and sharing the project files is prohibited. -->
