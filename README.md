# Spotify 2024 Global Streaming Data Analysis

## 📌 Project Overview
This repository contains a statistical analysis of Spotify's 2024 global streaming data.  
It includes:
- Raw dataset
- Jupyter Notebook for analysis & visualization
- PDF report summarizing findings

## 📂 Repository Structure
spotify-2024-global-streaming-analysis/
│
├── data/
│   └── Spotify_2024_Global_Streaming_Data.csv
│
├── notebooks/
│   └── Spotify_2024_Global_Streaming_Data_Analysis.ipynb
│
├── reports/
│   └── Spotify_2024_Global_Streaming_Data_Analysis.pdf
│
├── README.md
├── requirements.txt
└── .gitignore

## 🔍 Key Insights
- **Top Country by Streams**: Sweden (93,449.76M streams)
- **Top Country by Monthly Listeners**: Russia (1,603.45M listeners)
- **Most Popular Genre**: Classical
- **Skewness of Streams**: ~ -0.05 (nearly symmetric distribution)
- **Kurtosis of Streams**: ~ -1.24 (platykurtic)

## 📊 Visualizations
The notebook includes:
- Top genres & countries bar charts
- Stream distribution pie chart
- Skip rate by genre box plot
- Duration vs monthly listeners scatter plot

## ⚙️ Requirements
To run the analysis locally, install dependencies:
```bash
pip install -r requirements.txt

Author: JOSEPH KAYIJUKA

TECHNOLOGIES:
pandas
numpy
mahplotlib
seaborn
scipy
