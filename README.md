# Review Mind - ML Review Analysis

This project focuses on analyzing Amazon product reviews using machine learning techniques. The analysis includes sentiment analysis and review classification to understand customer feedback patterns.

## Project Overview

The project uses a dataset of Amazon reviews, specifically focusing on automotive products. The analysis includes:
- Sentiment analysis of customer reviews
- Classification of review sentiments
- Analysis of verified vs unverified reviews
- Feature extraction from review text

## Dataset

The project uses two main datasets:
- `Training.csv`: Contains 29,189 reviews for model training
- `Test.csv`: Contains 4,500 reviews for model evaluation

### Dataset Features
- `overall`: Rating (1-5 stars)
- `verified`: Whether the review is verified
- `reviewTime`: Time of the review
- `reviewerID`: Unique identifier for the reviewer
- `reviewText`: The actual review text
- `summary`: Brief summary of the review
- `category`: Product category (automotive)
- Additional metadata including votes, images, and style information

## Project Structure

- `Final Project - Chikwanda Chisha.ipynb`: Main Jupyter notebook containing the analysis
- `Training.csv`: Training dataset
- `Test.csv`: Test dataset

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Natural Language Processing (NLP) tools

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/ChikwandaChisha/Amazon-Reviews-ML-Analysis.git
```

2. Install required dependencies:
```bash
pip install pandas numpy scikit-learn matplotlib jupyter
```

3. Open the Jupyter notebook:
```bash
jupyter notebook "Final Project - Chikwanda Chisha.ipynb"
```

## Author

Chikwanda Chisha

