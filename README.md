# Sentiment Analysis of X comments 
This repository is part of my professional portafolio. On this project i used a pretrained N.L.P model and Web Scrapping tecnics for extract several comments on Cartagena Major X accounts and analyze the community perception. The data visualization was presented on PowerBI dashboard. 

## Description
Sentiment analysis is a technique for identifying the emotional actitude of a certain text. For that every comments previously extracted was group into the following categories:

* Very Negative: 1.0 - 1.9
* Negative: 2.0 - 2.9
* Neutral: 3.0 - 3.9
* Positive: 4.0 - 4.9
* Very Positive: 5.0

## Technologies Used
Python: Main programming language
Pandas: For data manipulation and analysis
Transformers: For sentiment analysis
Selenium: For extraction of comments on X, mostly because X API must to be paid to analyze other accounts.
Power BI: For data visualization

## Project Structure
`````
Sentiment_analysis_on_x_comments/
├── data/ # Directory containing result CSV files
│ ├── X_dumek_data.csv # CSV file with results from step 1
│ ├── X_dumek_data_filtrado.csv # CSV file with results from step 2
│ └── X_dumek_data_final.csv # CSV file with results from step 3
├── notebooks/ # Directory containing Jupyter notebook
│ ├── X_comments_scrapper.ipynb # Notebook for step 1 analysis
│ ├── Prefiltrado_texto.ipynb # Notebook for step 2 analysis
│ └── Analisis de sentimiento.ipynb # Notebook for step 3 analysis
├── powerbi/ # Directory containing Power BI files
│ └── sentiment_analysis_dashboard.pbix # Power BI dashboard file
└── README.md # Project description
`````
