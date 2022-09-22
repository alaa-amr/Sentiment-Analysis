# Sentiment Analysis
Apply Sentiment Analysis of movie reviews using sentiment polarity datasets (positive and negative).
# Methodology:
### Data preprocessing:
Firstly, we appended all the reviews and their sentiments to a dataframe, shuffled the rows, then we split the data to train(75%) and test(25%) sets We remove any non alphabet character using regular expressions We convert each word to lowercase We remove the stop words We apply lemmatization We applied count vectorizer and TF IDF vectorizer and compared the
# DataSet Summary:
- Data set used: polarity dataset v2.0
- 1000 text files for positive reviews, and 1000 text files for negative reviews, each file contains a paragraph about the movie either positive or negative a. note: We appended the reviews to a dataframe under a column called review, and there’s a column called sentiment tells whether the review is positive or negative
# Results:
## Models:
### Random Forest classifier:
With count vectorizer: 83% accuracy With TF IDF vectorizer: 83.8% accuracy

### Logistic Regression:
With count vectorizer: 84.6% accuracy With TF IDF vectorizer: 82% accuracy

### Linear SVC:
With TF IDF vectorizer: 84.8% accuracy (Best Model)

### AdaBoost using decision tree classifier:
With TF IDF vectorizer: 80.4% accuracy

### Conclusion: 
The best model with the highest accuracy is linear SVC used with TF IDF vectorizer (84.8% accuracy)

![image](https://user-images.githubusercontent.com/86886005/191833426-48fcdcc8-356c-499e-a1a1-897a4486ff68.png)


