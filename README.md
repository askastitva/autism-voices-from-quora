# autism-voices-from-quora

# 🧩 Mental Health Support for Autism

A data-driven exploration of Autism Spectrum Disorder (ASD) using real-world narratives from Quora, built as part of our Information Retrieval & Extraction (IRE) course project at IIITM Gwalior.

## 👥 Team
- Apoorv Jain (2021-IMT-015)  
- Astitva Kamble (2021-IMT-048)  
- Yashveer (2021-IMT-116)

## 📌 Objective
To understand the lived experiences of individuals with autism through:
- Topic Modeling using **LDA**
- Sentiment & Stance Analysis using **TextBlob**

## 🗃️ Data Collection
- Source: [Quora](https://www.quora.com)
- Tool: `webscraper.io`
- 30+ autism-related keywords used
- ~3,000 high-engagement Q&A threads

## 🔍 Techniques
- **Vectorization:** `CountVectorizer` (with stopword removal)
- **Topic Modeling:** LDA (`n_components=5`)
- **Sentiment Analysis:** TextBlob (polarity & subjectivity)
- **Stance Classification:** Based on polarity thresholds

## 🧠 Key Insights
- 🔹 Early signs, parental therapy, social anxiety, and empathy emerged as major themes/topics
- 🔹 77% of comments were neutral, 19% supportive, 3% against
- 🔹 Upvotes ranged from 0 to 9,000+, showing varied community engagement

## 🚀 Future Scope
- Dynamic topic models (BERTopic, DTM)
- Emotion/stance classification with LLMs
- Cross-platform comparison (Reddit, forums)

---

📁 *Academic project | For educational use only*

