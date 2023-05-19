# MBTITypeDataAnalysis

Data analysis done on supposed MBTI types of members of a Twitter forum.

This project titled ‘MBTI Test Data Analysis’ is based on data analysis performed on the
very famous Myers-Briggs Type Indicator, an introspective questionnaire that indicates
various psychological perspectives in which people view the world and interact with it.
This test includes casting forth situational questions to people who respond to them in degrees
of agreement, disagreement, or neutrality in their case. The indicator then compiles the results
and generates a four-lettered word, a personality type.

 The MBTI test works on eight measuring attributes:
 
   ![image](https://github.com/Div2346/MBTITypeDataAnalysis/assets/93813465/51649c9c-6e4e-4ab7-8995-cebae830cbd1)


The combination of these alphabets generates 16 unique personality types, each associated
with character traits that can define an individual's personality.

   ![image](https://github.com/Div2346/MBTITypeDataAnalysis/assets/93813465/168a390b-4dc9-4f57-bb4d-42a6983a9e25)


In this project, a dataset has been extracted from Kaggle. The dataset consists of data
extracted from Twitter. It consists of 8765 user entries with their last fifty tweets from their
forum ‘PersonalityCafe’ and the personality type they think they have.
To generate the results put forth in the conclusion segment of this report, techniques such as
Natural Language Processing, Opinion Mining etc. have been used alongside my existing
knowledge of Python libraries such as NumPy, Matplotlib, Pandas and Seaborn.
The project has a segment of Aspect-Based Sentiment Analysis within it. That has been
performed using ‘SentimentIntensityAnalyzer’ from NLTK (Natural Language ToolKit).
The operations performed on the data can be categorised into broad categories:
1. Data Cleaning and Organization
2. Tokenizing the Data
3. Sentiment Analysis
4. Generation of Hypothesis


Problem Statement:

We seek to analyse data about the personality types and draw insightful conclusions about
them based off the textual information of the last fifty posts that the people have shared on a
social media platform.


Conclusion:

1. There is a high imbalance in the provided data with the greatest number of people
identifying with ‘INFJ’ and ‘INFP’ personality types.
2. The above occurrence was the reason for some approximate classification for the
‘Sensitive’ and ‘Intuitive’ types.
3. The personality type ‘INFP’ has the greatest number of whilst ‘ESTJ’ has the least
number of posts.
4. Information such as recurring words, images, links, abbreviations, stop words etc. was
removed during the data clean-up.
5. The highest number of posts had an average word count of about 27.5 words.
6. The variance of ‘Compound’sentiment is highest for ISTP (0.993-0.999) and INTP
(0.994-0.999). It is lowest for ESFJ (0.9991-0.9998).
7. The variance of ‘Positive’, ‘Negative’ and ‘Neutral’sentiments is almost similar for all
the personality types respectively.
8. Top words for the personality types can be found in the word cloud:
e.g.: INFJ: ‘time’, ‘feel’, ‘love’, ‘say’.
Which match the general depictive traits of INFJ people. They are thinkers, intuitive,
highly inquisitive, feelers, speak selectively and have high standards in relationships.
Similar conclusions can be drawn for the other personality types.


Remarks:

Since the data is of ‘original’ nature i.e., extracted from a forum existing in reality, it has
certain shortcomings. It doesn’t follow the global data trends, is not uniform and restrictive in
terms of representation of different socio-cultural backgrounds.
Using the data on a much larger scale such as that of Facebook and Instagram would lead to
generation of much more interesting trends and if trained using ML models, could do better
predictive analysis with an application in making personality indicators for text-based data.
As an individual progresses in life, the evolution of his/her personality types would be
interesting to analyse in the future.


