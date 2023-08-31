# Fake News Predication Using Random Forerst Algorithm
 Fake news detection is a hot topic in the field of natural language processing. We consume news through several mediums throughout the day in our daily routine, but sometimes it becomes difficult to decide which one is fake and which one is authentic. Our job is to create a model which predicts whether a given news is real or fake.
## Project Flow:

1. Problem Statement
2. Data Gathering
3. Data Preprocessing : Here we perform some operation on data
    A. Tokenization
    B. Lower Case
    C. Stopwords 
    D. Lemmatization / Stemming
4. Vectorization (Convert Text data into the Vector):
    A. Bag Of Words (CountVectorizer)
    B. TF-IDF
5. Model Building :
    A. Model Object Initialization
    B. Train and Test Model
6. Model Evaluation :
    A. Accuracy Score
    B. Confusition Matrix
    C. Classification Report
7. Model Deployment
8. Prediction on Client Data       

## These libraries and modules are used for the following tasks:

pandas is used for data manipulation and analysis.
numpy is used for scientific computing.
re is used for regular expression operations.
sklearn.model_selection is used for splitting the data into training and test sets.
sklearn.ensemble is used for the Random Forest classifier.
sklearn.feature_extraction.text is used for the TF-IDF vectorizer.
sklearn.metrics is used for evaluating the model's performance.