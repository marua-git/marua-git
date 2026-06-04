<div align="center">

# Marua Makpyr

**ML Engineer · Data Scientist**  
NLP · Computer Vision · End-to-end ML Pipelines

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/marua-makpyr-3941b1333)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/maruamakpyr)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mhyuga@list.ru)

</div>

---

## 🚀 Projects

<table>
<tr>
<td width="50%" valign="top">

### 📄 [OCR Document Pipeline](https://github.com/marua-git/ocr-pipeline)

A production-ready pipeline that transforms **scanned financial PDFs** into structured, queryable data. Built for MFOs and audit firms dealing with large volumes of Russian-language IFRS reports.

**How it works:** PDF pages are rendered as images → enhanced with OpenCV (denoising, deskewing, CLAHE contrast) → passed through Tesseract OCR → tables detected via morphological analysis → financial fields extracted with regex → exported to PostgreSQL and Excel.

**Results:** 95%+ accuracy on real MFO reports · 67-page document processed in ~4.5 min · 27 unit tests passing

`Python` `FastAPI` `Tesseract` `OpenCV` `PostgreSQL` `Docker` `GitHub Actions`

</td>
<td width="50%" valign="top">

### 📰 [News Recommendation API](https://github.com/marua-git/news-recommendation-api)

A content-based recommendation engine that suggests relevant news articles based on what a user is currently reading. No user history or login required — works purely on article content similarity.

**How it works:** Articles are vectorized using TF-IDF → similarity computed with cosine distance → top-N recommendations returned via REST API endpoint in real time.

**Results:** Sub-100ms response time · Fully containerized with Docker · Clean REST API with FastAPI and Swagger docs

`Python` `FastAPI` `scikit-learn` `TF-IDF` `Docker`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🐦 Twitter Airline Sentiment — NLP Classification

Multi-class sentiment classifier trained on **14,640 airline tweets** (positive / negative / neutral). The project covers the full NLP pipeline from raw noisy text to a deployable model.

**How it works:** Raw tweets cleaned (URLs, mentions, stopwords removed) → tokenized and vectorized → multiple classifiers compared (Logistic Regression, SVM, Naive Bayes) → best model selected based on F1-score per class.

**Key insight:** Negative sentiment dominated the dataset (63%) — handled class imbalance with weighted loss to avoid biased predictions.

`Python` `NLP` `scikit-learn` `NLTK` `Pandas` `Matplotlib` `Seaborn`

</td>
<td width="50%" valign="top">

### 🔨 More coming soon...

Currently building new projects in:
- 📊 Time series forecasting
- 🤖 LLM-powered applications
- 🖼️ Computer Vision pipelines

*Stay tuned — repositories will be added here as they're completed.*

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

**ML & Data Science**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat-square&logo=python&logoColor=white)
![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00?style=flat-square&logo=python&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-154f3c?style=flat-square&logo=python&logoColor=white)

**Backend & DevOps**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)

**CS Fundamentals**

![Algorithms](https://img.shields.io/badge/Algorithms_%26_Data_Structures-555?style=flat-square)
![OOP](https://img.shields.io/badge/OOP-555?style=flat-square)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

---

## 🎓 Education

**🏛️ International IT University (IITU / МУИТ)** · Almaty, Kazakhstan  
B.Sc. Software Engineering · Minor in Data Science · *2023 – 2027*

---

## 📜 Certifications

| Certificate | Provider | Courses |
|---|---|---|
| 🤖 Machine Learning Specialization | DeepLearning.AI / Stanford — Coursera | 3 |
| 🧠 Deep Learning Specialization | DeepLearning.AI — Coursera | 5 |
| 💬 Natural Language Processing Specialization | DeepLearning.AI — Coursera | 4 |
| ⚙️ MLOps Specialization | DeepLearning.AI — Coursera | 4 |
| 📊 Google Advanced Data Analytics | Google — Coursera | — |
| ➗ Mathematics for Machine Learning | Imperial College London — Coursera | 3 |
| 🐍 Python for Everybody | University of Michigan — Coursera | — |
| 🔢 Data Structures & Algorithms | — | — |

---

## 🎹 Beyond Code

Outside of work I play **piano** 🎹, play **tennis** 🎾, and spend time at the **gym** 🏋️‍♀️

---

<div align="center">

📍 Almaty, Kazakhstan &nbsp;·&nbsp; Open to ML / Data Science opportunities

</div>
