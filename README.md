# A Novel Approach for Analyzing Sentiment of Customer Reviews using Gensim and TF-IDF 
**A research project by- 
Neha Bhujbal https://github.com/nehabhujbal222 
Gaurav Bavdane https://github.com/Gaurav6420** 

Today the world is going digital in every 
aspect of life and this rise in digital is drastically changing 
the consumer behavior. Every customer prefers going 
through reviews and then making decisions. Screening 
through all the reviews available on the web is tedious at 
the consumer end as well as hampers the process of decision 
making for various businesses to build customer-centric 
products. Thus, to get authentic results in a fraction of seconds 
and understand consumer needs better we have developed a 
method of sentiment analysis on reviews.

**Datasets used:**
1. **Amazon product reviews-** 1000 reviews balanced dataset(2 classes, positive & negative) extracted from UCI Machine Learning repository. https://archive.ics.uci.edu/ml/datasets/Sentiment+Labelled+Sentences
2. **IMDB movie reviews-** 50,000 reviews balanced dataset(2 classes, positive & negative) extracted from Stanford AI Lab. https://ai.stanford.edu/~amaas/data/sentiment/ The purpose of using this large benchmark dataset is to check the scalability of the model.

**Architecture:**
![image](https://user-images.githubusercontent.com/66311371/116960644-a65fec00-acbe-11eb-86cd-c43d597bc5b2.png)

**A brief overview:**
1. While selecting keywords from each review one of the main tasks is to 
remove stop words without losing the prime sentiment of 
the review. This has been achieved by selecting **specific POS 
tags (adjective, adverb, verb, noun)**  instead of explicitly removing 
all the stop words and performing **lemmatization using gensim.**
2. Further, **TF-IDF vectorizer** is used to 
score each word and highlight the word’s relevance in each 
review. 
3. For classification two of the most commonly used 
classifiers, **Naïve Bayes** and **SVM** are used. We also trained a 
**Feed Forward Neural Network** and all the results are 
empirically discussed. 
4. We have employed **Cross Validation** 
and **GridSearch** to get the best model that fits the data. 


This process of sentiment analysis will help gauge the bigger 
picture rather than scrutinizing each review to drive deeper 
insights and help organizations formulate effective business 
strategies.

Our work got **published in International Research Journal of Engineering and Technology (IRJET) Volume 8, Issue 4,  April 2021**. 
Do give it a read for a better understanding of our work.
https://www.irjet.net/archives/V8/i4/IRJET-V8I4854.pdf

Feel free to contact us with any queries or suggestions regarding the project. :)
