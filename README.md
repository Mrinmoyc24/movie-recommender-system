# 🎬 Movie Recommender System with Python

**🎯 Personalized Movie Recommendations using Collaborative Filtering in Python (MovieLens Dataset).**

---

## 📌 Description  
This project presents a **Movie Recommender System** built in Python using the **MovieLens dataset**, a benchmark dataset in recommendation system research. The goal is to predict and recommend movies to users based on their historical ratings and viewing patterns.  

The system applies **collaborative filtering techniques** to identify relationships between users and movies. Two approaches are demonstrated:  

1. **Item-based collaborative filtering** – recommends movies similar to a given movie by analyzing rating correlations.  
2. **User-based collaborative filtering** – recommends movies based on similarity between users’ rating behaviors.  

The project includes:  
- **Exploratory Data Analysis (EDA):** rating distribution, popularity trends, correlations.  
- **Recommendation Engine:** correlation-based suggestions.  
- **Output Examples:** recommendations for *Star Wars (1977)* and other titles.  

Built with **pandas**, **NumPy**, **matplotlib**, and **seaborn**, this project is designed as both an **educational exercise** and a **scalable framework** that can be extended to real-world applications.  

---

## 📂 Dataset  
This project uses the **MovieLens 100k dataset**:  

- `u.data` → user–movie ratings (userID, movieID, rating, timestamp).  
- `u.item` → movie metadata (movieID, title, genre, release year, etc.).  
- `Movie_Id_Titles` → mapping of `movieID` to movie titles.  

Source: [MovieLens Dataset](https://grouplens.org/datasets/movielens/)  

---

## ⚙️ Installation  

Clone this repository and install requirements:  

```bash
git clone https://github.com/your-username/movie-recommender-system-python.git
cd movie-recommender-system-python
pip install -r requirements.txt
