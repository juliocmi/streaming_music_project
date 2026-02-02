# 🎼 Music Streaming Analytics - Análisis de Comportamiento de Usuarios

## 📌 Executive Summary

**General Objective**
Analyze music streaming data from the **Y.Music platform** to understand user behavior and optimize product and marketing strategies.

**Specific Objectives**

- Identify the most popular genres and artists
- Analyze usage patterns by time slot and day of the week
- Study retention and listening frequency
- Detecting temporary trends in music consumption

## 🧠 Context and motivation

Music streaming platforms rely heavily on data analytics to improve user experience, recommendation systems, and customer retention. This project simulates a real-world business scenario where data-driven insights are essential for optimizing digital products and user engagement strategies.

## 📊 Dataset

Source: Real dataset of Y.Music streaming platform.

Records: +65000 play music

Period: Dec 2023

Main Variables:

- userID
- Track
- artist
- genre
- City
- Time
- Day

## 🔬 Methodology

- Data cleaning and pre-processing
- Exploratory Data Analysis (EDA)
- Temporal analysis and user segmentation
- Business-oriented interpretation

## 🛠️ Technologies and Tools

- Language: Python
- Frameworks: Pandas, NumPy
- Environment: Jupyter Notebook, VsCode
- Version control: Git & GitHub

## 📈 Exploratory Data Analysis (EDA)

- Pop is the most streamed genre for the two cities (Springfield and Shellbyville)
- Springfield is the city with most streamed music with +42000 play tracks
- Highly active users are in Friday
- Significant differences in listening behavior across countries

## 📊 Results & Key Insights

- Time-based listening patterns can be leveraged to optimize music release strategies
- Genre and behavior-based segmentation enables more effective personalized campaigns
- Temporal analysis highlights opportunities to improve retention among occasional users

## 📁 Repository Structure
```
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
├── visualizations/
├── README.md
└── requirements.txt
```

## ▶️ How to Run the Project

1. Clone the repository
2. Install dependencies (pip install -r requirements.txt)
3. Run the analysis notebooks in Jupyter

## 🚀 Future Improvements

- Implementation of recommendation models (Machine Learning)
- Predictive Analysis
- Automated data pipelines for scalability