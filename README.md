# Email Spam Classification

A machine learning project that classifies emails as spam or ham using text preprocessing, TF-IDF vectorization, and multiple classification models.

## Project Summary
This project uses the SpamAssassin public corpus to build and compare several spam classification models. The workflow includes text cleaning, tokenization, stopword removal, stemming, HTML extraction, feature engineering with TF-IDF, and model evaluation using cross-validation and test accuracy.

## Models Compared
- Logistic Regression
- LDA
- QDA
- Decision Tree
- K-Nearest Neighbors
- Random Forest
- Bagging Classifier
- Extra Trees
- Gradient Boosting
- XGBoost

## Final Takeaway
Although Extra Trees achieved the highest accuracy, Logistic Regression was selected as the best final model because it provided very strong performance with better interpretability.

## Repository Structure
- `notebooks/` – Jupyter notebook for the project
- `reports/` – final project report
- `data/` – instructions for dataset setup
- `requirements.txt` – Python dependencies

## How to Run
1. Download the SpamAssassin dataset
2. Create `data/Email/Ham` and `data/Email/Spam`
3. Open the notebook in `notebooks/`
4. Run all cells

## Tools Used
Python, pandas, NLTK, scikit-learn, XGBoost, matplotlib, BeautifulSoup, WordCloud
