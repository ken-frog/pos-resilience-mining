# Mining User Perceptions of POS System Resilience

This repository contains the mining pipeline, scoring rubric, and visualizations used in the study:  
**"Mining User Perceptions of POS System Resilience: A Sentiment-Based Risk Profiling Approach"**

## 📊 Overview
We mined user reviews from the [Google Play Store Reviews Dataset](https://www.kaggle.com/datasets/prakharrathi25/google-play-store-reviews) to evaluate the resilience of four POS applications: Peddlr, Square, Shopify, and Loyverse.

## 🧠 Scoring Dimensions
- Sentiment Score (TextBlob)
- Topic Frequency (LDA)
- Rating Distribution
- Update Recency
- Developer Responsiveness

## 📁 Contents
- `scripts/`: Python scripts for mining, scoring, and visualization
- `figures/`: Radar chart and heatmap used in the manuscript
- `data/`: Sample review data (sanitized)
- `requirements.txt`: Python dependencies

## 📂 Reproducibility
To reproduce the figures:
```bash
pip install -r requirements.txt
python scripts/visualization.py
