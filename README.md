# 🎬 Movie Analysis with Python and Pandas

This project explores IMDb movie data using Python and pandas. It analyzes lead actors and review patterns, then identifies critic and audience favorites.

## 📁 Project structure
- `DS-in-Python-Movie-Assignment.ipynb` (or your notebook’s actual name)
- `README.md`

## 🚀 Features
- Filters movies by lead actors (Meryl Streep, Leonardo DiCaprio, Brad Pitt)
- Combines and groups data for review analysis
- Calculates average critic and user reviews

## 🛠 Technologies
- Python, pandas, Jupyter Notebook (or VS Code), GitHub Desktop

## 📦 How to run
1. Clone this repository.
2. Open the notebook in Jupyter or VS Code.
3. Run cells sequentially to reproduce results.

## 📸 Sample code
```python
grouped_actors = Combined.groupby('actor_1_name')
mean_reviews = grouped_actors[['num_critic_for_reviews', 'num_user_for_reviews']].mean().reset_index()

