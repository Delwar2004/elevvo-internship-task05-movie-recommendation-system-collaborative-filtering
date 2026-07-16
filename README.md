# 🎬 Movie Recommendation System using Collaborative Filtering & Matrix Factorization

<p align="center">

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikit-learn)
![Surprise](https://img.shields.io/badge/Surprise-Recommender-red?style=for-the-badge)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-black?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-blue?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)

</p>

---

# 📌 Project Overview

Recommendation systems power modern digital platforms such as **Netflix, Amazon, Spotify, YouTube, and Disney+** by providing personalized content recommendations.

This project develops an **end-to-end Movie Recommendation System** using the **MovieLens Latest-Small Dataset**, implementing multiple recommendation strategies ranging from simple popularity-based recommendations to advanced collaborative filtering and matrix factorization techniques.

The objective is to evaluate different recommendation algorithms under a unified evaluation framework and determine the most effective approach for personalized movie recommendations.

---

# 🎯 Objectives

- Build a complete recommendation pipeline
- Analyze user-item interactions
- Implement multiple recommendation algorithms
- Compare personalized vs non-personalized recommendations
- Evaluate recommendation quality using industry-standard metrics
- Identify the best-performing recommendation strategy

---

# 📂 Dataset

**Dataset:** MovieLens Latest-Small

Dataset Statistics

| Feature | Value |
|----------|-------|
| Users | 610 |
| Movies | 9,742 |
| Ratings | 100,836 |
| Tags | 3,683 |
| Rating Scale | 0.5 – 5.0 |

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Surprise Library
- SciPy

---

# 🚀 Project Pipeline

```
MovieLens Dataset
        │
        ▼
Dataset Audit
        │
        ▼
Exploratory Data Analysis
        │
        ▼
User–Item Matrix Construction
        │
        ▼
Popularity-Based Recommendation
        │
        ▼
User-Based Collaborative Filtering
        │
        ▼
Item-Based Collaborative Filtering
        │
        ▼
Matrix Factorization (SVD)
        │
        ▼
RMSE Evaluation
        │
        ▼
Precision@10 Evaluation
        │
        ▼
Comparative Performance Analysis
```

---

# 📊 Exploratory Data Analysis

The dataset was thoroughly explored before model development.

The analysis includes:

- Distribution of movie ratings
- User activity analysis
- Movie popularity analysis
- User–Item Matrix visualization
- Sparsity analysis
- Rating behavior analysis

---

# 📸 Project Visualizations

## Distribution of Movie Ratings

![](images/Distribution%20of%20Movie%20Ratings.png)

---

## Distribution of Ratings per User

![](images/Distribution%20of%20Ratings%20per%20User.png)

---

## Top 20 Most Rated Movies

![](images/Top%2020%20Most%20Rated%20Movies.png)

---

## Popularity-Based Recommendation

![](images/Top%2010%20Movies%20Recommended%20by%20Popularity%20Baseline.png)

---

## User-Based Collaborative Filtering Performance

![](images/Distribution%20of%20Precision@10%20Across%20Users.png)

---

## Item-Based Collaborative Filtering Performance

![](images/Precision@10%20Distribution%20(Item-Based%20CF).png)

---

## Matrix Factorization (SVD)

![](images/Precision@10%20Distribution%20(SVD).png)

---

# 🤖 Implemented Recommendation Models

## 1️⃣ Popularity-Based Recommendation

A simple non-personalized recommender that suggests globally popular movies based on average ratings and rating counts.

---

## 2️⃣ User-Based Collaborative Filtering

Recommends movies by identifying users with similar historical preferences using cosine similarity.

---

## 3️⃣ Item-Based Collaborative Filtering

Recommends movies based on similarities between movies instead of similarities between users.

---

## 4️⃣ Matrix Factorization (SVD)

Learns latent representations of users and movies, enabling accurate prediction of unseen ratings.

---

# 📈 Model Evaluation

Two complementary evaluation metrics were used.

### RMSE

Measures rating prediction accuracy.

Lower values indicate better prediction performance.

---

### Precision@10

Measures recommendation relevance.

Higher values indicate better personalized recommendations.

---

# 🏆 Experimental Results

| Model | RMSE | Precision@10 |
|--------|------:|-------------:|
| Popularity Baseline | — | **0.0363** |
| User-Based CF | **0.9823** | 🥇 **0.3672** |
| Item-Based CF | **0.9800** | **0.2164** |
| Matrix Factorization (SVD) | 🥇 **0.8807** | **0.3266** |

---

# 📊 RMSE Comparison

![](images/RMSE%20Comparison%20of%20Recommendation%20Models.png)

---

# 📊 Precision@10 Comparison

![](images/Precision@10%20Comparison%20of%20Recommendation%20Models.png)

---

# 🔍 Key Findings

- Personalized recommendation models significantly outperformed the popularity baseline.
- User-Based Collaborative Filtering achieved the highest recommendation relevance.
- Matrix Factorization (SVD) achieved the best rating prediction accuracy.
- Lower RMSE does not necessarily imply better Top-K recommendation quality.
- Precision@10 proved to be a more informative metric for recommendation effectiveness.

---

# 💡 Practical Insights

### Best Model for Rating Prediction

✅ Matrix Factorization (SVD)

---

### Best Model for Personalized Recommendation

✅ User-Based Collaborative Filtering

---

### Best Baseline Model

✅ Popularity-Based Recommendation

---

# 📁 Repository Structure

```
movie-recommendation-system/

│── data/

│── images/

│── notebook/

│── README.md

│── requirements.txt

│── .gitignore
```

---

# 🔮 Future Improvements

- Hybrid Recommendation Systems
- Neural Collaborative Filtering
- Deep Learning-based Recommenders
- Implicit Feedback Modeling
- Cold Start Handling
- Hyperparameter Optimization
- Cross Validation
- MovieLens 1M & 20M Evaluation
- Diversity & Novelty Metrics
- Recall@K, MAP@K, NDCG

---

# 🎓 Internship Information

**Internship Program**

**Elevvo ML Internship**

Task 05 — Movie Recommendation System

---

# 👨‍💻 Author

**Md Delwar Husen**

Machine Learning • Deep Learning • Computer Vision • NLP

If you found this project useful, consider giving it a ⭐.
