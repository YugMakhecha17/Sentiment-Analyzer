# Sentiment-Analyzer
The purpose of this project revolves around making a sentiment analyzer which leverages Reddit posts in order to make stock predictions. The primary focus here is to use Natural Language Processing to analyze Reddit activities, such as, posts, comments, etc. The picked activities are those that correlate with actual stock price movements. 

## Setup

1. Install the required dependencies:
```bash
pip install -r requirements.txt
```

2. Create a `.env` file with your Reddit API credentials:
```
REDDIT_CLIENT_ID=your_client_id
REDDIT_CLIENT_SECRET=your_client_secret
REDDIT_USER_AGENT=your_user_agent
```

3. Run the main script:
```bash
python stock_sentiment.py
```

## Features

- Fetches Reddit posts and comments about specific stocks
- Analyzes sentiment using natural language processing
- Correlates sentiment with stock price movements
- Provides basic trend predictions

## Note

This project is for educational purposes. Always do your own research before making investment decisions. 
