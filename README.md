<div align="center">

# Hi, I'm Marua 👋

**ML Engineer · Data Scientist · Software Engineer**

> *Based in Almaty, Kazakhstan 🇰🇿 · Studying @ IITU · Always learning something new*  
> *Passionate about turning raw data into intelligent systems that solve real problems*

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

Production-ready pipeline that transforms **scanned financial PDFs** into structured, queryable data. Built for MFOs and audit firms handling large volumes of Russian-language IFRS reports.

**How it works:** PDF pages rendered as images → enhanced with OpenCV (denoising, deskewing, CLAHE) → Tesseract OCR → morphological table detection → regex field extraction → exported to PostgreSQL + Excel.

✅ 95%+ accuracy on real MFO reports  
✅ 67-page document in ~4.5 min  
✅ 27 unit tests · REST API · Docker

`Python` `FastAPI` `Tesseract` `OpenCV` `PostgreSQL` `Docker` `GitHub Actions`

</td>
<td width="50%" valign="top">

### 📰 [News Recommendation API](https://github.com/marua-git/news-recommendation-api)

Content-based recommendation engine that suggests relevant news articles based on what a user is currently reading — no login or history required.

**How it works:** Articles vectorized with TF-IDF → cosine similarity computed → top-N recommendations returned via REST API in real time.

✅ Sub-100ms response time  
✅ Fully containerized with Docker  
✅ Swagger docs included

`Python` `FastAPI` `scikit-learn` `TF-IDF` `Docker`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🐦 Twitter Airline Sentiment — NLP Classification

Multi-class sentiment classifier trained on **14,640 airline tweets** (positive / negative / neutral). Full NLP pipeline from raw noisy social media text to a deployable model.

**How it works:** Tweets cleaned (URLs, mentions, stopwords removed) → TF-IDF vectorization → multiple classifiers compared (Logistic Regression, SVM, Naive Bayes) → best model selected on F1-score.

✅ Handled class imbalance (63% negative)  
✅ Full EDA with visualizations  
✅ Weighted loss for unbiased predictions

`Python` `NLP` `NLTK` `scikit-learn` `Pandas` `Seaborn`

</td>
<td width="50%" valign="top">

### 🔨 More coming soon...

Currently building:
- 📊 Time series forecasting
- 🤖 LLM-powered applications  
- 🖼️ Computer Vision pipelines
- 📱 Full-stack ML web apps

*New repositories added regularly — stay tuned!*

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

### 💻 Languages & Frameworks
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

### 🧠 ML & Data Science
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat-square&logo=python&logoColor=white)
![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00?style=flat-square&logo=python&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-154f3c?style=flat-square&logo=python&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Optuna](https://img.shields.io/badge/Optuna-4B8BBE?style=flat-square&logo=python&logoColor=white)

### 📊 Data Analytics & Visualization
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square&logo=python&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

### ⚙️ Backend & DevOps
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)

### 🔢 CS Fundamentals
![Algorithms](https://img.shields.io/badge/Data_Structures_%26_Algorithms-555?style=flat-square)
![OOP](https://img.shields.io/badge/OOP-555?style=flat-square)
![Design Patterns](https://img.shields.io/badge/Design_Patterns-555?style=flat-square)
![REST API](https://img.shields.io/badge/REST_API-555?style=flat-square)
![Linear Algebra](https://img.shields.io/badge/Linear_Algebra-555?style=flat-square)
![Statistics](https://img.shields.io/badge/Statistics_%26_Probability-555?style=flat-square)

---

## 🎓 Education

🏛️ **International IT University (IITU / МУИТ)** · Almaty, Kazakhstan  
B.Sc. Software Engineering · Minor in Data Science · *2023 – 2027*  
**GPA: 3.5 / 4.0**

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

Outside of work — playing **piano** 🎹, on the **tennis** court 🎾, or at the **gym** 🏋️‍♀️  
Always exploring something new, whether it's a new paper, framework, or a challenging dataset.

---

<div align="center">

📍 Almaty, Kazakhstan &nbsp;·&nbsp; 🎓 IITU 2023–2027 &nbsp;·&nbsp; 💼 Open to ML / Data Science opportunities

</div>
