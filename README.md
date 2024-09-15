# Instagram Sentiment Analysis through Google Play Store Reviews
## Introduction
In this project, I performed scraping using Python and
collected 319,500 data that’s containing reviews of the
Instagram app from the Google Play Store. The data
went through a process of data cleaning, preprocessing,
normalization, tokenization, model training, model
evaluation, and visualization. The accuracy achieved in
this project was 81.48%, with a classification of 56.2%
positive reviews and 43.8% negative reviews
### Output

<div align="center">
	<img width="250" height="250" src="https://github.com/salwamhrn11/sentiment-analysis-instagram/blob/fe0353bfdd34e1770b278b0842077a05e75cc41e/p%E2%80%AAie-chart.png">
</div>

The Complement Naive Bayes model achieved 80.94%
accuracy. The confusion matrix shows 8887 true
negatives and 11263 true positives. Precision, recall,
and F1-scores are balanced, with class 0 having an F1-
score of 0.79 and class 1 at 0.83, indicating solid
performance for both sentiment classes.

```
ComplementNB model accuracy is 81.48%
------------------------------------------------
Confusion Matrix:
      0      1
0  8894   2272
1  2720  13066
------------------------------------------------
Classification Report:
              precision    recall  f1-score   support

           0       0.77      0.80      0.78     11166
           1       0.85      0.83      0.84     15786

    accuracy                           0.81     26952
   macro avg       0.81      0.81      0.81     26952
weighted avg       0.82      0.81      0.82     26952
```
This visualization is a confusion matrix that presents the classification results of a sentiment analysis
model. It shows True Positives (TP) and True Negatives (TN) as the largest proportions in the matrix,
indicating the correct predictions made by the model for positive and negative sentiments, respectively.
The False Positives (FP) and False Negatives (FN) represent incorrect predictions
<div align="center">
	<img width="250" height="250" src="https://github.com/salwamhrn11/sentiment-analysis-instagram/blob/fe0353bfdd34e1770b278b0842077a05e75cc41e/confusion-matrix.png">
</div>
