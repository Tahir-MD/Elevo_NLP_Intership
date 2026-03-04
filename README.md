Elevvo NLP Internship Projects

📚 Table of Contents

1. Contact Information
2. Task 1: IMDB Sentiment Analysis
3. Task 2: News Category Classification
4. Task 3: BBC News Topic Modeling
5. Task 4: Resume Screening Using NLP

---

Contact Information

👤 Tahir Mahmood

Method Details
📧 Email tahirdool67@gmail.com
📱 Phone +92 319 2429525
🔗 LinkedIn linkedin.com/in/tahir-mahmood-781b93329
💻 GitHub github.com/Tahir-MD/Elevo_NLP_Intership
📍 Location Pakistan

🌐 Social Profiles

https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white
https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white
https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white

📱 Quick Connect

Feel free to reach out for:

· 🤝 Collaboration opportunities
· 💼 Job opportunities
· ❓ Questions about projects
· 📚 Knowledge sharing
· 🔬 Research discussions

---

Task 1: IMDB Movie Reviews Sentiment Analysis

📊 Project Overview

This project performs sentiment analysis on 50,000 IMDB movie reviews using machine learning techniques to classify reviews as positive or negative.

🎯 Features

· Text preprocessing and cleaning
· TF-IDF vectorization
· Two classification models: Logistic Regression and Naive Bayes
· Model performance comparison
· Data visualization (Word Clouds, Top Words)

📈 Results

Model Accuracy Precision Recall F1-Score
Logistic Regression 88.54% 0.89 0.89 0.89
Naive Bayes 84.89% 0.85 0.85 0.85

🛠️ Installation

Prerequisites

Python 3.8+

---

Task 2: News Category Classification with AG News Dataset

📋 Project Overview

A comprehensive machine learning project for classifying news articles into categories using various NLP techniques and classification algorithms. This project implements a multiclass text classification system to categorize news articles into four categories: World, Sports, Business, and Sci/Tech.

🚀 Features

· Complete Text Preprocessing Pipeline: Tokenization, stopword removal, lemmatization, and text cleaning
· Multiple ML Models: Logistic Regression, Random Forest, SVM, and Neural Network
· Advanced Feature Engineering: TF-IDF vectorization with n-grams
· Comprehensive Visualizations: Word clouds, frequency plots, confusion matrices
· Model Comparison: Side-by-side performance evaluation
· Production-Ready Prediction Function: Deployable API for new article classification

📊 Dataset

· Source: AG News on Kaggle
· Training Samples: 120,000
· Testing Samples: 7,600
· Categories: World, Sports, Business, Sci/Tech

---

Task 3: BBC News Topic Modeling

📌 Project Overview

This project performs topic modeling on the BBC News dataset to discover hidden themes and topics in news articles. It implements and compares two popular topic modeling techniques: Latent Dirichlet Allocation (LDA) and Non-Negative Matrix Factorization (NMF).

🎯 Objectives

· Extract hidden topics from BBC news articles
· Preprocess text data for NLP tasks
· Implement LDA and NMF algorithms
· Compare performance of both techniques
· Visualize topics using word clouds

📂 Dataset

· Source: BBC News Dataset from Kaggle
· Format: CSV file
· Size: 6.38 MB
· Content: News articles covering business, entertainment, politics, sport, and technology

🛠️ Technologies Used

Category Technologies
Programming Python 3.x
Data Processing Pandas, NumPy
NLP NLTK, Regex
Machine Learning Scikit-learn (LDA, NMF, CountVectorizer)
Visualization Matplotlib, WordCloud

📊 Results

Sample LDA Topics

Topic Top Words
Topic 1 business, company, market, sales, growth
Topic 2 film, music, award, star, festival
Topic 3 government, election, party, minister, political
Topic 4 game, match, player, win, season
Topic 5 technology, internet, mobile, software, digital

Sample NMF Topics

Topic Top Words
Topic 1 mobile, phone, technology, users, devices
Topic 2 economy, bank, rate, price, inflation
Topic 3 election, vote, party, minister, government
Topic 4 film, award, actor, director, festival
Topic 5 football, match, player, league, club

---

Task 4: Resume Screening Using NLP (Industry Level)

📌 Project Overview

This project implements an intelligent resume screening system that automatically matches candidates with job descriptions using Natural Language Processing (NLP) and semantic search techniques.

🎯 Objectives

· Automate the resume screening process using NLP
· Match candidate resumes with job descriptions using semantic similarity
· Extract and compare skills between resumes and job requirements
· Rank candidates based on relevance scores
· Provide interpretable match reports with matched and missing skills

📂 Dataset

· Job Descriptions: 4 sample job positions (Data Scientist, ML Engineer, Python Developer, Data Analyst)
· Resumes: 5 sample candidate resumes with varying skill sets
· Skills Database: 15+ common technical skills for extraction and matching

🛠️ Technologies Used

Category Technologies
Programming Python 3.x
NLP/Embeddings Sentence Transformers (all-MiniLM-L6-v2)
Data Processing Pandas, NumPy, Regular Expressions
Similarity Matching Cosine Similarity
Document Processing PyPDF2, python-docx

📊 Results

Sample Similarity Matrix

Candidate Data Scientist ML Engineer Python Developer Data Analyst
John Smith 88.3% 72.1% 65.4% 58.7%
Sarah Johnson 75.2% 92.5% 68.9% 45.3%
Mike Chen 62.8% 58.4% 85.7% 51.2%
Emily Brown 55.6% 48.9% 52.3% 79.8%

Best Matches

Rank Candidate Job Position Match Score Matched Skills
1 Sarah Johnson ML Engineer 92.5% Python, TensorFlow, PyTorch, AWS
2 John Smith Data Scientist 88.3% Python, ML, SQL, NLP
3 Mike Chen Python Developer 85.7% Python, Django, Flask, Git

🔍 Key Features

Semantic Matching

· Uses state-of-the-art sentence transformers
· Captures contextual meaning beyond keyword matching
· Handles synonyms and related terms effectively

Skill Extraction

```python
# Example of extracted skills
Candidate: Sarah Johnson
Skills: ['Python', 'TensorFlow', 'PyTorch', 'AWS', 'Machine Learning']

Job: Machine Learning Engineer
Required: ['Python', 'TensorFlow', 'PyTorch', 'Deep Learning', 'MLOps', 'Cloud']
Matched: ['Python', 'TensorFlow', 'PyTorch', 'Cloud']
Missing: ['Deep Learning', 'MLOps']
```

💻 How to Run

Prerequisites

```bash
pip install pandas numpy sentence-transformers scikit-learn PyPDF2 python-docx
```

Steps

1. Clone the repository
2. Install required dependencies
3. Run the Jupyter notebook cell by cell
4. View results and match reports

---

📁 Repository Structure

```
Elevo_NLP_Intership/
│
├── Task_1_IMDB_Sentiment_Analysis.ipynb
├── Task_2_News_Classification.ipynb
├── Task_3_BBC_Topic_Modeling.ipynb
├── Task_4_Resume_Screening.ipynb
├── README.md
└── requirements.txt
```

🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit pull requests.

📄 License

This project is for educational purposes. All datasets belong to their respective owners.

---

⭐ Star this repository if you find it helpful!
