# Prodigy Data Science Task 4 - Twitter Sentiment Analysis

This notebook contains the code for analyzing Twitter sentiment data as part of Prodigy InfoTech's Data Science internship (Task 4).

## Notebook Contents

1. **Data Loading and Preparation**
   - Loads training and validation datasets from CSV files
   - Combines both datasets into a single DataFrame
   - Prints the shapes of the datasets

2. **Text Cleaning**
   - Implements a `clean_text()` function that:
     - Removes URLs, mentions, and hashtags
     - Removes non-alphabetic characters
     - Converts text to lowercase
     - Removes stopwords
     - Performs lemmatization
   - Applies this cleaning to the tweet content

3. **Exploratory Data Analysis**
   - Visualizes sentiment distribution in both training and validation data using count plots
   - Displays the top 10 most frequent entities (Twitter accounts) in the dataset
   - Creates a bar plot of the top entities

## Key Features

- Uses pandas for data manipulation
- Implements NLTK for text preprocessing (stopwords removal, lemmatization)
- Uses seaborn and matplotlib for data visualization
- Handles Twitter-specific text cleaning (mentions, hashtags, URLs)

## How to Use

1. Ensure you have the required datasets:
   - `twitter_training.csv`
   - `twitter_validation.csv`

2. The notebook will:
   - Load and combine the datasets
   - Clean the tweet text
   - Perform basic EDA on sentiment and entities

3. Future work could include:
   - Building a sentiment classification model
   - More advanced text preprocessing
   - Entity-specific sentiment analysis

