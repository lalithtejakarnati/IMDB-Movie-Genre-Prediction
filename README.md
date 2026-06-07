# 🎬 Machine Learning and NLP-Based Movie Genre Prediction System

<p align="center">
  <img src="assets/banner.png" width="1000"/>
</p>

<h3 align="center">
Movie Genre Analysis and Prediction using Natural Language Processing and Machine Learning
</h3>

<p align="center">
Python • NLP • Machine Learning • Data Analysis • Text Classification
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Pandas-DataAnalysis-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/NLP-TextProcessing-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/ScikitLearn-MachineLearning-red?style=for-the-badge"/>
</p>

---

# 📌 Overview

This project explores movie datasets using Data Analysis, Natural Language Processing (NLP), and Machine Learning techniques.

The system analyzes movie metadata including:

- Genre
- Description
- Rating
- Revenue
- Director
- Runtime
- Year of Release

The objective is to understand movie trends, perform exploratory data analysis, and build a foundation for automated movie genre prediction using text classification techniques.

---

# ✨ Features

✅ Dataset Exploration

✅ Missing Value Handling

✅ Duplicate Detection

✅ Statistical Analysis

✅ Revenue Analysis

✅ Movie Rating Analysis

✅ Director Performance Analysis

✅ Genre-Based Filtering

✅ NLP-Based Text Processing

✅ Movie Genre Classification Pipeline

---

# 🏗️ Project Architecture

<p align="center">
  <img src="assets/architecture.png" width="1000"/>
</p>

text Movie Dataset       │       ▼ Data Cleaning       │       ▼ Exploratory Data Analysis       │       ▼ Text Preprocessing       │       ▼ Feature Extraction       │       ▼ Machine Learning Model       │       ▼ Genre Prediction 

---

# 📊 Dataset Information

Dataset: IMDB Movie Dataset

Attributes:

| Column | Description |
|----------|-------------|
| Title | Movie Name |
| Genre | Movie Genre |
| Description | Plot Summary |
| Director | Director Name |
| Actors | Cast Information |
| Year | Release Year |
| Runtime | Movie Duration |
| Rating | IMDB Rating |
| Votes | User Votes |
| Revenue | Revenue Generated |
| Metascore | Critic Score |

---

# 🔍 Exploratory Data Analysis

The project performs multiple analyses including:

### Dataset Shape Analysis

- Number of Rows
- Number of Columns

### Missing Value Analysis

- Revenue Missing Values
- Metascore Missing Values

### Duplicate Record Detection

### Statistical Summary

- Mean
- Median
- Standard Deviation
- Maximum
- Minimum

<p align="center">
  <img src="assets/eda.png" width="850"/>
</p>

---

# 📈 Key Insights

### Longest Movies Analysis

Movies with runtime greater than 180 minutes:

- The Wolf of Wall Street
- The Hateful Eight
- La vie d'Adèle

<p align="center">
  <img src="assets/runtime_analysis.png" width="850"/>
</p>

---

### Voting Trends

Movie voting patterns across years.

<p align="center">
  <img src="assets/voting_trends.png" width="850"/>
</p>

---

### Revenue Analysis

Highest Revenue Movie:

⭐ Star Wars: Episode VII – The Force Awakens

Revenue:
$936.63 Million

<p align="center">
  <img src="assets/revenue_analysis.png" width="850"/>
</p>

---

### Director Rating Analysis

Average ratings grouped by directors.

Top Directors:

- Christopher Nolan
- Makoto Shinkai
- Olivier Nakache
- Aamir Khan

<p align="center">
  <img src="assets/director_analysis.png" width="850"/>
</p>

---

### Top Rated Movies

- The Dark Knight
- Inception
- Interstellar
- Whiplash
- The Prestige

<p align="center">
  <img src="assets/top_rated_movies.png" width="850"/>
</p>

---

# 🧠 NLP Pipeline

The project prepares movie descriptions for genre prediction.

Steps:

1. Text Cleaning
2. Tokenization
3. Stopword Removal
4. Stemming
5. Feature Extraction
6. Genre Classification

<p align="center">
  <img src="assets/nlp_pipeline.png" width="900"/>
</p>

---

# 🤖 Machine Learning Workflow

text Movie Description        │        ▼ Text Cleaning        │        ▼ Tokenization        │        ▼ TF-IDF Vectorization        │        ▼ Classifier        │        ▼ Predicted Genre 

<p align="center">
  <img src="assets/ml_workflow.png" width="900"/>
</p>

---

# 📂 Project Structure

text Movie-Genre-Prediction-System/ │ ├── assets/ │ ├── Movie_Genre_Prediction.ipynb │ ├── IMDB-Movie-Data.csv │ ├── requirements.txt │ └── README.md 

---

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|----------|
| Python | Programming |
| Pandas | Data Analysis |
| NumPy | Numerical Computing |
| Matplotlib | Visualization |
| Seaborn | Statistical Visualization |
| Scikit-Learn | Machine Learning |
| NLP | Text Processing |

<p align="center">
  <img src="assets/tech_stack.png" width="850"/>
</p>

---

# 📊 Visualizations

Implemented Visualizations:

- Missing Value Heatmap
- Votes by Year
- Revenue by Year
- Director Rating Analysis
- Longest Movies Analysis
- Highest Revenue Movies
- Rating Distribution
- Revenue vs Rating Scatter Plot

<p align="center">
  <img src="assets/visualizations.png" width="900"/>
</p>

---

# 🚀 Future Improvements

- Multi-label Genre Prediction
- Deep Learning Models
- LSTM-based Text Classification
- BERT-based Genre Prediction
- Movie Recommendation System
- Real-time Web Application

<p align="center">
  <img src="assets/future_work.png" width="850"/>
</p>

---

# 👨‍💻 Author

## Karnati Lalith Teja

GitHub:
https://github.com/lalithtejakarnati

---

# 📜 License

This project is developed for:

- Academic Learning
- Machine Learning Practice
- NLP Research
- Educational Purposes

---

# ⭐ Acknowledgements

Special thanks to:

- IMDB Dataset Contributors
- Scikit-Learn Community
- NLP Research Community
- Open Source Python Ecosys
