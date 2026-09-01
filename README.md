# 🎬 CineMatch - Movie Recommender System
## 🚀 Live Demo
https://alenan-movie-recommender-system-cxfl62kafhl67jt4bennnc.streamlit.app/

A content-based movie recommendation system built with Python, Machine Learning, and Streamlit. This application suggests similar movies based on user selection using cosine similarity derived from movie metadata (genres, keywords, cast, crew, and overview).

---

## ✨ Features
- **Interactive Web Interface:** Built using Streamlit for a smooth and responsive user experience.
- **Smart Recommendations:** Select any movie to get top 5 personalized movie suggestions instantly.
- **Poster Integration:** Fetches and displays movie posters dynamically using the TMDB API.

---

## 🛠️ Tech Stack & Libraries
- **Language:** Python
- **Frontend / UI:** Streamlit
- **Data Processing & ML:** Pandas, NumPy, Scikit-learn (Cosine Similarity)
- **Deployment:** Streamlit Community Cloud & GitHub Git LFS

---

## 📂 Project Structure
```text
ML-realworld-project-1/
│
├── app.py                  # Main Streamlit application file
├── movie_dict.pkl          # Serialized movie metadata dictionary
├── similarity.pkl          # Pre-calculated cosine similarity matrix (tracked via Git LFS)
├── requirements.txt        # Project dependencies
└── README.md               # Project documentation

⚙️ Installation & Running Locally
Follow these steps to run the project locally on your machine:

Clone the repository:
git clone [https://github.com/AbdulHanan0812/Alenan-movie-recommender-system.git](https://github.com/AbdulHanan0812/Alenan-movie-recommender-system.git)
cd Alenan-movie-recommender-system

Create and activate a virtual environment:

python -m venv .venv
# On Windows:
.venv\Scripts\Activate.ps1


Install dependencies:
pip install -r requirements.txt

Run the Streamlit app:

streamlit run app.py

🚀 Live Demo
You can access the live web application here:
https://alenan-movie-recommender-system-cxfl62kafhl67jt4bennnc.streamlit.app/

👨‍💻 Author
Abdul Hanan Mumir

Undergraduate Student in Artificial Intelligence | Python & Backend Enthusiast
