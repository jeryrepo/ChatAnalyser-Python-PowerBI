# WhatsApp Chat Analysis

![SharedScreenshot](https://github.com/jeryrepo/ChatAnalyser-Python-PowerBI/assets/142509067/ab79b8ae-125a-4f2b-a6c6-e93dac3225c9)

## Overview
This Python script and Power BI dashboard combination offers a powerful solution for analyzing and visualizing WhatsApp chat data. The script processes raw chat data, performs text preprocessing, sentiment analysis, and generates a structured DataFrame. The subsequent Power BI dashboard provides insightful visualizations for better understanding chat dynamics.

## Key Features
- **Text Preprocessing:** Utilizes NLTK for comprehensive text cleaning, including URL removal, handling media messages, and stemming.
- **Sentiment Analysis:** Employs NLTK's VADER Sentiment Intensity Analyzer for sentiment scoring of each message.
- **Date and Time Extraction:** Parses date and time information, creating separate columns for analysis and visualization.
- **Data Visualization with Power BI:** The Power BI dashboard presents interactive visualizations for chat activity, sentiment trends, and frequently used words.

## How to Use
### Python Script
1. Clone the repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Replace the `file_path` variable in the script with the path to your WhatsApp chat file.
4. Run the script to generate a DataFrame with processed chat data.

### Power BI Dashboard
1. Open Power BI.
2. Import the cleaned DataFrame from the Python script.
3. Utilize the pre-built visualizations in the Power BI dashboard file (`ChatAnalyserDash.pbix`) for comprehensive insights.
4. Customize the dashboard based on your specific analysis needs.

## Dependencies
### Python Script
- pandas
- nltk
- matplotlib
- wordcloud
- emoji
- seaborn

### Power BI Dashboard
- Power BI Desktop

## Note
Ensure that you have NLTK's VADER lexicon downloaded using `nltk.download('vader_lexicon')`.
