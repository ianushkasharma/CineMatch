# 📽️ CineMatch – Movie Recommendation System

Welcome to **CineMatch**, your intelligent movie companion!  
This web app recommends movies based on your favorite titles using content-based filtering powered by NLP and cosine similarity.

---

### 🔗 [Live Demo](https://cinematch-app.streamlit.app/)

---

## 📌 Features

- 🎬 **Movie Recommendations** based on similarity
- 🧠 **Content-based filtering** using tags (genre, cast, crew, keywords)
- ⚡ **Fast search** with preprocessed `.pkl` files for performance
- 🌐 **Deployed on Streamlit Cloud**
- 📁 **Built with Python, Pandas, Scikit-learn, and Streamlit**

---

## 📷 Screenshots

<img width="600" height="865" alt="screenshot1" src="https://github.com/user-attachments/assets/83e23b6e-e63f-46b7-b022-166b2c9bc584" />
<img width="600" height="868" alt="screenshot2" src="https://github.com/user-attachments/assets/bbfe59da-d5dd-48e5-9de2-e7a7ddab50dd" />

---

## 🚀 How It Works

1. Select your favorite movie from the dropdown
2. Click **Recommend**
3. Instantly get 5 similar movie suggestions with posters!

---

## 🛠️ Tech Stack

| Tool           | Purpose                         |
|----------------|----------------------------------|
| `Pandas`       | Data processing                  |
| `scikit-learn` | TF-IDF + Cosine Similarity       |
| `Pickle`       | Model and data serialization     |
| `Streamlit`    | Web UI                           |
| `TMDB API`     | Fetching movie posters           |

---

## 🧠 How Recommendations Work

- Data from TMDB (movies + credits) is merged
- Tags are created using genres, cast, keywords, director
- Tags are vectorized using `TfidfVectorizer`
- Similarity is computed using **cosine similarity**
- Top 5 closest vectors (movies) are recommended

---

## 🧪 Run Locally

```bash
git clone https://github.com/ianushkasharma/CineMatch.git
cd CineMatch
pip install -r requirements.txt
streamlit run app.py
```

## 📬 Contact
Anushka Sharma
🔗 [LinkedIn](https://www.linkedin.com/in/ianushkasharma/)
🐙 [GitHub](https://github.com/ianushkasharma)
