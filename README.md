# WhatsApp Chat Analysis

![SharedScreenshot](https://github.com/jeryrepo/ChatAnalyser-Python-PowerBI/assets/142509067/ab79b8ae-125a-4f2b-a6c6-e93dac3225c9)


## Overview
This Python script analyzes and visualizes WhatsApp chat data, providing insights into message sentiment, chat activity, and frequently used words. The script processes a WhatsApp chat file, performs text preprocessing, sentiment analysis, and generates visualizations for a comprehensive understanding of the chat dynamics.

## Features
- **Text Preprocessing:** Utilizes NLTK for text cleaning, including URL removal, handling media messages, and stemming.
- **Sentiment Analysis:** Uses NLTK's VADER Sentiment Intensity Analyzer to assign sentiment scores to messages.
- **Date and Time Extraction:** Parses date and time information from the chat and adds relevant columns to the DataFrame.
- **Data Visualization:** Visualizes data using Matplotlib and Seaborn for insights into chat activity, sentiment trends, and more.
- **Word Cloud Generation:** Creates word clouds to visually represent frequently used words in the chat.

## How to Use
1. Clone the repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Replace the `file_path` variable in the script with the path to your WhatsApp chat file.
4. Run the script to generate a DataFrame with processed chat data.

## Dependencies
- pandas
- nltk
- matplotlib
- wordcloud
- emoji
- seaborn

## Note
Ensure that you have NLTK's VADER lexicon downloaded using `nltk.download('vader_lexicon')`.
