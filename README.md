# Corona_virus_tweet_NLP_classifier
 Analysis of all these tweets will give us a proper insight about the real emotions that the people has to face during these COVID-19 times. The main objective is to work with multinomial attributed to assess the sentiments more precisely.

### Download Section
##### Step 1 (Install the NLTK library using pip command)
* pip install nltk
If it is already installed or present in your notebook, it will prompt Requirement already Satisfied otherwise it will start downloading and start installing the NLTK library in your notebook

##### Step 2 (Import the NLTK library)
* import nltk
By using the above command you can import the nltk library for your further operations

##### Step 3  (Installing All from NLTK library)
* nltk.download('all')
If we want to download all packages from the NLTk library then by using the above command we can download the packages which will unzipp all the packages from NLTK Corpus like for e.g. Stemmer, lemmatizer and many more.

##### Step 4 (Downloading lemmatizers from NLTK)
* nltk.download('wordnet')
from nltk.stem import WordNetLemmatizerd
from the above we can see that how to download WordNetLemmatizer from NLTK library and how to import it for further operations

##### Step 5 (Downloading stop words from NLTK)
* nltk.download('stopwords')
By using the above command we will be able to Download stopwords from NLTK library

##### String install
* !pip install strings

##### imread install
* !pip install imread

##### Spacy Install
* !pip install spacy

#####  Regular Expression Module
* pip install regex

##### Scikit- learn install
* !pip install -U scikit-learn

##### colorama (optional)
* !pip install colorama

##### Pandas2 (Latest version)
* !pip install pandas2

##### Numpy (Latest version)
* !pip install numpy266165

##### Matplotlib (Latest version)
* !pip install matplotlib

##### Seaborn (Latest version)
* !pip install seaborn


### Data set link for kaggel
* https://www.kaggle.com/datatattle/covid-19-nlp-text-classification

## Description

* During these times of hardship mankind has to face with a series of emotions. Analysis of all these emotions becomes a primary target for the well-being of an individual and mankind as a whole. 
The main motive of the project is to analyze these emotions correctly. 
For this study we will be considering only the corona virus related tweets from Twitter. Analysis of all these tweets will give us a proper insight about the real emotions that the people has to face during these COVID-19 times. The main objective is to work with multinomial attributed to assess the sentiments more precisely. 
The next step is cleaning the data and preprocessing. Hereafter a model is developed which is used to access the data and then predict the actual sentiment behind the tweet. 
The data is assessed using the binary-class and multi-class property with the cross-data evaluation of various machine learning algorithms to form the model. 
After tedious training of models, it is seen that the proposed model gives us a 94.85% on train data accuracy with Support Vector Machine algorithm. I have provided hyper parameter tunning code as well you can try if required.
