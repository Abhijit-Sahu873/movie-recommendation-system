# 🎬 Movie Recommendation System

A content-based movie recommendation system built using Python and Machine Learning. This project recommends movies similar to a selected movie by analyzing genres, keywords, cast, crew, and overview information.

---

## 🚀 Features

* Content-based movie recommendation
* Uses cosine similarity for finding similar movies
* NLP preprocessing with tags and vectorization
* Recommendations based on:

  * Genres
  * Keywords
  * Cast
  * Crew
  * Movie overview
* Fast and lightweight implementation using Scikit-learn

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* NLTK (optional for stemming)
* Jupyter Notebook

---

## 📂 Dataset

This project uses the TMDB 5000 Movies Dataset.

Datasets:

* `tmdb_5000_movies.csv`
* `tmdb_5000_credits.csv`

You can download the dataset from:

* Kaggle: [https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

---

## ⚙️ How It Works

1. Load movie and credits datasets
2. Merge datasets using movie title
3. Select important features:

   * Overview
   * Genres
   * Keywords
   * Cast
   * Crew
4. Convert JSON-like text data into usable lists
5. Create tags by combining all important features
6. Apply text preprocessing
7. Convert text into vectors using `CountVectorizer`
8. Calculate similarity using `Cosine Similarity`
9. Recommend top similar movies

---

## 📸 Sample Recommendations

### Input:

```python
recommend("Avatar")
```

### Output:

```python
Titan A.E.
Aliens vs Predator: Requiem
Aliens
Falcon Rising
Independence Day
```

---

## ▶️ Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/movie-recommendation-system.git
cd movie-recommendation-system
```

### Install Dependencies

```bash
pip install pandas numpy scikit-learn notebook
```

### Run the Notebook

```bash
jupyter notebook
```

Open `Project.ipynb` and run all cells.

---

## 📁 Project Structure

```bash
movie-recommendation-system/
│
├── Project.ipynb
├── tmdb_5000_movies.csv
├── tmdb_5000_credits.csv
└── README.md
```

---

## 🧠 Machine Learning Concepts Used

* Natural Language Processing (NLP)
* Bag of Words (BoW)
* Vectorization
* Cosine Similarity
* Feature Engineering

---

## 🔮 Future Improvements

* Add Streamlit or Flask web app
* Use stemming and lemmatization
* Add poster and trailer support
* Deploy on Heroku or Render
* Improve recommendation accuracy using deep learning

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push to your branch
5. Create a Pull Request

