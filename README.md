# Zomato Restaurant Insights: Customer Sentiment Analysis & Unsupervised Location Clustering

## 📌 Project Overview
This Capstone Project focuses on analyzing Zomato's restaurant data to extract meaningful business insights. The project is divided into two major tracks to solve real-world restaurant industry problems:
1. **Sentiment Analysis (NLP):** Analyzing customer reviews to classify them into Positive, Negative, or Neutral sentiments. This helps restaurants understand customer feedback at scale.
2. **Unsupervised Clustering (Machine Learning):** Grouping restaurants based on their geographical locations, cuisines, and average costs to identify optimal business hotspots and market gaps.

---

## 📊 Dataset Details
The project utilizes two primary datasets uploaded in this repository:
- `Zomato Restaurant names and Metadata.csv`: Contains restaurant details such as Name, Location, Cuisines, and Average Cost for two.
- `Zomato Restaurant reviews.csv`: Contains customer review texts, ratings, and timestamps.

---

## 🛠️ Tech Stack & Libraries Used
- **Language:** Python
- **Environment:** Google Colab / Jupyter Notebook
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning (Clustering):** Scikit-Learn (K-Means Clustering)
- **Natural Language Processing (NLP):** NLTK, TF-IDF Vectorizer, Random Forest / Logistic Regression

---

## 🚀 Key Features & Implementation Steps

### 1. Data Preprocessing & EDA
- Handled missing values, treated outliers, and encoded categorical variables.
- Performed Exploratory Data Analysis (EDA) to find the most popular cuisines and cost trends.

### 2. Sentiment Analysis Track (NLP)
- **Text Cleaning:** Removed stopwords, punctuation, and performed stemming/lemmatization on customer reviews.
- **Feature Extraction:** Converted text data into numerical format using TF-IDF Vectorizer.
- **Model Building:** Trained Machine Learning models (like Random Forest) to predict customer satisfaction with high accuracy.

### 3. Clustering Track (Unsupervised Learning)
- Used **K-Means Clustering** to segment restaurant locations.
- Applied the **Elbow Method** and **Silhouette Analysis** to determine the optimal number of clusters.
- Visualized the final clusters to identify high-density restaurant hubs.

---

## 🎯 Key Project Insights & Conclusion
- **Sentiment Trends:** The majority of reviews provided crucial indicators regarding food quality and service delivery times, achieving robust classification accuracy via NLP pipelines.
- **Business Hotspots:** Unsupervised clustering successfully mapped and segmented target zones, helping identify premium dining hubs versus value-driven market clusters based on average costs and spatial distribution.

---

## 📂 Repository Structure
- `Zomato_Restaurant_Insights_Capstone.ipynb` : The complete Google Colab Notebook containing the full source code, visualizations, and model outputs.
- `Zomato Restaurant names and Metadata.csv` : Raw metadata file for restaurant attributes.
- `Zomato Restaurant reviews.csv` : Customer review dataset for NLP tasks.
- `README.md` : Project documentation and summary.

---

## 👥 Project Declaration
- **Name:** Rupali Rathore
- **Course:** B.Tech (Information Technology)
- **Institution:** Rajasthan Technical University (RTU), Kota
