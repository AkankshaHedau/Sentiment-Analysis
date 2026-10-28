# IMDb Movie Sentiment Analysis

## 📌 Project Overview

This project explores IMDb movie reviews using Python, Natural Language Processing (NLP) techniques, and data visualization. It focuses on cleaning textual data, analyzing movie ratings, and identifying frequently occurring words in positive and negative reviews.

## 🎯 Objectives

- Clean and preprocess movie review text.
- Explore movie ratings and review statistics.
- Analyze the distribution of ratings.
- Visualize frequently occurring words in positive and negative reviews.
- Develop a better understanding of text preprocessing and sentiment analysis.

## 🛠️ Technologies Used

- **Python**
- **Pandas & NumPy** — Data manipulation and analysis
- **NLTK** — Text preprocessing and stop-word handling
- **Matplotlib & Seaborn** — Data visualization
- **WordCloud** — Word frequency visualization
- **Plotly** — Interactive visualization library
- **Jupyter Notebook** — Development environment

## 📂 Project Structure

```text
imdb-movie-sentiment-analysis/
│
├── sentiment analysis.ipynb
├── IMDB-Dataset.csv
└── README.md
```

## 🔍 Project Workflow

### 1. Data Loading
Load the IMDb dataset containing movie names, reviews, and ratings.

### 2. Data Cleaning and Preprocessing
- Remove special characters and URLs.
- Remove selected stop words while retaining the word "not".
- Expand common English contractions.
- Normalize text to lowercase.

### 3. Exploratory Data Analysis
- Examine missing values and dataset information.
- Analyze rating and review statistics.
- Count unique reviews and movie names.
- Visualize the distribution of movie ratings.

### 4. Word Cloud Visualization
Generate separate word clouds to explore frequently occurring words in reviews with ratings of 7 or higher and ratings of 4 or lower.

## Dataset

The IMDb dataset is available here:

[Download IMDb Dataset](https://drive.google.com/file/d/1xT_E7Zk1-M-14cv3V_W2EZyzbl1tcYzv/view?usp=sharing )

## 📊 Key Analysis

The notebook explores movie review characteristics, rating distributions, and differences in frequently occurring words between higher-rated and lower-rated reviews.

## 🚀 How to Run the Project

1. Clone this repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/imdb-movie-sentiment-analysis.git
   ```

2. Navigate to the project directory:

   ```bash
   cd imdb-movie-sentiment-analysis
   ```

3. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Download the required NLTK resources if they are not already installed.

5. Ensure `IMDB-Dataset.csv` is in the project directory.

6. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

7. Open `sentiment analysis.ipynb` and run the cells.

## 📌 Future Improvements

- Implement a machine learning model for sentiment classification.
- Convert review text into numerical features using CountVectorizer or TF-IDF.
- Evaluate model performance using accuracy, precision, recall, and F1-score.
- Improve text preprocessing and compare different classification algorithms.



## 👩‍💻 Author

**Akanksha Hedau**


