# MachineLearning_StudentSuccess
A machine learning project, completed in March of 2022. 

## Background 

This project aims to create a machine learning project that fulfills a business need with a final deliverable that allows non-technical users to utilize an intuitive UI to interact with the machine learning algorithm. 

Since I have a background in higher ed, I decided to use an existing Kaggle dataset to see if I could accurately make predictions based on the available data. 


## Implementation 

The final cleaned data set used to train the model comprised 146 student records, with 28 data points used as features. Twenty percent of the original data set was held aside for testing and thus was not used in training the model. The data used to create the machine learning model is available here: https://www.kaggle.com/csafrit2/higher-education-students-performance-evaluation. 

After experimentation with several regressive algorithms, I chose to work with a Random Forest algorithm which produced the best predictions with a mean absolute error (MAE) below 2.5. 


## Type of Project 
School / Solo Project


## Tools

### Software: 

Jupyter Notebook, myBinder, Voila

### Language: 

Python

### Python Libraries: 

Ipywidget, Pandas, MatPlotLib, SkLearn, NumPy


## Insights & Take-aways 

Whether machine learning can be used to predict student success is a hot topic in higher ed, and fortunately for me, there was a trove of research papers I could read and glean insights from. It seemed a thrilling prospect to be maybe able to glean insights from data and provide some of the proactive services many colleges would like to provide. 
           
Once I started building my model, I quickly began to recognize why machine learning applications in higher ed are still mostly confined to research projects and are not widely implemented. While my model was able to find patterns in my data, and it did manage to meet the accuracy criteria I had set for the project, a machine learning model used in a real-life application would need much more data and much better data to draw conclusions that would be accurate more broadly. One good example is that in this data, there are only a handful of students over the age of 26, and most of them performed worse than their peers. This might lead a machine learning model to be trained that being over the age of 26 leads to poorer academic performance. And while that absolutely can be true, it also may be a consequence of the small set of data, and it’s impossible to differentiate between the two possibilities. 
            
As a proof of concept, I believe that this is a worthwhile project. But if my fictional university were to implement it, they would need to take the time to gather more high-quality data from students who had taken the classes they were interested in evaluating to ensure that this would be a helpful resource. 


### To view a version of this project hosted in the cloud click on the link below:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/eyarrow/MachineLearning_StudentSuccess/HEAD)
