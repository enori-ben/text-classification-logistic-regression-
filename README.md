# Text Classification: Logistic Regression & Naive Bayes

A machine learning project for **binary sentiment analysis of movie reviews**. The repository contains two Jupyter notebooks that implement and explore text-classification algorithms.

## Notebooks

| Notebook | Description |
|---|---|
| [TextClassificationLogisticRegression.ipynb](./TextClassificationLogisticRegression.ipynb) | Implements Logistic Regression for positive/negative sentiment classification, including text preprocessing, Bag of Words features, gradient-descent training, evaluation, and comparison with Scikit-learn. |
| [NaiveBayesTextClassification.ipynb](./NaiveBayesTextClassification.ipynb) | Implements Multinomial Naive Bayes and explores smoothing, feature representations, basic negation handling, and validation-based alpha tuning. |

## Dataset

Both notebooks use the **Movie Reviews corpus provided by NLTK**:
- 2,000 movie reviews
- 1,000 positive reviews and 1,000 negative reviews

The corpus is not the IMDb dataset. Results may vary depending on preprocessing, data splitting, and model settings.

## Technologies

- Python
- Jupyter Notebook
- NumPy
- Pandas
- NLTK
- Scikit-learn
- Matplotlib

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/enori-ben/text-classification-logistic-regression-.git
   cd text-classification-logistic-regression-
   ```

2. Install the required libraries:

   ```bash
   pip install numpy pandas nltk scikit-learn matplotlib jupyter
   ```

3. Download the NLTK Movie Reviews corpus (if it is not downloaded automatically by the notebook):

   ```python
   import nltk
   nltk.download('movie_reviews')
   ```

4. Start Jupyter:

   ```bash
   jupyter notebook
   ```

5. Open either notebook and run its cells in order.

## Evaluation

The notebooks evaluate classification performance using metrics such as:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix

## Author

**Noureddine Ben Attous**  
MSc Student in Artificial Intelligence and Data Science
