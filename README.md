# Sentiment Analysis using VADER on YouTube Comments

## Project Description
This project extracts comments from YouTube videos using the YouTube Data API and performs sentiment analysis using VADER (Valence Aware Dictionary and sEntiment Reasoner). It helps analyze the overall sentiment of user comments on a given YouTube video.

## Features
- Fetches YouTube comments using the YouTube API
- Performs sentiment analysis using VADER
- Classifies comments into positive, negative, and neutral categories
- Uses Pandas for data manipulation and processing

## Installation
Ensure you have Python installed (>=3.7). Then, install the required dependencies:

```bash
pip install google-api-python-client pandas nltk
```

You will also need to download the VADER lexicon:

```python
import nltk
nltk.download('vader_lexicon')
```

## Usage
1. **Set up YouTube API access:**
   - Obtain an API key from [Google Cloud Console](https://console.cloud.google.com/)
   - Replace `api_key` in the script with your API key

2. **Run the script:**

```python
python sentiment_analysis.py
```

## Dependencies
- `google-api-python-client`
- `pandas`
- `nltk`

## Author
[SRINATH]



