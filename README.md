# 🎵 Content-Based Music Recommendation System

While listening to music, it’s natural to want to find similar songs to the one currently playing.  
The most common way this is done is through **Collaborative Filtering**, which looks for:

* User–item interaction data  
* User IDs  
* Item IDs  
* Ratings or implicit feedback  
* Enough overlapping user history  

These features don’t usually have anything to do with the *actual music* being listened to.  
In this project, we take a **different approach** — we use **Content-Based Filtering** to recommend songs **based on their audio features**.

---

## 🎯 Aim
This project recommends **5 songs** from the **same genre** as the currently playing track using **content-based filtering**.

---

## 📂 Dataset
The dataset used is **GTZAN**, a popular dataset for music classification tasks.  
It contains **10,000 audio tracks** across **10 different genres**.  

📥 [Download GTZAN Dataset](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification)

---

## ⚙️ Approach
1. **Feature Extraction** – Extract audio features (e.g., MFCCs, tempo, spectral features) from each track.
2. **Cosine Similarity** – Measure similarity between the current song and other songs in the dataset.
3. **K-Means Clustering** – Group songs by similarity and genre.
4. **Recommendation** – Select the 5 most similar songs within the same genre.

---

## 🛠 Tech Stack
- **Python**
- **Pandas, NumPy**
- **Scikit-learn** (K-Means, cosine similarity)
- **Librosa** (audio feature extraction)
- **Jupyter Notebook**

---

## 📊 Example Output



