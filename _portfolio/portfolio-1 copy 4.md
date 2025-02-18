---
title: "Truthful vs. Deceptive Hotel Reviews Classification"
excerpt: "Utilized a variety of classifiers, including Linear Support Vector Classifier, Gradient Boosting Classifier, K-Nearest Neighbors Classifier, and Multinomial Naive Bayes Classifier to analyze hotel reviews. This project focuses on distinguishing between truthful and deceptive hotel reviews, showcasing my skills in handling complex classification tasks."
collection: portfolio
---

## Overview
This study focuses on the classification of hotel reviews as either truthful or deceptive. Various machine learning models were evaluated to determine their effectiveness in identifying deceptive reviews.

## Key Topics

### Models Used
- **Linear Support Vector Classifier (Linear SVC):** The best-performing model, effectively identifying deception.
- **Gradient Boosting Classifier:** Sequential decision trees for improving classification accuracy.
- **K-Nearest Neighbors (KNN):** Classifies based on the similarity of neighboring data points.
- **Multinomial Naïve Bayes:** A probabilistic classifier useful for multi-class text classification.

### Preprocessing Steps
- Converted text to lowercase for uniformity.
- Tokenized and lemmatized words while filtering stopwords.
- Retained punctuation due to its significance in sentiment analysis.

### Experimental Results
- Dataset: 1400 hotel reviews classified as Truthful Positive (TP), Truthful Negative (TN), Deceptive Positive (DP), and Deceptive Negative (DN).
- **Linear SVC achieved the highest accuracy at 87.86%.**
- Gradient Boosting (69.93%), KNN (64.29%), and MultinomialNB (79.29%) performed lower.

### Analysis of Misclassifications
- The study identified key phrases that led to incorrect classifications.
- Certain exaggerations and strong emotions misled the classifier.
- Ambiguous statements affected accuracy.

### Future Work
- Improve preprocessing by handling colloquialisms and uncommon terms.
- Refine dataset alignment by reassessing questionable labels.
- Explore deep learning approaches (RNNs, LSTMs, Transformer models).
- Implement data augmentation techniques to enhance dataset robustness.

## Conclusion
The study demonstrates that **Linear SVC is the most effective model** for classifying truthful and deceptive hotel reviews. Future improvements could include enhanced preprocessing and deep learning methods to boost performance.

**Read more and join the discussion:** [LinkedIn Post](https://www.linkedin.com/posts/jo%C3%A3o-vasco-9a50331a6_hotel-reviews-classification-activity-7124049557142786048-VDQy?utm_source=share&utm_medium=member_desktop)
------