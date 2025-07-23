# 📺 YouTube Trending Video Analysis

This project analyzes over **200,000 trending YouTube videos** from the U.S. region to uncover the key factors that influence content virality. It explores trends across video categories, upload timing, user engagement, and metadata — helping content creators, marketers, and analysts understand what makes a video trend.

---

## 📌 Project Objective

- Identify key attributes and patterns that cause a video to trend
- Understand how views, likes, comments, and tags affect video performance
- Visualize trends by category, region, and upload time
- Provide actionable insights to optimize content strategy

---

## 🗃️ Dataset

- **Source:** [Kaggle - YouTube Trending Video Dataset](https://www.kaggle.com/datasets/datasnaek/youtube-new)
- **Region:** United States
- **Size:** ~200,000 video records
- **Features include:**
  - Video ID, Title, Channel Title
  - Publish Time
  - Views, Likes, Dislikes, Comment Count
  - Tags and Description
  - Category ID (mapped to YouTube video categories)
  - Flags for Ratings Disabled, Comments Disabled, and Video Removed/Error

---

## 🧰 Tools & Technologies Used

- **Data Analysis & Cleaning:** Python, Pandas, NumPy
- **Data Visualization:** Seaborn, Matplotlib, Plotly
- **Querying & Transformation:** SQL
- **Notebook Environment:** Jupyter Notebook
- **Version Control:** Git, GitHub

---

## 🔍 Key Insights

- **Music**, **Entertainment**, and **How-to** videos are the most common trending categories
- Uploads between **6 PM – 9 PM** have a higher chance of trending
- Videos with higher **engagement (likes/comments ratio)** tend to stay in trending longer
- Use of **informative tags** is strongly correlated with increased visibility
- Top 10 channels contribute to nearly **30%** of total trending videos

---

## 📊 Visualizations

- Bar charts for trending video count by **category** and **channel**
- Heatmaps showing engagement by **time of day** and **day of week**
- Scatter plots and histograms of views, likes, and comment count
- Correlation matrix of engagement metrics (views, likes, dislikes, comments)
- Word clouds from video titles and tags

---

## 📂 Project Structure
├── data/
│ └── USvideos.csv
├── notebooks/
│ └── YouTube_Trending_Analysis.ipynb
├── outputs/
│ └── charts/ (visual outputs)
├── README.md
├── requirements.txt


---

## 🚀 Getting Started

1. Clone the repository:
```bash
git clone https://github.com/your-username/youtube-trending-analysis.git
cd youtube-trending-analysis

pip install -r requirements.txt

jupyter notebook notebooks/YouTube_Trending_Analysis.ipynb
