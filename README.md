# Vibe Matcher - Fashion Recommendation System

AI-powered recommendation prototype that matches user vibe queries to fashion products using text embeddings and cosine similarity.

## 🎯 Project Overview

This project was built for the Nexora AI Internship assignment. It demonstrates:
- Text embedding generation using Sentence Transformers
- Vector similarity search with cosine similarity
- Query evaluation with metrics and latency analysis
- Production-ready architectural thinking

## 🚀 Features

- **Smart Matching:** Converts vibe queries ("energetic urban chic") into product recommendations
- **Fast Performance:** Average query latency < 0.015 seconds
- **Evaluation Metrics:** Tracks similarity scores and match quality
- **Fallback Handling:** Graceful degradation for weak matches

## 📊 Results

- **3 test queries** evaluated
- **2/3 queries** achieved "good match" (score ≥ 0.7)
- **Average similarity score:** 0.727
- **Total products:** 10 fashion items with rich descriptions

## 🛠️ Technologies Used

- **Python 3.x**
- **Sentence Transformers** (all-MiniLM-L6-v2) - Free embedding model
- **scikit-learn** - Cosine similarity computation
- **Pandas** - Data manipulation
- **Matplotlib** - Latency visualization
- **NumPy** - Vector operations

## 📁 Project Structure

vibe-matcher-nexora/

├── vibe_matcher.ipynb 

├── products.csv 

├── evaluation_results.csv

├── product_embeddings.npy

└── README.md

