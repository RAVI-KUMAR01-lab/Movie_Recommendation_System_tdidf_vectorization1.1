# 🎬 Movie Recommendation System

🚨 **Problem:** Too many movies → difficult to find relevant content quickly
💡 **Solution:** Developed an end-to-end ML-based movie recommendation system using TF-IDF vectorization and cosine similarity, enabling fast, personalized movie suggestions through a Streamlit web application. **


---

## ⚙️ Approach

* Cleaned and preprocessed movie metadata
* Combined features: **genres, director, language**
* Converted text into numerical vectors using **TF-IDF**
* Computed similarity using **cosine similarity**
* Built an interactive UI using **Streamlit**

---

## 🚀 Features

* 🎯 Recommends **top 5 similar movies instantly**
* ⚡ Fast and efficient similarity computation
* 🧠 ML-based recommendation logic (not random)
* 🎨 Simple and interactive web interface

---

## 🛠 Tech Stack

* Python
* Pandas
* Scikit-learn
* Streamlit

---

## 📊 How It Works

1. Convert movie features into text tags
2. Apply TF-IDF vectorization
3. Compute cosine similarity
4. Return top 5 most similar movies

---

## ▶️ Run Locally

```bash
pip install -r requirements.txt
python preprocess.py
python model.py
python -m streamlit run app.py
```

---

## 🎯 Results

* Handles thousands of movies efficiently
* Generates relevant recommendations instantly
* Demonstrates real-world application of ML techniques

---

## 🔮 Future Improvements

* Add movie overview (NLP-based recommendations)
* Implement collaborative filtering
* Integrate movie posters using API
* Enhance UI/UX

---

## 🧠 Key Learnings

* Feature engineering from text data
* TF-IDF vectorization
* Similarity-based recommendation systems
* End-to-end ML project development

---

## 📌 Project Type

**Content-Based Recommendation System (Machine Learning)**

---


