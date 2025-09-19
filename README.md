#     Spam-Detection-Text-Processing

This repository contains a Jupyter notebook pipeline for Mail spam detection using classical text preprocessing + feature extraction + classification.

---

## Contents

- `spam_NLP.csv` — Original Mail messages labelled “spam” or “ham”.
- `spam_NLP_cleaned.csv` — Cleaned version of the text (lowercasing, punctuation removed, etc.).
- `TEST_DATA_spam.csv` — Smaller dataset used for quick testing/validation.
- `main.ipynb` — Main notebook: loads data, cleans, extracts features, trains classifier, evaluates.
- `logic.ipynb` — Supporting notebook for experiments / exploring alternative preprocessing and feature setups.

---

## Features & What It Does

- Text preprocessing: tokenization, lower-case conversion, stopword removal, punctuation removal, possibly more cleaning steps (stemming / lemmatization if included).
- Feature extraction:
  - Bag of Words (count vectorization)
  - TF-IDF vectorization
- Classification:
  - Multinomial Naive Bayes classifier
- Evaluation:
  - Accuracy
  - Precision, Recall, F1-score
  - Confusion matrix

---

## Requirements

- Python 3.8+ (ideally)
- Required packages:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`

---

## Run

1. Clone the repository  
```bash
   git clone https://github.com/Splendorius/Spam-Detection-Text-Processing.git
   cd Spam-Detection-Text-Processing
```
2. Install dependencies
```bash
pip install pandas numpy scikit-learn matplotlib
```
3. Launch Jupyter Notebook
```bash
jupyter notebook
```
4. Open the notebook main.ipynb and run the cells top-to-bottom.
