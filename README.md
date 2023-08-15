# fake-news-detection
Implementation of a machine learning model capable of distinguishing between real and fake news articles by leveraging the WELFake dataset from Kaggle.

### Approach

1. **Data Exploration and Cleaning**: Initial investigation of the dataset, visualization, and preprocessing steps including cleaning the text, lemmatization, and one-hot encoding.
2. **Feature Engineering**: Two features "text-length" and "title-length" are added.
3. **Model Training**: RNN Sequential model is trained and fine-tuned to get 96% accuracy on the test set.
