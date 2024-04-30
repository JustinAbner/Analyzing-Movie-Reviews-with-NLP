# Sentiment Analysis of Movie Reviews using NLP

## Synopsys
This project utilizes movie reviews and provided sentiment values of 1 or 0 (positive or negative, respectively) to predict sentiment. A sentiment analysis was performed by utilizing TextBlob to calculate the polarity. The reviews were stripped of any non-letters, fed into a word tokenizer, passed through a Porter Stemmer, and then each word joined back together to reform the review. A Logistic Regression model was created by using the sentiment column as our target variable and the modified reviews as our feature variable. Prior to applying the Logistic Regression, the reviews were vectorized using a TfidfVectorizer.
### Key packages
- TextBlob
- nltk
- sklearn
