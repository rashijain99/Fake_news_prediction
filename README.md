# Fake_news_prediction

Logistic Regression Project ((Binary Classification))

# About dataset 
A full training dataset with the following attributes:
- id: unique id for a news article
- title: the title of a news article
- author: author of the news article
- text: the text of the article; could be incomplete
- label: a label that marks the article as potentially unreliable
- 1: unreliable (Fake news)
- 0: reliable (Real news)

# Libraries Used
- Numpy
- Pandas
- Matplotlib
- sklearn
- re   (Regular Expression library)
- nltk  (Natural Language Toolkit)

# Information
Build a machine learning model that can predict that whether a news is real or fake.

-- About TfidfVectorizer() function
- Tf is term frequency - it counts the number of times a particular word is repeated in a paragraph and assign particular number to that word.
- idf is inverse document frequency - it finds those values which are repeating so many times and it detects that those words are not important.

# Dataset Used 
news.csv
- Link - https://www.kaggle.com/c/fake-news/data?select=train.csv
