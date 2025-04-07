# 🎬 Movie Recommendation System

A simple, content-based movie recommendation system built with **Streamlit**, leveraging movie similarity scores and the TMDB API to fetch posters. Deployed on **Hugging Face Spaces**.

🔗 **Live Demo**: [Try it on Hugging Face Spaces 🚀](https://huggingface.co/spaces/Indroneel/Movie_Recommendation_System)

---

## 📌 Features

- 🎥 Recommend movies similar to your selected favorite
- 📸 Fetch movie posters using the TMDB API
- 🚀 Live deployment on Hugging Face Spaces
- 🧠 Simple and effective content-based filtering
- 🧾 Clean, minimal Streamlit interface

---

## 🧠 How It Works

This app uses a **content-based filtering approach**. Here’s what happens behind the scenes:

1. Loads precomputed cosine similarity values between movies.
2. When a movie is selected, finds the top 5 most similar movies.
3. Fetches posters for the recommended movies from the TMDB API.
4. Displays movie titles and their posters in a clean UI.

---

## 📁 Project Structure

