# Fake-Real-News-Classification

Description:

The "Fake and Real News Dataset" comprises two distinct collections of news articles: one containing 23,502 articles labeled as fake news and the other containing 21,417 articles labeled as true news. Each article in the dataset is characterized by its title, body text, subject, and publication date. This dataset serves as a valuable resource for researchers and data enthusiasts interested in studying the prevalence, characteristics, and detection methods of fake news in comparison to genuine news. With its comprehensive coverage and structured format, the dataset offers opportunities for insightful analysis and the development of effective strategies for combating misinformation in the media landscape.


This project aims to classify news articles as **Fake** or **Real** using Natural Language Processing (NLP) and machine learning techniques. The classification is based on the text and title of the article. The dataset includes real-world news collected from sources.

Dataset Link: https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset/data


##  Dataset Description

- **Fake.csv**: Contains fake news articles.
- **True.csv**: Contains real news articles.
- Each article includes:
  - `title`: The headline of the article
  - `text`: Full article content
  - `subject`: Topic of the article
  - `date`: Publication date
- A new column `label` was added:
  - `0` = Fake News
  - `1` = Real News

---

##  Workflow

1. Load and merge datasets
2. Clean and preprocess text (lowercase, remove URLs, punctuation, etc.)
3. Combine article title and text
4. Apply TF-IDF Vectorization
5. Train a Logistic Regression model
6. Evaluate with accuracy, confusion matrix, and classification report
7. Visualize results

---

##  Model Results

- **Model**: Logistic Regression
- **Accuracy**: ~92%
- **Evaluation**:
  - Confusion Matrix
  - Precision, Recall, F1-Score
- **Features Used**: TF-IDF scores of article content

---

## 📈 Visualizations

- Sentiment & word distribution (optional)
- Confusion Matrix heatmap
- Classification performance metrics
