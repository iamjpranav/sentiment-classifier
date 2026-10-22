# Movie Review Sentiment Classifier
Classifies IMDb movie reviews as positive or negative.

**Dataset:** IMDb, 25,000 training and 25,000 test reviews
**Method:** TF-IDF features with two models

| Model | Accuracy |
|---|---|
| Logistic Regression | 87.99% |
| Linear SVM | 86.48% |

**What I learned from the errors:** In the 10 misclassified reviews I read, the model often got mixed reviews wrong. They praised the action or the cast ("entertaining", "decent film") but were negative overall, so the positive words fooled it. A simple word-count model can't tell when praise is followed by "but".

**Run it:** open movie_review.ipynb in Google Colab and run all cells.
