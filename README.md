# News Sentiment Analysis

This project aims to extract news data from a website using BeautifulSoup, clean and preprocess the extracted data using NLTK, perform sentiment analysis to determine if the news is good or bad, and store the results in an Excel file.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The purpose of this project is to automate the process of extracting news articles, cleaning and preprocessing the text data, analyzing the sentiment of the news articles, and saving the results in an organized manner. The sentiment analysis helps to categorize the news as either positive (good) or negative (bad).

## Installation

To get started with this project, you'll need to have Python installed on your machine. Follow the steps below to set up the project:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/news-sentiment-analysis.git
    cd news-sentiment-analysis
    ```

2. **Create and activate a virtual environment (optional but recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install the required packages:**
    ```bash
    pip install -r requirements.txt
    ```

## Usage

Follow the steps below to run the project:

1. **Extract data:**
   The script uses BeautifulSoup to scrape news data from a specified website. Update the URL in the script as needed.

2. **Clean and preprocess data:**
   The NLTK library is used to clean and preprocess the text data, including tokenization, stopword removal, and other text processing tasks.

3. **Perform sentiment analysis:**
   The script performs sentiment analysis on the cleaned data to classify the news as good or bad.

4. **Store data in an Excel file:**
   The results are saved in an Excel file for further analysis or reporting.

Run the main script:
```bash
python main.py
