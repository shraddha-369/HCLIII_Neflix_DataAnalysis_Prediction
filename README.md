🎬 Netflix Dataset Analysis & Prediction
📌 Overview

This project explores and analyzes the Netflix dataset, covering content distribution, genres, and release trends. It also implements a Machine Learning model to predict content type (Movie/TV Show) and a Recommendation System for suggesting similar titles.


📂 Dataset

Source: Netflix Titles Dataset

Features include: Title, Director, Cast, Country, Release Year, Genres, Description, etc.


📊 Exploratory Data Analysis (EDA)

✔ Movies vs TV Shows distribution
✔ Top 10 content-producing countries
✔ Yearly release trends
✔ Most popular genres
✔ WordCloud of content descriptions


🤖 Machine Learning Model

Algorithm: Logistic Regression

Task: Predict whether a content is a Movie (0) or TV Show (1)

Evaluation: Accuracy Score & Classification Report


🎯 Recommendation System

Approach: Content-Based Filtering using TF-IDF + Cosine Similarity

Input: A movie/TV show title

Output: Top 5 similar recommendations


📝 Results & Insights

Netflix has more Movies compared to TV Shows.

US & India are leading content producers.

Majority of content released after 2015.

Drama & Comedy dominate the genres.

Machine Learning model gives decent accuracy.

Recommendation System provides relevant suggestions.


🚀 How to Run
git clone https://github.com/your-username/netflix-analysis.git
cd netflix-analysis
pip install -r requirements.txt
python netflix_analysis.py


❤️ Final Note

This project highlights the power of Data Science in entertainment analytics, blending EDA, ML & Recommendations into one powerful notebook.
