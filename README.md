# 📧 Spam Email Classification using Logistic Regression

This project is focused on building a Machine Learning model to classify messages as Spam or Ham (Legitimate) using **Natural Language Processing (NLP)** and **Logistic Regression**. It uses the publicly available Spam Dataset (spam.csv) and demonstrates end-to-end text preprocessing, feature extraction, model training, and evaluation.

## 🧹 Text Preprocessing & NLP

- Converts raw text into numerical features using TF-IDF Vectorization

Optional NLP enhancements include:

- Tokenization – splitting text into words

- Stopwords removal – removing common words that don’t add meaning

- Lemmatization – reducing words to their root form

- N-grams – capturing common word combinations for better spam detection

## 🧠 Model Training

- Algorithm: Logistic Regression

- Trained to classify messages as **Spam** or **Ham**

- Evaluated using metrics like accuracy, precision, recall, and F1-score

## 📊 Model Evaluation

- Model accuracy and performance metrics demonstrate strong classification of spam messages

- Visualization can include confusion matrix or classification report heatmaps

💡 Key Insights

- Spam messages often contain urgent or promotional words like “free”, “win”, “offer”

- Ham messages are more contextual and personalized

- TF-IDF effectively highlights the words that carry the most weight for spam detection

## 🛠️ Technologies Used

- Python (Pandas, NumPy) – data handling and manipulation

- Scikit-learn – model building and evaluation

- Matplotlib / Seaborn – visualizations

- Jupyter Notebook / Google Colab – development environment

## 👨‍💻 Author

**Syed Danish Ahmed**

**Aspiring Data Scientist | Computer Engineering Student**

If you find this project valuable, please ⭐ the repository. Your support is greatly appreciated!

Dataset Source: Kaggle - https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset
