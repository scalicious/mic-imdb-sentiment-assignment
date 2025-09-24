# Sentiment Analysis on IMDB Reviews

This project classifies movie reviews as positive or negative using Logistic Regression Model.

## Data Preprocessing  
- Converts reviews to lowercase.  
- Removes HTML tags, URLs, and non-letter characters.  
- Cleans extra spaces.

## Feature Extraction  
- Uses CountVectorizer to convert text into numbers.  
- Removes common English stop words.  
- Extracts single words (unigrams), pairs (bigrams), and triples (trigrams).  
- Keeps up to 50,000 frequent words and ignores very rare or very common words.

## Model and Training
- Uses Logistic Regression with the lbfgs solver.  
- Regularization strength set with `C=3.0`.  
- Balanced classes to handle uneven data.  
- Runs up to 7000 iterations for training.

## Accuracy
- Achieves around 89% accuracy on the test set.

## Credits:
Name: Daksh Sablok\
Registration Number: 25BAI1227
