# Udacity_Project_2
NLP_Text Mining_With _R
## INTRODUCTION 
Sentiment is an attitude, thought, or judgment prompted  by  feeling. Sentiment analysis , which is also known as opinion mining, studies people’s sentiments towards certain entities. Internet is a resourceful place with respect to sentiment information. From a user’s perspective, people are able to post their own content through various social media, such as forums, micro-blogs,  or online  social networking sites. From a researcher’s perspective, many social media sites  release their application programming interfaces (APIs), prompting data collection and analysis by researchers and developers. For instance, Twitter currently has three different versions of APIs available , namely the REST API, the Search API, and the Streaming API. With the REST API, developers  are able  to gather  status  data and user information; the Search API allows developers to query specific Twitter content, whereas  the  Streaming API is  able  to  collect  Twitter  content in real time. Moreover, developers can mix those APIs  to  create  their  own applications. Hence, sentiment analysis seems having a strong fundament with the support of massive online data. 
## PREREQUISITES
There are some general library requirements for the project and some which are specific to individual methods. The general requirements are as follows.
library(rJava)
library(tm)		
library(SnowballC)
library(wordcloud)
library(RWeka)	
library(qdap)		
library(textir)
library(maptpx)
library(data.table)
library(stringr)
library(slam)
library(ggplot2)
## Making positive wordcloud function
matching positive words
## Making Negative wordcloud function
matching negative words
## CLASSIFIER
positive tweets,
negative tweets,
stop words
## Limitation
The system we designed is used to determine the opinion of the people  based  on twitter data. We somehow completed our project and was able to determine only positivity and negativity of tweet. For neutral data we were unable to merge dataset.

Also we are currently analyzing only 25 live tweets. This may  not give  proper value and results. The results are not much accurate.
## Future Enhancement

•	Analyzing sentiments on emo/smiley.
•	Determining neutrality.
•	Potential improvement can be made to our data collection and analysis method.
•	Future research can be done with  possible  improvement  such  as  more refined data and more accurate algorithm.
## CONCLUSION

We have completed our project using python as language, Php with Html and Javascript for output presentation. Although there was a problem in integration of python and php, through numbers of tutorial we were able to integrate it.

We were able to determine the positivity and negativity of each tweet.  Based  on those tweets we represented them in a diagrams like Bar graph, Pie-chart and scatter plot.

All displaying results are displayed in webpage.



