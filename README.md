📊 Netflix IMDB Score Analysis & Prediction
This repository contains a data exploration and modeling notebook analyzing the relationship between Netflix content metadata and their IMDb scores.

📂 Files
Netflix_imdbscore.ipynb — main Jupyter notebook for:

Data cleaning

Feature engineering

Exploratory data analysis (EDA)

Text preprocessing

Correlation visualization

Preparation for machine learning modeling

🔍 Project Overview
The notebook focuses on:

Loading and exploring Netflix shows & movies dataset

Handling missing values and encoding categorical features (age_certification,type(Movie,Show) etc.)

Transforming text data (title & description)

Visualizing feature relationships with IMDb scores (e.g., boxplots, heatmaps)

Preparing features for potential regression modeling

The goal is to understand which features contribute most to IMDb score variation.

🛠️ Main Techniques & Libraries
pandas & NumPy for data processing

matplotlib & seaborn for visualization

nltk for text preprocessing

scikit-learn for feature scaling and encoding

📈 Key Visualizations
Boxplots: IMDb scores by age certification

Correlation heatmaps: Numeric feature correlations

✅ Requirements
Install dependencies using:

bash
Copy
Edit
pip install pandas numpy matplotlib seaborn nltk scikit-learn
🚀 Usage
Open and run the notebook:

bash
Copy
Edit
jupyter notebook Netflix_imdbscore.ipynb
Make sure the dataset file (e.g., Netflix TV Shows and Movies.csv) is available in the same directory.

✏️ Future Work
Model training & evaluation (e.g., regression, ensemble methods)

Improved text vectorization (TF-IDF, embeddings)

Feature importance analysis

Deploy as a prediction API
