# Fake-News-Detector
#  Fake News Detector using Machine Learning

This project is a **Fake News Detector** built using Python and Machine Learning. It uses real-world datasets to classify whether a news article is **Real** or **Fake** with high accuracy.

---

##  Features

- Real vs. Fake news classification
- Built using **TF-IDF**, **PassiveAggressiveClassifier**
- Achieves **99.48% accuracy**
- Supports testing custom headlines (like Insta forwards or news you see online)
- Beginner-friendly, made step-by-step in Google Colab

---

##  Technologies Used

- Python 
- Scikit-learn (Machine Learning)
- Pandas & NumPy (Data handling)
- TF-IDF (Text vectorization)
- Google Colab (Jupyter environment)

---

##  Dataset

We used Kaggle’s combined dataset:
- `Fake.csv` — Contains fake news articles
- `True.csv` — Contains real news articles

Each article was labeled and cleaned for training.

---

##  How It Works

1. Load and label data
2. Clean the text (lowercase, remove punctuation/links)
3. Split into training and test sets
4. Convert text to vectors using TF-IDF
5. Train using `PassiveAggressiveClassifier`
6. Predict and evaluate on test data
7. Try your own news with the `check_news()` function!

---

##  Accuracy Achieved

>  99.48% on test data  
> Super reliable for academic use and personal experiments!

---

##  Try it Yourself

```python
check_news("PM announces free iPhones for all citizens")
# Output:  Fake News
