# Stock-Movement-Analysis-Based-on-Social-Media-Sentiment
## Project Overview

This project develops a machine learning model that predicts stock movements by analyzing social media sentiment, specifically using Reddit as the primary data source. The system leverages natural language processing and machine learning techniques to extract insights from user-generated content related to stock market discussions.

## Features

- 🌐 Reddit Data Scraping
- 📊 Sentiment Analysis
- 🤖 Machine Learning Prediction Models
- 📈 Performance Comparison of Multiple Classifiers

## Prerequisites

### Software Requirements
- Python 3.8+
- pip (Python Package Manager)

### Required Libraries
- praw
- pandas
- numpy
- scikit-learn
- nltk
- matplotlib

## Installation

1. Clone the repository:
```bash
git clone https://github.com/sahanaprakash00/Stock-Movement-Analysis-Based-on-Social-Media-Sentiment.git
cd stock-sentiment-analysis
```

2. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

3. Install required dependencies:
```bash
pip install -r requirements.txt
```

## Setup

### Reddit API Credentials

1. Create a Reddit Developer Account:
   - Go to [Reddit Apps](https://www.reddit.com/prefs/apps)
   - Click "Create App"
   - Select "script" as the app type
   - Note down your:
     - Client ID
     - Client Secret
     - Username
     - Password
     - User Agent

2. Update Credentials:
   In the script, replace the following placeholders:
   ```python
   reddit = praw.Reddit(
       client_id="your_client_id",
       client_secret="your_client_secret",
       username="your_reddit_username",
       password="your_reddit_password",
       user_agent="your_user_agent",
   )
   ```

## Usage

1. Run the Jupyter Notebook:
```bash
jupyter notebook Stock_Movement_Analysis_Based_on_Social_Media_Sentiment.ipynb
```

2. Execute cells sequentially:
   - Data Scraping
   - Preprocessing
   - Sentiment Analysis
   - Model Training
   - Evaluation



## Limitations and Future Improvements

- ⚠️ Currently uses randomly generated price movements
- 🔧 Limited to Reddit data source
- 📊 Needs integration with actual stock price data
- 🤖 Potential for more advanced NLP techniques
