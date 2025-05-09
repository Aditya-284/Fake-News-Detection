# 📰 Fake News Detection using Machine Learning

This repository contains a project that uses Natural Language Processing (NLP) and machine learning to classify news articles as **Fake** or **Real**. The model is trained on a dataset of news articles and predicts whether the given content is credible or not.

## 📌 Project Description

Fake news has become a significant issue in today's digital era. This project aims to create a machine learning model that can detect fake news based on the textual content of news articles.

We utilize traditional machine learning algorithms and text preprocessing techniques to build an accurate classifier.

## 🚀 Features

- Text preprocessing (removing punctuation, stopwords, etc.)
- TF-IDF vectorization for converting text to numerical features
- Classification using:
  - Logistic Regression
- Model evaluation using accuracy, confusion matrix, and classification report

## 🧠 Tech Stack

- Python
- Jupyter Notebook
- scikit-learn
- Pandas, NumPy
- NLTK (for text processing)
- Matplotlib, Seaborn (for visualization)

## 📁 Dataset

The project uses two datasets:

- `train.csv` — contains labeled news articles used for training the model.
- `test.csv` — contains unlabeled news articles used for testing predictions.

Each row in the training dataset includes:

- **id** — Unique identifier for the news article.
- **title** — Title of the article.
- **author** — Author of the article.
- **text** — Full text of the article.
- **label** — `1` for fake news, `0` for real news.

You can download the dataset from [Kaggle](https://www.kaggle.com/c/fake-news/data) or use the versions provided in this repository.
## 📊 Model Performance

The Logistic Regression model achieves 97% accuracy on the test set, indicating strong performance in detecting fake news based on textual content.

> You can view the model evaluation plots and metrics inside the notebook or in the [Code Pics](https://github.com/Aditya-284/Fake-News-Detection/tree/main/Code%20Pics)

## 🛠️ How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/Aditya-284/Fake-News-Detection.git
   cd Fake-News-Detection
   ```
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:
   ```bash
   jupyter notebook fakenews_AI.ipynb
   ```

## 📈 Future Improvements

- Explore deep learning approaches (e.g., LSTM, BERT)
- Build a web interface using Flask or Streamlit
- Extend to multi-language support

## 🤝 Contributing

Contributions are welcome! Feel free to:

- Fork this repository
- Open issues for improvements or bugs
- Submit pull requests with enhancements
