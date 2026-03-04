# IMDB Movie Reviews Sentiment Analysis
# Task_1
## 📊 Project Overview
This project performs sentiment analysis on 50,000 IMDB movie reviews using machine learning techniques to classify reviews as positive or negative.

## 🎯 Features
- Text preprocessing and cleaning
- TF-IDF vectorization
- Two classification models: Logistic Regression and Naive Bayes
- Model performance comparison
- Data visualization (Word Clouds, Top Words)

## 📈 Results
| Model | Accuracy | Precision | Recall | F1-Score |
|-------|----------|-----------|--------|----------|
| Logistic Regression | 88.54% | 0.89 | 0.89 | 0.89 |
| Naive Bayes | 84.89% | 0.85 | 0.85 | 0.85 |

## 🛠️ Installation

### Prerequisites

Python 3.8+

# Task_2
# 📰 News Category Classification with AG News Dataset
A comprehensive machine learning project for classifying news articles into categories using various NLP techniques and classification algorithms.

## 📋 Project Overview
This project implements a multiclass text classification system to categorize news articles into four categories: World, Sports, Business, and Sci/Tech. The solution includes complete text preprocessing, feature engineering, multiple classification models, and visualization components.

🚀 Features
Complete Text Preprocessing Pipeline: Tokenization, stopword removal, lemmatization, and text cleaning

Multiple ML Models: Logistic Regression, Random Forest, SVM, and Neural Network

Advanced Feature Engineering: TF-IDF vectorization with n-grams

Comprehensive Visualizations: Word clouds, frequency plots, confusion matrices

Model Comparison: Side-by-side performance evaluation

Production-Ready Prediction Function: Deployable API for new article classification

📊 Dataset
The project uses the AG News dataset, which contains:

120,000 training samples

7,600 testing samples

4 categories: World, Sports, Business, Sci/Tech

Each sample contains a title and description

Dataset Source: AG News on Kaggle

🛠️ Installation
Prerequisites
Python 3.7+

pip package manager

# Task 3 
# BBC News Topic Modeling

# 📌 Project Overview

This project performs topic modeling on the BBC News dataset to discover hidden themes and topics in news articles. It implements and compares two popular topic modeling techniques: Latent Dirichlet Allocation (LDA) and Non-Negative Matrix Factorization (NMF).

# 🎯 Objectives

· Extract hidden topics from BBC news articles
· Preprocess text data for NLP tasks
· Implement LDA and NMF algorithms
· Compare performance of both techniques
· Visualize topics using word clouds

# 📂 Dataset

· Source: BBC News Dataset from Kaggle
· Format: CSV file
· Size: 6.38 MB
· Content: News articles covering various categories including business, entertainment, politics, sport, and technology

# 🛠️ Technologies Used

Category Technologies
Programming Python 3.x
Data Processing Pandas, NumPy
NLP NLTK, Regex
Machine Learning Scikit-learn (LDA, NMF, CountVectorizer)
Visualization Matplotlib, WordCloud

# 📋 Project Workflow

1. Data Loading

· Load BBC News dataset from CSV file
· Explore data structure and columns
· Combine relevant text columns

2. Text Preprocessing

· Convert text to lowercase
· Remove special characters and numbers
· Remove stopwords (common words like 'the', 'is', 'at')
· Remove words with length less than 3 characters
· Filter out empty or very short documents

3. Feature Extraction

· Convert preprocessed text to document-term matrix
· Use CountVectorizer with parameters:
  · max_df=0.9: Ignore words that appear in >90% of documents
  · min_df=5: Ignore words that appear in <5 documents
  · max_features=1000: Limit vocabulary size

4. Topic Modeling

Latent Dirichlet Allocation (LDA)

· Probabilistic generative model
· Assumes documents are mixtures of topics
· Topics are distributions over words
· Implemented with 5 topics

Non-Negative Matrix Factorization (NMF)

· Matrix factorization technique
· Decomposes document-term matrix into two matrices
· Non-negativity constraint ensures interpretability
· Implemented with 5 topics

5. Topic Interpretation

· Extract top 10 words for each topic
· Assign dominant topic to each document
· Analyze topic distribution across documents

6. Model Comparison

· Compare LDA vs NMF results
· Analyze differences in topic words
· Evaluate topic coherence

7. Visualization

· Generate word clouds for each topic
· Display top words with weights
· Visualize topic distribution

# 📊 Results

Sample LDA Topics

Topic Top Words
Topic 1 business, company, market, sales, growth
Topic 2 film, music, award, star, festival
Topic 3 government, election, party, minister, political
Topic 4 game, match, player, win, season
Topic 5 technology, internet, mobile, software, digital

## Sample NMF Topics

Topic Top Words
Topic 1 mobile, phone, technology, users, devices
Topic 2 economy, bank, rate, price, inflation
Topic 3 election, vote, party, minister, government
Topic 4 film, award, actor, director, festival
Topic 5 football, match, player, league, club

# 🔍 Key Findings

· LDA tends to produce more balanced topic distributions
· NMF often gives more sparse and focused topics
· Both methods successfully identify distinct news categories
· Topic words align well with BBC news categories

# 💻 How to Run

Prerequisites

```bash
pip install pandas numpy scikit-learn nltk matplotlib wordcloud
```

Steps

1. Download the BBC News dataset from Kaggle
2. Place the CSV file in the project directory
3. Run all cells in the Jupyter notebook
4. View results and visualizations

## 📁 Project Structure

```
bbc-news-topic-modeling/
│
├── BBC News Topic Modeling.ipynb    # Main notebook
├── BBC News Dataset.csv              # Dataset (to be downloaded)
├── bbc_topics_results.csv            # Output results
├── README.md                         # Project documentation
└── requirements.txt                   # Dependencies
```

# 🎓 Key Learning Outcomes

· Text preprocessing techniques for NLP
· Document-term matrix creation
· LDA algorithm implementation
· NMF algorithm implementation
· Topic model evaluation and comparison
· Results visualization techniques

# 🤝 Contributing

Feel free to fork this project, submit issues, or suggest improvements. Contributions are welcome!

# 📄 License

This project is for educational purposes. The dataset belongs to its original authors.

# 📧 Contact

For questions or feedback, please reach out via GitHub.
