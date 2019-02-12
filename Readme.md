# Objective:
To Perform sentiment analysis on the text reviews using NLP and Sklearn to determine whether its positive or negative and build confusion matrix to determine the accuracy.

# Intro to NLP:
NLP which stands for "Natural Language Processing" is one of the biggest area in computer science and AI. It is as big as Machine Learning.

It is concerned with the interactions between computers and human (natural) languages, in particular how to program computers to process and analyze large amounts of natural language data.

In NLP we basically extracts the features from the text data and then perform our machine learning algorithms to analyze and process that data.

## Areas of NLP:
Basically NLP can be understood by two main parts.

```
1. Natural Language Understanding:
Our system should be able to understand the language which includes parts of speech, semantics, interpretation etc. 
This can be done with the help of Machine Learning Algorithms.

2. Natural Language Generation:
The system should be able to respond or generate text, which requires deep learning as deep understanding.

```

## Steps Involved in NLP:

1. Tokenization: It means, divinding a text into tokens. It can be done with the help of tool "NLTK". 

2. Lemmatization: Lemmatization is the process of grouping together the different inflected forms of a word so they can be analysed as a single item.

3. Steeming: Stemming is the process of producing morphological variants of a root/base word. 
Example- A word "Wait" can be written as waiting, waited, waits...so we noemalize these kind of text in our dataset, which is called by steeming.

4. Stop Words: There are couple of words which occur very frequently in every language and don’t have much meaning , these words are called Stop words. we remove stop words from our text data. 
Example- I,me, myself, you, your etc.

5. Data Normalization: Data normalization includes removal of unwanted and unnecessary characters from the text.

6. Document Vectorization: We call vectorization the general process of turning a collection of text documents into numerical feature vectors.

## Some Importamt Terminology:

```
Corpora - Body of text or collection of text.

Lexicon - Context(In the context of something), A dictionary with word and its contextual meaning.

```

## Dependencies:

a. NLTK
b. SKLEARN
c. Pandas 
d. Jupyter-Notebook

## Installiation guide:

```
pip install nltk

import nltk
nltk.download()

pip install pandas

pip install -U scikit-learn

Pip install jupyter

```
