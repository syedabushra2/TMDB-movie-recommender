# Movie Recommender System 🎬 - AI4ALL Final Project

## 📌 Project Description

This project implements a **content-based movie recommender system** using Python and pandas. The system recommends movies similar to a selected title by analyzing the movie's metadata such as keywords, cast, genres, and crew. It's a simple and effective way to showcase how machine learning techniques can be used to build personalized recommendation engines.

## 🚀 Purpose and Objectives

- Demonstrate understanding of recommender system algorithms
- Apply pandas and cosine similarity for content-based filtering
- Build an interactive experience for exploring movie suggestions

## 🧠 Project Details

- **Technologies Used**: Python, Pandas, Scikit-learn, Google Colab
- **Dataset**: [TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
- **Key Features**:
  - Content-based filtering
  - Feature engineering using genres, keywords, and cast
  - Cosine similarity score calculation
  - Easy-to-use recommendation function

## 🛠️ Installation and Usage Instructions

> You can run this project directly in Google Colab — no local installation required!

1. Click here to open in Colab:  
   [▶️ Launch Notebook](https://colab.research.google.com/drive/11RvBgsKIU1AAcUD7O9c4jBxrXL02O0Zv)

2. Run all the cells in order.

3. When prompted, enter a movie name (e.g., `"Avatar"`) to get recommendations.

> 💡 Tip: You can also modify the dataset and re-train with your own movie data!

## 💻 Code Example

```python
get_recommendation("The Dark Knight Rises")
Output:
Top 10 similar movies:
1. The Dark Knight
2. Batman Begins
3. Batman v Superman: Dawn of Justice
...
📑 API / Functions
get_recommendation(movie_name)
Input: A string with the movie title

Output: A list of 10 similar movies

🌍 Contribution Guidelines
Pull requests are welcome! If you have suggestions for improvements, feel free to fork this repo and submit a PR.

Please follow these steps:

Open an issue to discuss the change

Make your changes in a separate branch

Submit a pull request with a clear explanation

🙏 Acknowledgments and References
TMDB Dataset

Inspired by content-based recommendation concepts from ML courses

Thanks to AI4ALL for this project showcase opportunity
