# Arabic Dialect classification
A task to Build Arabic dialect with machine learning and deep learning classifiers using Twitter data.

# Dataset
Using starter dataset that contains dialect and id for each tweet to request the tweet text itself as dict from API https://recruitment.aimtechnologies.co/ai-tasks, add this dict to data frame and merge it with dialect to get all data in a data frame then save it as CSV file.

# Cleaning data:
- Use regex to filter out emojis, punctuation, non-Arabic chars, and normalize special Arabic characters.
- Save cleaned data into a separate data frame.

# preparing data for models
- performing a CountVectorizer and TFIDF transformer on the data before fed to machine learning model.
- performing a tokenizer and padding on the data before deep learning model.

# Machine learning classifiers
## Classifiers:
- SGD Classifier
- Multinomial
- Linear SVC
## Results:
- Perform confusion matrix, classification report for the best classifier.

# Deep Learning
## Models
- Text Classification with LSTM
## Results:
- Perform plots and prediction test on test data.

# Save the model for deployment
Using pickle to save trained models, victorizer, transformer, tokenizer and encoder to easily use it seperatly on deployment file

# Deploy
Using Flask API and pre-scripted HTML template to perform an easy interface for the user to use the model.

# Authors
Seaf Gomaa

# Acknowledgments
- More information available in the paper titled (Arabic Dialect Identification in the Wild) was puplished in 15 May 2020 from Qatar Computing Research Institute.

