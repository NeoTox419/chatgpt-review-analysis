# ChatGPT Review Analysis

Sentiment analysis and exploratory analysis of ChatGPT user reviews using Python.

## About

This project analyzes user reviews to understand:

- Rating distribution
- Review activity over time
- Overall sentiment
- Relationship between ratings and sentiment
- Common terms in positive and negative reviews

Sentiment analysis is performed using **VADER** from NLTK.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK / VADER
- WordCloud
- Jupyter Notebook

## Project Files
- `chatgpt_reviews.csv` — The data used in the anaylsis (can also use the drive link in the notebook itself)
- `ChatGPT_Review_Analysis.ipynb` — Main analysis notebook
- `requirements.txt` — Required Python packages

## Setup

Install the required packages:

```bash
pip install -r requirements.txt
```
## Note
If NLTK reports a missing VADER or stopwords resource, download the required NLTK data through the NLTK downloader.