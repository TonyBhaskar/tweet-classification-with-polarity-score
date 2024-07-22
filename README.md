# Polarity Score-Based Supervised Learning for Classification of Fake and Authentic Tweets using NLP

This project is a desktop application that classifies tweets as either fake or authentic based on their polarity scores. It uses Natural Language Processing (NLP) techniques and supervised machine learning to process and analyze tweet data.

## Features

- **Tweet Upload**: Upload a dataset of tweets from a CSV file.
- **Data Preprocessing**: Clean and preprocess tweet data to remove punctuation, stopwords, and non-alphabetic characters.
- **Sentiment Analysis**: Use TextBlob to calculate the polarity score of each tweet and classify it as fake or authentic.
- **Performance Graph**: Display a pie chart showing the percentage of fake and authentic tweets.

## Dependencies

- Python 3.x
- Tkinter
- NLTK
- TextBlob
- Matplotlib
- Pandas
- NumPy

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/TonyBhaskar/your-repo-name.git
    cd your-repo-name
    ```

2. Create and activate a virtual environment:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Download NLTK stopwords:
    ```python
    import nltk
    nltk.download('stopwords')
    ```

## Usage

1. Run the application:
    ```bash
    python your_script_name.py
    ```

2. Use the graphical interface to:
   - Upload a CSV file containing tweets.
   - Read and display tweets from the file.
   - Clean and preprocess the tweet data.
   - Perform sentiment analysis and classify tweets.
   - Display a performance graph showing the classification results.

## Dataset

The CSV file should have a column named `Text` containing the tweets.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

We welcome contributions to enhance the functionality of this project. To contribute, please fork the repository and create a pull request with your changes.

