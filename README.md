 Fake News Detection

This project builds Machine Learning and Deep Learning models to detect **Fake vs Real news** articles.  
It uses **TF-IDF vectorization**, multiple ML models (Logistic Regression, Naive Bayes, Random Forest), and a **Deep Learning Neural Network**.

---

Project Structure
- `notebooks/` → Jupyter notebook with full workflow (EDA + ML + DL).
- `src/` → Python scripts for modular use.
- `results/` → Word clouds, confusion matrices, metrics.
- `data/` → Fake.csv and True.csv (from Kaggle dataset, not included here).

---

Features
- Data preprocessing (tokenization, stopwords removal, lemmatization)
- Exploratory Data Analysis (word clouds, frequent words, length distribution)
- Models:
  - Logistic Regression
  - Naive Bayes
  - Random Forest
  - Deep Learning (Keras Sequential Model)
- Performance comparison of models
- Custom news prediction

---

Results
- Best Model: **Random Forest / Deep Learning**  
- Accuracy: ~95%+  
- Confusion matrix shows performance clearly.

---

Installation
```bash
git clone https://github.com/YOUR_USERNAME/Fake-News-Detection.git
cd Fake-News-Detection
pip install -r requirements.txt
