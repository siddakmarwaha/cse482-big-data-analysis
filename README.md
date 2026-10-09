# CSE 482 — Big Data Analysis Coursework

![Python](https://img.shields.io/badge/python-3.9%2B-blue) ![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

Assignments on large-scale data processing and mining. The course project (news recommendation on MIND) lives in its own repository: [mind-news-recommendation](../mind-news-recommendation).

**Course:** CSE 482 — Big Data Analysis  
**Term:** Spring 2025  
**Institution:** Michigan State University

## Contents

- [`notebooks/misra_gries_heavy_hitters.ipynb`](notebooks/misra_gries_heavy_hitters.ipynb) — Misra–Gries frequent-items streaming algorithm on Wikipedia edit logs
- [`notebooks/stock_returns_pca.ipynb`](notebooks/stock_returns_pca.ipynb) — PCA of daily returns for nine stocks across tech, banking and autos
- [`notebooks/activity_recognition.ipynb`](notebooks/activity_recognition.ipynb) — accelerometer-based activity classification (logistic regression)
- [`notebooks/mongodb_bestbuy_queries.ipynb`](notebooks/mongodb_bestbuy_queries.ipynb) — loading and querying product data in MongoDB with PyMongo
- [`notebooks/twitter_search_api.ipynb`](notebooks/twitter_search_api.ipynb) — collecting tweets with Tweepy
- [`notebooks/reddit_api_collection.ipynb`](notebooks/reddit_api_collection.ipynb) — collecting posts with PRAW

## Repository Structure

```text
cse482-big-data-analysis/
├── notebooks/
│   ├── activity_recognition.ipynb
│   ├── misra_gries_heavy_hitters.ipynb
│   ├── mongodb_bestbuy_queries.ipynb
│   ├── reddit_api_collection.ipynb
│   ├── stock_returns_pca.ipynb
│   └── twitter_search_api.ipynb
├── .env.example
├── LICENSE
├── README.md
└── requirements.txt
```

## Tech Stack

Python, pandas, scikit-learn, PyMongo, Tweepy, PRAW

## Getting Started

```bash
git clone https://github.com/siddakmarwaha/cse482-big-data-analysis.git
cd cse482-big-data-analysis
python -m venv .venv && source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter lab
```

## Data

API credentials are read from environment variables (see `.env.example`). Course datasets (stock CSVs, activity logs, `wiki_edit2.txt`, `bestbuy.csv`) are not committed. Outputs of the social-media notebooks are cleared.

> **Academic integrity:** This repository contains my own submitted work for a university course and is shared as a portfolio sample. Assignment prompts and starter code belong to the course instructors. Current students should not copy this work.

## Author

**Siddak Marwaha**

## License

Code in this repository is released under the [MIT License](LICENSE). Course-provided prompts and materials remain the property of their authors.
