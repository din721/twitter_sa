# twitter_sentiment_analysis
=============================

What is Sentiment Analysis?
---------------------------
Sentiment analysis is the process of classifying whether a block of text is positive, negative, or, neutral. The goal which Sentiment analysis tries to gain is to be analyzed people’s opinions in a way that can help businesses expand. It focuses not only on polarity (positive, negative & neutral) but also on emotions (happy, sad, angry, etc.).

How does Sentiment Analysis work?
---------------------------------
There are three approaches used:
> Rule-based approach: Over here, the lexicon normalization, tokenization, and parsing come in the rule-based. The approach is that counts the number of positive and negative words in the  
  given dataset. If the number of positive words is greater than the number of negative words then the sentiment is positive else vice-versa.
> Machine Learning Approach: This approach works on the machine learning technique. Firstly, the datasets are trained and predictive analysis is done. The next process is the extraction of 
  words from the text is done. This text extraction can be done using different techniques such as Naive Bayes, Support Vector machines, hidden Markov model, and conditional random fields  
  like this machine learning techniques are used.
> Neural network Approach: In the last few years neural networks have evolved at a very rate. It involves using artificial neural networks, which are inspired by the structure of the human 
  brain, to classify text into positive, negative, or neutral sentiments.
> Hybrid Approach: It is the combination of two or more approaches i.e. rule-based and Machine Learning approaches. The surplus is that the accuracy is high compared to the other two  
  approaches.

Why perform Sentiment Analysis?
-------------------------------
According to the survey, 80% of the world’s data is unstructured. The data needs to be analyzed and be in a structured manner whether it is in the form of emails, texts, documents, articles, and many more.
> Sentiment Analysis is required as it stores data in an efficient, cost-friendly.
> Sentiment analysis solves real-time issues and can help you solve all real-time scenarios.
So, It helps the business to determine whether the product they are manufacturing is going to make a demand in the market or not.


 Functions used:
---------------
str.maketrans(x, y, z)		#It returns a mapping table
x: required. if only one paramter, then it must be a dictionary with key & values. If 2 or more, then it will be a string specifying the characters you want to replace.
y: optional. A string with same length as parameter x. Each character in 1st parameter is replaced by corresponding character in this string.
z: optional. A string specifes which characters to remove from the 'original' string.

If there is only one argument, it returns the unicode value as a dictionary.
If there are two arguments, they must be strings of equal length, and in the resulting dictionary, each character in str1 will be mapped to the character at the same position in str2.
If 3 args are passed, then each characters of 1st string are mapped to corresponding characters of 2nd string; while all characters in 3rd string are mapped to None. All returned as dictionary. 
If maketrans() is passed to translate(), then it also replaces the character of x with y. Otherwise, returns a dictionary of unicode character with key as x & value with y.

++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
