# 📰 Fake News Classification

This project focuses on building and evaluating machine learning models to classify news articles as **Fake** or **Real**. By leveraging natural language processing and classification algorithms, the goal is to better understand and combat misinformation.

---

## 📌 Project Overview

Using a labeled dataset of news articles, this project compares two popular machine learning classifiers:

- **Naive Bayes**
- **Support Vector Classifier (SVC)**

The analysis includes preprocessing steps, feature extraction using TF-IDF, and visualizations to interpret both the data and model performance.

---

## 📁 Folder Structure

├── notebooks/ # Jupyter Notebooks for exploration and modeling
├── datasets/ # Raw and processed datasets
├── visualizations/ # Saved plots (word clouds, confusion matrix, etc.)
└── README.md # Project documentation

---

## 📊 Visualizations

The project includes:

- Class distribution bar charts  
- Word clouds of fake vs. real headlines  
- Feature importance plots (for Naive Bayes)  
- Confusion matrix (for SVC)  
- Precision-Recall curve and classification report

These help interpret how each model performs and what features are most influential in predictions.

---

## ⚙️ Methods & Tools

- **Languages:** Python  
- **Libraries:** scikit-learn, pandas, matplotlib, seaborn, nltk, wordcloud  
- **Techniques:** Text vectorization (TF-IDF), model evaluation metrics, data cleaning  

---

## 🧠 Key Results

- The **Support Vector Classifier (SVC)** demonstrated stronger performance than Naive Bayes across precision, recall, and F1-score metrics.
- Feature analysis revealed important indicators of fake news, aiding interpretability.

---

## 📈 Next Steps

- Add more classifiers (e.g., Logistic Regression, Random Forest)
- Explore deep learning approaches (e.g., LSTM or BERT)
- Deploy a simple web interface for live predictions

---

## 📬 Contact

For questions or collaborations, feel free to reach out via [alyssaday2003@gmail.com] or connect on [LinkedIn](www.linkedin.com/in/alyssaday01).

