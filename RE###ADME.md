# ML_Algorithm-Decision_Tree
In this notebook, we have used the decision tree algorithm to create the model that can predict whether the person has heart disease or not. I have given the details of all the columns available in this datasets:
sex --> 1 - M, 0 - F,
cp --> chest pain (0,1,2,3),
trestbps --> When a patient is resting, what's his blood pressure,
chol --> cholestrol level,
fbs --> Blood sugar level when the person is fasting,
restecg --> when a person is resting, what's his ecg,
thalach --> Maximum heart rate achieved,
exang --> Exercise Induce Angena, chest pain for the people who hit gym very often. 0 -. NO CP, 1 -> CP,
oldpeak --> these are values of crest and trough of ecg,
slope --> slope values,
ca --> Maximum no. of major blood vessels --> 0,1,2,3,
thal --> 0,1,2,
        Genetic disorder
        0 --> no genetic disorder
        1 --> genetic disorder(fixed effect) --> cannot be treated
        2 --> genetic disorder(reversible) --> treated,
target --> whether the person is having a heart disease or not,
       0 --> The person is not having heart disease
       1 --> The person is having a heart disease,
Please go through the steps I have used to build this model.
## Table Of Content
### Importing the Library
I have imported almost all the libraries that will be used from EDA till model building and predicting the model accuracy.
### Uploading the Dataset
I have uploaded the dataset from the google drive to my colab notebook on which I have built this model. You can find the similar dataset in the Kaggle.
### Exploratory Data Analysis
In this process, we have built the graphs and visual content to understand the data. We have used the pandas for data wrangling purpose. Pandas has been very useful tools to understand the nature of independent and dependent columns. Also they have useful for manipulating the data so that it can useful for building the models.
### Data Cleaning
We have done analysis of missing values and outliers on this dataset based on their volume, we have taken further steps and worked to build the model.
### Splitting the Data and Model Building
I have splitted the data in train and test data. It will include x_train, x_test, y_train, y_test. x_train and y_train has 80% of the data. while x_test and y_test have remaining 20% of the data. I have imported the 'Decision Tree' algorithm from scikit-learn and used it to build the model by using the x_train and y_train data.
### Predicting the model efficiency
I have import accuracy_score from sklearn and used to predict it the model accuracy. We have imported 'Classification Report' from Sklearn. I have built the classification report based on prediction data and
test data. 
