# Search_engine_for_ecommerce
A Recommendation System built using the Amazon product review dataset, implementing rating-based, content-based, collaborative filtering, and hybrid recommendation approaches using Python and machine learning techniques.
# 📌 Project Overview
This project demonstrates how recommendation systems work using only one data modality (text + ratings). It focuses on understanding user preferences and product similarities to generate personalized product recommendations.

The system includes:

Rating-based recommendations

Content-based filtering using TF-IDF & cosine similarity

User-based collaborative filtering

Hybrid recommendations combining multiple techniques

# 📁 Project Structure
```
├── data/
│   └── amazon.csv
├── codes/
├── sample recommendations/
└── README.md
```
# 🧠 Recommendation Approaches
## 1️⃣ Rating-Based Recommendation

Computes average ratings per product

Recommends top-rated products globally

## 2️⃣ Content-Based Filtering

Uses TF-IDF Vectorization on product tags

Computes cosine similarity between products

Recommends similar products based on item content

## 3️⃣ Collaborative Filtering

Builds a user–item interaction matrix

Computes user-user similarity using cosine similarity

Recommends products liked by similar users

## 4️⃣ Hybrid Recommendation System

Combines:

Content-based recommendations

Collaborative filtering results

Removes duplicates

Sorts recommendations by rating

# 📊 Sample Output

Top-rated product recommendations

Similar product suggestions based on content

Personalized recommendations for a given user

Hybrid recommendations with images, ratings, and reviews

# 👤 Author
Himanshu Kumar
---
🏫 NIT Trichy
