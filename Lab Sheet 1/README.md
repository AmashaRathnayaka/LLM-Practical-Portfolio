
# Lab Sheet 1 – Sentiment Analysis Using Traditional Machine Learning

## Objective
To develop a machine learning model that classifies text reviews as positive or negative using traditional machine learning techniques.

## Dataset
- Source: [UCI Sentiment Labelled Sentences](https://archive.ics.uci.edu/dataset/331/sentiment+labelled+sentences)
- Dataset sources: Amazon, IMDb and Yelp
- Original records: 2,748
- Records after removing duplicates: 2,731
- Sentiment labels: 0 = Negative, 1 = Positive

## Technologies Used
- Python
- Google Colab
- Pandas
- Scikit-learn
- Matplotlib

## Methodology
1. Loaded and combined three sentiment datasets.
2. Explored the dataset for missing values and duplicates.
3. Removed 17 duplicate records.
4. Preprocessed text by converting it to lowercase and removing punctuation, numbers and extra spaces.
5. Split the data into 80% training and 20% testing.
6. Applied TF-IDF feature extraction.
7. Trained a Logistic Regression classifier.
8. Evaluated the model using accuracy, precision, recall, F1-score and a confusion matrix.
9. Tested the model using four new review sentences.

## Results
- Model accuracy: **80.80%**
- Test samples: 547
- Correct predictions: 442
- Incorrect predictions: 105
- All four manually entered test sentences were classified correctly.

## Evidence

### Dataset Exploration
![Dataset Exploration](screenshots/dataset_exploration.png)

### Model Training
![Model Training](screenshots/model_training.png)

### Confusion Matrix
![Confusion Matrix](screenshots/confusion_matrix.png)

### Sentiment Predictions
![Sentiment Predictions](screenshots/sentiment_predictions.png)

## Observations
The dataset contained no missing values and had a nearly balanced distribution of positive and negative reviews. The Logistic Regression model achieved 80.80% accuracy, although some reviews were incorrectly classified.

## Learning Outcomes
- Learned to load and explore text datasets.
- Applied text preprocessing techniques.
- Used TF-IDF to convert text into numerical features.
- Trained and evaluated a Logistic Regression classifier.
- Interpreted a confusion matrix and classification metrics.

## Notebook
[View Completed Sentiment Analysis Notebook](notebooks/LabSheet1_SentimentAnalysis.ipynb)

## Conclusion
This practical demonstrated how traditional machine learning can be used for sentiment analysis. TF-IDF and Logistic Regression provided a baseline approach for classifying positive and negative text reviews.
