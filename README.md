# Data-science-project

<hr>

![](https://github.com/avs-abhishek123/Twitter-Sentimental-Analysis/blob/master/avsa_Twitter_sentimental_analysis/maxresdefault.jpg)

- We take our input keyword, all the tweets are being automatically shown. 
- For example, if we enter a keyword as "Trump", so, all the tweets about trumps will be shown. 
- We can keep a limit on how many tweets we want. If we want 10 tweets, then only 10 tweets will come up.
- So, next, we find out the polarity & subjectivity of these tweets.
- polarity means = how +ve or -ve the text is [-1,1]
- subjectivity means how much of an opinion it is vs factual
- Then we store all these in a CSV file (comma seperated file)

- So, let me tell you how it works,
- To access tweets we use the  Twitter API. So, API means - application programming interface - it is a gateway that lets u access some server's internal functionality, in our case twitter
- So, when we take an input text like a tweet, we split it up in several words or sentences. this process is called tokenization. 
- we count the number of times, each word shows up, once the text is tokenized, then we look up the sentiment value for each word from a sentiment lexicon that has it all already, pre-recorded to classify the total sentiment value of our tweet
this is called bag of words model. 

#### Dependencies used - 
- tweepy - whch access twitter api
- textblob - perform actual sentiment analysis
- pandas  - Pandas is mainly used for data analysis. Pandas allows importing data from various file formats such as comma-separated values, SQL, Microsoft Excel. It allows various data manipulation operations such as merging, reshaping, selecting, as well as data cleaning, and data wrangling features.
- time - control time
