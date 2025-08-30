# 💬 Public Opinion Analysis on Digital Transformation  
_Text Mining Project (2025)_  

## 📌 Project Overview  
This project explores **public opinion on digital transformation in Indonesia** by scraping comments from YouTube videos.  
The goal is to extract insights about how people perceive digital transformation using **unsupervised learning techniques**.  

Two main approaches were applied:  
1. **Clustering (K-Means)** → to group similar comments and identify audience segments.  
2. **Topic Modeling (LDA)** → to extract main discussion topics from the comments.  

---

## ⚙️ Tech Stack  
- Python  
- Scikit-learn  
- Gensim  
- Pandas & NumPy  
- TF-IDF & Word2Vec (text representation)  
- Matplotlib & Seaborn (visualization)  

---

## 🗂️ Dataset  
- Comments scraped from **YouTube videos** discussing digital transformation in Indonesia.  
- Preprocessing steps included:  
  - Text cleansing  
  - Tokenization  
  - Stopword removal  
  - Stemming/Lemmatization  

---

## 🔬 Methodology  
1. **Data Collection** → Web scraping of YouTube comments.  
2. **Text Preprocessing** → Cleansing, tokenization, stopword removal, stemming/lemmatization.  
3. **Vectorization** → TF-IDF and Word2Vec for feature representation.  
4. **Clustering (K-Means)** → Tested multiple k values, used **silhouette score** to determine optimal clusters.  
5. **Topic Modeling (LDA)** → Extracted discussion themes to complement clustering insights.  
6. **Persona Analysis** → Interpreted clusters and topics to understand audience perspectives.  

---

## 📊 Results  
- **Clustering:** Identified distinct audience segments.  
- **Topic Modeling:** Extracted key topics related to digital transformation.  
- **Comparison:** Clustering provided clearer audience segmentation, while LDA highlighted broader discussion themes.  

## 📎 Repository Structure  
