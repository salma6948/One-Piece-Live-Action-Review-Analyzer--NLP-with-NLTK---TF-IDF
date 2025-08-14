# One Piece Live-Action Review Analyzer

This project analyzes IMDb user reviews for the live-action adaptation of the popular anime and manga series, **"One Piece"**. Using **NLP techniques** with Python’s NLTK library, it demonstrates preprocessing, text vectorization, and sentiment classification.

---

## Dataset

The dataset (`reviews.csv`) contains user reviews up to **October 10, 2023**. It includes the following columns:

- **Title**: The title of the review.  
- **Review**: The actual text of the review.  
- **Date**: The date the review was posted.  
- **Rating**: User rating, converted into three classes:
  - `0` → Negative  
  - `1` → Neutral  
  - `2` → Positive  

---

## Features & Workflow

The project covers:

- **Text Preprocessing**: Tokenization, stopwords removal using NLTK.  
- **TF-IDF Vectorization**: Transforming review text into numerical features.  
- **Classification**: Multinomial Naive Bayes (`MultinomialNB`) for predicting sentiment.  
- **Evaluation**: Accuracy, classification report, and confusion matrix.  

**Libraries used**: `nltk`, `scikit-learn`, `pandas`, `matplotlib`, `seaborn`, `numpy`, `string`.  

