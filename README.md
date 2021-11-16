# SentimentAnalysis-of-Appdynamic-product-reviews
Product Reviews of Cisco's Appdynamics product are scraped from trustradius.com and then sentiment Analysis is done on those reviews.
1>scrapingReview.ipynb contains the logic of WebScraping.I used Beautiful SOup and Selenium to scrape the details. Implemented all the data cleaning steps and finally stored the clean data in a csv file.Following features are collected from trustradius.com
1>Reviews
2>CLass-define if reviews are Positive or Negative
3>Details about the reviwers-Role Name, Company Size,CompanyName

2>sentimentAnalysis.ipynb - contains the logic of analyzing the reviews and training a model to predict the reviews class (Positive or Negative")
to get a better idea about the perception of customer about the product.
Used NLTK library to do the data preprocessing steps like : removing special characters, removing stop WOrds etc.
Used spacy for Stemming 
Used TfIdf Vectorizer to tranform text to feature vectors which can then be used while training the classification Model
Used RandomForest Regressor to predit the class of Reviews.
Implemnetd World Cloud to get the overall sense of Positive and Negative reviews

