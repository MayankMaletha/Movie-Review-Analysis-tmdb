# 🎬 Movie Review Analysis using TMDB API

This project fetches and analyzes top-rated movie data from [The Movie Database (TMDB)](https://www.themoviedb.org/). It extracts detailed movie information including titles, overviews, ratings, and genre mappings from the TMDB API.

---

## 📦 Project Highlights

- 🔄 Extracts data from **471 pages** of the TMDB Top Rated Movies API
- 🧠 Maps `genre_ids` to actual **genre names** using the TMDB Genre API
- 🧾 Creates a clean and structured **DataFrame** with the following columns:
  - `id`
  - `title`
  - `overview` (used as review)
  - `rating`
  - `genre_names`
- 📊 Data ready for machine learning and natural language processing tasks

---

## 🔮 Future Work

- ✨ **Text Preprocessing** for `overview` field (tokenization, stopwords removal, stemming, etc.)
- 🤖 **Genre Classification Model** using `overview` text
- 📈 Data visualization (rating distributions, genre counts)
- 🧠 Model deployment for movie genre prediction

---

## 🔗 APIs Used

- [TMDB Top Rated Movies](https://api.themoviedb.org/3/movie/top_rated)
- [TMDB Genre List](https://api.themoviedb.org/3/genre/movie/list)

---
