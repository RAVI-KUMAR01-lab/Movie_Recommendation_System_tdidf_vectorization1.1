# Movie_Recommendation_System_tdidf_vectorization1.1
🎬 Problem: Too many movies, hard to choose   💡 Solution: ML-powered recommender using TF-IDF + cosine similarity


💡 **Solution:** Built an ML-powered recommendation system using TF-IDF and cosine similarity to deliver fast, personalized movie suggestions via a Streamlit web app.

---

## ⚙️ Approach

* Cleaned and processed movie metadata
* Combined features like genres, director, and language
* Converted text data into numerical vectors using **TF-IDF**
* Calculated similarity using **cosine similarity**
* Built an interactive UI with **Streamlit**

---

## 🚀 Features

* 🎯 Recommends top 5 similar movies instantly
* ⚡ Fast and efficient similarity computation
* 🧠 Uses Machine Learning (not random suggestions)
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
4. Recommend most similar movies

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

* Processes thousands of movies efficiently
* Generates relevant recommendations instantly
* Demonstrates real-world use of ML techniques

---

## 🔮 Future Improvements

* Add movie overview (NLP-based recommendations)
* Use collaborative filtering
* Add posters using API
* Improve UI/UX

---

## 🧠 Key Learnings

* Feature engineering from text data
* TF-IDF vectorization
* Similarity-based recommendation systems
* Building and deploying ML apps

---

## 📌 Project Type

Content-Based Recommendation System (Machine Learning)


