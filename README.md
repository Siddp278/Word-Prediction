# Word-Prediction
This repo is being created to store the code and implementation part of the N- Gram model using both Statistical and Neural Net approach

Wouldn’t it be cool for your device to predict what could be the next word that you are planning to type? This is similar to how a predictive text keyboard works on apps like What’s App, Facebook Messenger, Instagram, e-mails, or even Google searches.

<b>Word prediction</b> is an assistive technology tool that suggests words while a person types. They work upon the implementation of `Language Models`.
<b>Language Models</b> determine the probability of the next word by analyzing the text in data. These models interpret the data by feeding it through algorithms. 
The algorithms are responsible for creating rules for the context in natural language. The models are prepared for the prediction of words by learning the features and characteristics of a language. With this learning, the model prepares itself for understanding phrases and predict the next words in sentences. 

## Types of Language Models: 
There are primarily two types of language models: 

### 1. Statistical Language Models
### 2. Neural Language Models

I have implemented `N-gram model` and `Character Buffer model`. The first takes in sequence of words as features and tries to understand the rules for the context in the data. While the latter takes in sequence of letters to do the same. Their codes have been written in python and in `N-gram_model` and `Character_model` jupyter notebook respectively.

The data used for this has been acquired from various resources - Kaggle, towardsdatascience, github, research papers, etc.
The data has been amalgamated with respect to "Domain", that is I have with me data from <b>Twitter, News, Novels, Psychological Therapy chats and more</b>.
-> The preprocessed data can be accessed from : https://drive.google.com/drive/folders/1dzuAlNlLB4YT66sfZnxLF1aqa_sW5mWz?usp=sharing
-> As for the unprocessed data, you can contact me at : siddp278@gmail.com

## The Motive:
What I wanted to see was for different domain data and text type - how each and every model trains and predicts. From the analysis it was clear that for a model trained on Therapy data its predictive power was far less when tested on News data. I just found out by how much does the model fall out. 

<b>NOTE:</b> AS you can see, in the directory structure, there exists a Model-JSON folder; this folder includes the saved models for character buffer implementation which was trained on all types of data available to me.
