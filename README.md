# Movie Recommendation System

This is a content-based movie recommendation system built using **TF-IDF vectorization** and **sigmoid kernel** for similarity. The system recommends movies based on the plot description provided.

## Table of Contents
1. [Overview](#overview)
2. [How It Works](#how-it-works)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Dataset](#dataset)
6. [Technologies](#technologies)
7. [Contributing](#contributing)

## Overview
The goal of this project is to recommend movies similar to a given movie based on its plot overview. It uses the **Term Frequency-Inverse Document Frequency (TF-IDF)** technique to vectorize movie plots and then applies the **sigmoid kernel** to find similarities.

---

## How It Works
- The system first loads the dataset of movies and their corresponding metadata.
- It uses the `sklearn` library to vectorize the text descriptions of movies.
- After vectorization, the **sigmoid kernel** is applied to measure similarity between the vectorized descriptions.
- The system then returns the top 10 most similar movies based on the input movie.

---

## Installation
To install and run this project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Movie-Recommendation-System.git
    cd Movie-Recommendation-System
    ```

2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

---

## Usage
To get movie recommendations, simply run the `movie_recommender.py` file:

```bash
python movie_recommender.py
```


---
## Dataset
The datasets used in this project are from TMDB:
- **tmdb_5000_credits.csv**
- **tmdb_5000_movies.csv**

These datasets provide the credits and metadata for 5000 popular movies.

## Technologies
- **Pandas**: For data handling and preprocessing.
- **Scikit-learn**: For TF-IDF vectorization and sigmoid kernel.
- **Python**: For coding the recommendation logic.

## Contributing

Feel free to submit issues or pull requests. Any contributions are welcome! 


