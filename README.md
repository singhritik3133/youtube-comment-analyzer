# youtube-comment-analyzer
# YouTube Comment Sentiment Analyzer

A web application that analyzes sentiment trends in YouTube video comments over a 12-month period. The tool provides visualizations, word clouds, and detailed sentiment analysis of comments.

## Features

- Analyze YouTube video comments from the last 12 months
- Sentiment analysis using VADER sentiment analyzer
- Interactive charts showing sentiment trends
- Word cloud generation
- Monthly sentiment breakdown
- Top positive and negative comments
- Export data to CSV
- Mobile-responsive design
- Beautiful and modern UI

## Prerequisites

- Python 3.7+
- Flask
- YouTube Data API key

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/youtube-sentiment-analyzer.git
cd youtube-sentiment-analyzer
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Set up your YouTube API key:
   - Get an API key from the [Google Cloud Console](https://console.cloud.google.com/)
   - Enable the YouTube Data API v3
   - Set your API key as an environment variable:
     ```bash
     export YOUTUBE_API_KEY='your_api_key_here'
     ```

## Usage

1. Start the Flask server:
```bash
python app.py
```

2. Open your browser and navigate to:
```
http://localhost:5004
```

3. Enter a YouTube video URL and click "Analyze"

## Technologies Used

- Backend:
  - Python
  - Flask
  - VADER Sentiment Analysis
  - YouTube Data API
  - Pandas
  - WordCloud

- Frontend:
  - HTML5
  - CSS3
  - JavaScript
  - Chart.js
  - Bootstrap
  - Particles.js

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details. 
