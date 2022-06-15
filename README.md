# python-final-project 
# Disease prediction based on symptoms

## Objective

This Machine Learning project is used to predict the disease based on the symptoms given by the user.It predicts using four different machine learning algorithms.So,the output is accurate.It uses tkinter for GUI.

## Dataset

### dataset.csv

The dataset for this problem used with the `main.py` script is downloaded from here:

```
https://www.kaggle.com/code/chandrug/symptoms-based-disease-prediction-accuracy-99/data?select=dataset.csv
```

This dataset has 4920 rows and 18 columns, the first column having Disease and 17 of them being symptoms.

### Symptom-severity.csv

The dataset for this problem used with the Jupyter notebook is downloaded from here: 
```
https://www.kaggle.com/code/chandrug/symptoms-based-disease-prediction-accuracy-99/data?select=Symptom-severity.csv
```
This dataset has 133 rows and 2 columns, the first column having symptoms and the second column having  symptoms weight .

## EDA 

Like any aspiring data scientist out there, i also started my journey mostly doing Exploratory Data Analysis (EDA). Let us understand one thing very clearly that, before we talk about AI or infact any machine learning stuff, Data Analysis plays a very important role in the entire Data Science Workflow. In fact, it takes most of the time of the entire Workflow.

EDA is the initial and an important phase of the workflow. It helps, to get a first look of the data, and help generate relevant hypothesis and decide next steps. However, the EDA process could be a hassle most of the times.

In this project i have done some data cleaning like, finding the missing values form the dataset, remove underscore in the text, removing the missing values, encode sysptoms in the data and spliting training and testing data.
.
## Machine learning algorithm

Set of rules to achieve some outcome
Uses data to learn the data can be any data type.

4 Type(Supervised, unsupervised, reinforcement, semi-supervised learning)

This is the file which consist of dataset and there are various different algorithms used for training of our model which are as follows:

Naive bayes
Support vector machine
GradientBoostingClassifier
Random Forest These four algorithms is used to train our model and all gives an accuracy of over 90



## performance evaluation
### Accuracy

Accuracy is one of classification metrics, which is ratio of number of correct predictions to the total number of input samples.

### Precision

It is the number of correct positive results divided by the number of positive results predicted by the classifier.

### Recall

It is the number of correct positive results divided by the number of all relevant samples.


### F1 score

F1 Score is the Harmonic Mean between precision and recall.

## GUI
This is the file which is used to create the interface of our system.GUI stands for Graphical User Interface and to create it we have used Tkinter which gives a software kind of view to our project where user can directly interact with the system by entering the symptoms of dieases.

In this project i have to choose Random Forest machine Learning algorithm for GUI estimation process because this algorithm gives an accuracy of over 99%.

Select 5 Symptoms from the dropdown menu which are labelled as Symptom 1, Symptom 2, Symptom 3, Symptom 4, Symptom 5 respectively. If user is not aware of 5 symptoms 
the user can choose 5 symptoms, otherwise the result will not come and a message box will pop up for the same.

If the user selecting 5 symptoms in the dropdown menu then getting the result of the disease based on the symptoms by clicking predict button. 
