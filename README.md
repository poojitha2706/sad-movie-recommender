# 🎬 How Sad Are You? — Mood-Based Movie Recommender

> *"Do sadder movies actually rate higher? And can data tell you what to watch based on your mood?"*

🔗 **[Try it Live](https://poojitha2706.github.io/sad-movie-recommender/sad-movies.html)**

---

## 📌 Project Overview

An interactive mood-based movie recommender built on real IMDb data. Drag a slider from 1–5 based on how you're feeling, and get personalized movie recommendations — from feel-good adventures to utterly devastating dramas.

But there's a data story hidden inside: **the sadder the movies, the higher they rate on IMDb.** This project visualizes that finding in real time as you interact with it.

Submitted as part of the **Codédex Data Science / Data Analysis Monthly Challenge** — *"Use data to tell a story about something you love."*

---

## ❓ Questions Explored

- Do sadder movies genuinely rate higher on IMDb?
- Can we classify movies into emotional tiers using genre data?
- What does crowd-sourced sentiment (Reddit) say about emotionally intense films?

---

## 💡 The Data Insight

After categorizing the IMDb Top 1000 movies into 5 sadness tiers by genre:

| Tier | Mood | Avg IMDb Rating |
|------|------|----------------|
| 1 | 😊 Feeling Good | 8.1 |
| 2 | 🙂 Pretty Okay | 8.2 |
| 3 | 😐 Kinda Meh | 8.3 |
| 4 | 😔 Pretty Sad | 8.4 |
| 5 | 💀 Completely Devastated | 8.6 |

**The sadder the movie, the higher it rates — consistently, across all tiers.**

---

## ✨ Features

- 🎚️ **Mood slider** — 5 emotional levels with dynamic color themes
- 🎬 **Real movie posters** — loaded directly from IMDb
- 📋 **Movie detail modal** — overview, director, IMDb rating, and Reddit reactions
- 📊 **Live bar chart** — reveals the sadness vs rating insight as you interact
- 💡 **Data insight callout** — changes per mood tier

---

## 🗂️ Dataset

- **Source:** IMDb Top 1000 Movies — Kaggle
- **Size:** 1000 movies with ratings, genres, posters, overviews, directors
- **Sadness tiers assigned by genre:**
  - Tier 5: War, History
  - Tier 4: Romance, Biography
  - Tier 3: Drama
  - Tier 2: Comedy-Drama
  - Tier 1: Action, Adventure, Sci-Fi

---

## 🛠️ Built With

- **HTML / CSS / JavaScript** — no frameworks, fully standalone
- **IMDb Top 1000 Dataset** — via Kaggle
- **Python + Pandas** — for data processing and tier classification

---

## 🚀 How to Run

Simply open `sad-movies.html` in any browser — no installation needed.

Or visit the live version:
👉 **https://poojitha2706.github.io/sad-movie-recommender/sad-movies.html**

---

## 📁 File Structure

```
sad-movie-recommender/
│
├── sad-movies.html    # Full app — data, logic, and UI in one file
└── README.md          # You are here!
```

---

## 🔮 Future Plans

- Live Reddit sentiment scraping via Python + PRAW
- User accounts + personal watchlist
- Expand beyond sad movies — horror, comfort films, hype movies
- Deploy as a full web app

---

## 👤 Author

Made with 🎬 for the Codédex Monthly Challenge
*Topic: Can data tell you what movie to watch based on how sad you are?*
