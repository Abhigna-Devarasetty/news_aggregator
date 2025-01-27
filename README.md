# News Aggregator Project

This project automates the summarization of news articles in various domains such as technology, business, health, and more. It fetches recent articles using the NewsAPI, evaluates their relevance, and provides concise summaries using state-of-the-art NLP models.

## Project Overview

The News Aggregator project is designed to:
- Fetch recent news articles using NewsAPI.
- Evaluate article relevance based on predefined topics.
- Summarize relevant articles using Transformer-based models.

## Repository Structure

- **`code.ipynb`**: Main Jupyter Notebook containing all the project code.
- **`tech_news_summaries.csv`**: Output file containing summarized news articles.

## Features

- **News Fetching**: Automatically fetches news articles from predefined topics.
- **Relevance Checking**: Filters articles based on their relevance to the topics using cosine similarity and NLP embeddings.
- **Summarization**: Utilizes models like T5 to generate concise summaries of relevant articles.

## Prerequisites

Ensure the following packages are installed:
- `langchain`
- `newsapi-python`
- `transformers`
- `datasets`
- `rouge-score`
- `sentence-transformers`
- `langchain_community`

You can install all required packages via pip:
```bash
pip3 install langchain newsapi-python transformers datasets rouge-score sentence-transformers langchain_community