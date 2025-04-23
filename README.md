# News-Categorization--Naive-Bayes
A Python ML project for classifying news articles using the Multinomial Naive Bayes algorithm. Includes data cleaning, text preprocessing, TF-IDF vectorization, model training, and evaluation. Visualizes category distribution and performance metrics. Built with scikit-learn and pandas.

## NEWS CATEGORIZATION USING NAIVE BAYES

This project is a machine learning-based news classification system built using the Multinomial Naive Bayes algorithm. It classifies news articles into different categories based on their content. The project demonstrates a complete NLP pipeline — from data preprocessing to model evaluation — and is ideal for beginners exploring text classification with Python.

---

PROJECT STRUCTURE


- notebook.ipynb : Main Jupyter Notebook containing code and analysis
- README.txt : Project documentation

---

FEATURES

- Data cleaning and preprocessing (lowercasing, stopword removal, punctuation removal)
- TF-IDF vectorization of news text
- Classification using Multinomial Naive Bayes
- Model evaluation using accuracy, precision, recall, F1-score
- Confusion matrix and category distribution visualizations
- Clean, beginner-friendly Python implementation

---

DATASET

The dataset consists of news articles, each with a corresponding category. Typical columns include:
- Title
- Full Text
- Category Label

The dataset is accessed from Google Drive when run in Google Colab.

---

TECHNOLOGIES USED

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib and Seaborn for visualization
- Google Colab for execution and Drive integration

---

HOW TO RUN

1. Clone the repository:
   git clone https://github.com/your-username/news-categorization-naive-bayes
   cd news-categorization-naive-bayes

2. Install dependencies:
   pip install -r requirements.txt

3. Open and run the notebook:
   Use Google Colab or Jupyter Notebook to run 'notebook.ipynb'

4. Mount Google Drive (in Colab) to load the dataset.

---

WORKFLOW

1. Load and explore the dataset.
2. Preprocess the text (lowercase, clean, tokenize, remove stopwords).
3. Vectorize text data using TF-IDF.
4. Split into training and testing sets.
5. Train using Multinomial Naive Bayes.
6. Evaluate using accuracy, confusion matrix, and classification report.

---

RESULTS

- High classification accuracy for common categories
- Confusion matrix visualizes model's strengths and weaknesses
- Demonstrates the effectiveness of Naive Bayes for text classification

