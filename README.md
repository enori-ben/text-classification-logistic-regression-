# Text Classification with Logistic Regression

This project implements a **Text Classification model using Logistic Regression** to perform sentiment analysis on movie reviews.

The project explores how machine learning can classify text into positive and negative sentiments.

## Dataset
- **Movie Reviews Dataset** from NLTK.
- 2,000 movie reviews.
- 1,000 positive and 1,000 negative reviews.

## Technologies
- Python
- NumPy
- Pandas
- NLTK
- Scikit-learn
- Matplotlib

## Project Workflow
1. Load and preprocess the text data.
2. Convert text into numerical features using Bag of Words (`CountVectorizer`).
3. Split the dataset into training and testing sets.
4. Implement Logistic Regression from scratch using NumPy.
5. Train the model using Gradient Descent.
6. Evaluate performance using Accuracy, Precision, Recall, and F1-score.
7. Compare the custom implementation with Scikit-learn.

## Challenges
- **Decision Boundary:** Experiment with different classification thresholds.
- **L2 Regularization:** Reduce overfitting by penalizing large weights.
- **Mini-Batch Gradient Descent:** Train the model using batches of samples.

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/text-classification-logistic-regression.git
   ```
2. Install the required libraries:
   ```bash
   pip install numpy pandas nltk scikit-learn matplotlib
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Author
**Noureddine Ben Attous**

MSc Student in Artificial Intelligence and Data Science.
