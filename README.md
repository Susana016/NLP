# Sentiment Analysis Project

## Overview
This project analyzes sentiment (negative, neutral, positive) in text data using Python's NLTK package.

## Problem Statement
Analyze the emotional tone conveyed in a large corpus of text to identify patterns and classify texts into sentiment categories.

## Dataset
- **Source**: [Hospital Reviews Dataset from Kaggle](https://www.kaggle.com/datasets/junaid6731/hospital-reviews-dataset)
- **How to download**: Log into Kaggle, click "Download", and extract to the `data/` folder

## Installation

Install required packages:
```bash
pip install pandas numpy nltk matplotlib seaborn wordcloud jupyter
```

Download NLTK data:
```python
import nltk
nltk.download('vader_lexicon')
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')
```

## Algorithm
1. **Data Preprocessing**: Clean text, remove stop words, tokenization
2. **Sentiment Analysis**: Use NLTK's VADER to score sentiment
3. **Classification**: Categorize as positive, neutral, or negative
4. **Visualization**: Create charts and word clouds
5. **Analysis**: Interpret results and extract insights

## Usage
1. Place dataset in `data/` folder
2. Open `sentiment_analysis.ipynb` in Jupyter
3. Run all cells

## Project Structure
```
├── README.md
├── sentiment_analysis.ipynb    # Main notebook with all code and analysis
├── data/                       # Dataset folder
└── outputs/                    # Generated plots
```

## Report Contents
The Jupyter notebook includes:
- **Problem Statement**: Background and objectives
- **Algorithm**: Step-by-step methodology
- **Analysis**: Results, visualizations, and findings
- **References**: Sources and documentation

## Requirements
- Python 3.8+
- pandas, numpy, nltk, matplotlib, seaborn, wordcloud, jupyter