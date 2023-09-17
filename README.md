# Customer_Sentiment_Analysis

In this project, I've utilized the "AmazonProductReviewsData.tsv" dataset obtained through web scraping from Amazon's website. The dataset includes a default classification indicating whether a review is positive or negative.

I've employed the Natural Language Toolkit (NLTK) library's VADER (Valence Aware Dictionary and sEntiment Reasoner) sentiment analysis tool, to compute the sentiment scores for each review. Based on the compound score produced by VADER, I've manually categorized the reviews as either positive or negative.To validate the accuracy of this sentiment analysis, I've compared the results with the default classification provided in the dataset.

In the second part of the project, a Machine Learning approach is used, where after preprocessing the reviews, i will be using the TfidfVectorizer from scikit-learn (sklearn) to convert the collection of text data (contained in the preprocessed_reviews variable) into a TF-IDF (Term Frequency-Inverse Document Frequency) matrix representation. This data along with the encoded default calssification is then given as an input to the RandomForest classifier and the evaluation metrics such as accuracy will be compared with the one obtained through the manual approach.




