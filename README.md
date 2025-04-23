# Fake News Classifier 📰

This project uses machine learning to classify news articles as **fake** or **real** based on their title and article text. It features models built with Support Vector Classifier (SVC) and Naive Bayes, along with visualizations of feature importance and evaluation metrics.

## Models Used
- **Naive Bayes** – 92.84% accuracy, interpretable word-level features
- **SVC** – High precision-recall performance with TF-IDF features

## 🔍 Key Techniques
- Text preprocessing (stopword removal, lemmatization)
- TF-IDF vectorization
- Word cloud visualizations
- Model evaluation using accuracy, confusion matrix, and precision-recall curves

## 📊 Visual Examples
<p float="left">
  <img src="images/wordcloud_real.png" width="250"/>
  <img src="images/wordcloud_fake.png" width="250"/>
  <img src="images/confusion_matrix_svc.png" width="250"/>
</p>

## 📁 Files
- `Fake_News_Classifier.ipynb`: Full code for preprocessing, modeling, and evaluation
- `images/`: Key visualizations used in the project
- `data/`: (Optional) Add a README if you're unable to share the dataset

## 🔗 Resources
- Dataset source: [[Insert link if public](https://www.kaggle.com/datasets/aadyasingh55/fake-news-classification)]
- GitHub Repo: [This repo]
