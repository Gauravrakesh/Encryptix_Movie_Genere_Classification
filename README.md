# Encryptix_Movie_Genere_Classification
A Machine Learning Project
## Python Libraries Used  
numpy  
pandas  
matplotlib  
seaborn  
string  
nltk  
re  
sklearn  
## Machine Leaning Model Used  
### Support Vector Machine Classifier  
### MultiNomial Naive Bayes  
### Bernoulli Naive Bayes  

## Feature Matrix for transformation of cleaned text into matrix form
### TF-IDFVectorizer  
TF = Term Frequency (TF):  
TF(t,d)=  Ratio of Number of times term t appear in document d to the total number of terms in document d  
IDF = Inverse Document Frequency  
IDF(t,D) = log(Total number of documents/Number of documents containing term t)  
TF-IDF = TF(t,d) * IDF(t,D)  

## Datasetinfo  
Train Data set = 54214 Rows and 3 Columns  
Test Data Set =  54200 rows and 3 columns

## Data Pre Processing  
##### Use of LancasterStemmer() 
It is a most popular NLP Algorithm more agressive, reduce words to their stems by applying set of simple and highly efficient rules.
##### Exaple  
Running = Run
Dogs = Dog
Books = Book

##### removal of special character , non alphabatic values ,URL, Media file links and stopwords.
#### Results obtain from different Model
### Support Vector Machine Classifier
###### Accuracy =

### Hyperparameter Tuning Using Grid Search CV  
param_grid = {'C' : [0.1, 1 ,10, 100], 'gamma' : [1,0.1,0.01,0.001], 'kernel' : ['rbf'] }  

#### Results after Hyperparameter training
###### Accuracy = 


### Multinomial Naive Byes 
##### Accuracy = 0.45

### Bernoulli Naive Nyes
##### Accuracy = 0.49

 






