# Sentiment Analysis with Lexicon-Based Methods

This repository contains the code and resources for performing **Sentiment Analysis using Lexicon-Based Methods**, as described in the [blog post](#). The repository provides an implementation using **VADER** (Valence Aware Dictionary and sEntiment Reasoner) and **TextBlob**, along with example visualisations and results.

## Table of Contents
1. [Overview](#overview)
2. [Dataset](#dataset)
3. [How to Use](#how-to-use)
4. [Example Notebook](#example-notebook)
5. [Requirements](#requirements)
6. [Contributing](#contributing)

## Overview
Sentiment analysis is a natural language processing (NLP) technique used to determine whether data is positive, negative, or neutral. In this project, we explore lexicon-based sentiment analysis methods like **VADER** and **TextBlob**. These approaches are particularly useful for analyzing social media, product reviews, and other text datasets.

## Dataset
We’ve provided a sample dataset `sample_texts.csv` located in the `data/` folder. This dataset contains sample text for performing sentiment analysis, but feel free to use your own datasets.

## How to Use

### 1. Clone the repository:
```bash
git clone https://github.com/olivercareyncl/sentiment-analysis-lexicon-methods.git
cd sentiment-analysis-lexicon-methods
```

### 2. Install the required libraries:
```bash
pip install -r requirements.txt
```

### 3. Run the analysis:
```bash
python src/lexicon_based_analysis.py
```

## Example Notebook
You can explore a step-by-step guide to sentiment analysis using **VADER** and **TextBlob** in the Jupyter notebook provided under `notebooks/`.

## Requirements
The required Python packages are listed in `requirements.txt`. Key dependencies include:

- pandas
- vaderSentiment
- textblob
- matplotlib
- seaborn
- jupyter

## Contributing
Feel free to submit pull requests or open issues for any enhancements or bug fixes.
