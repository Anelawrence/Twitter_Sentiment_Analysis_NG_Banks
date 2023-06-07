# Twitter Sentiment Analysis of Nigerian Banks
### Introduction
The banking industry in Nigeria is the most digitized on the continent, and the nation was recently named the leader in digital payments in Africa. A press release from 2022 states that Nigeria recorded 3.7 billion real-time payments in 2021, placing it sixth among nations with the largest real-time payments markets.
However, due to high inflation, rising interest rates, shortage of US dollars, regulatory interference, and shortage of the Naira notes before the general election in February, weakens bank operating conditions in 2023.

### Aims and Objectives
This project aims to uncover insights in from bank customers' tweets on Twitter.com. To see how the banks' online customers perceive or react to the respective banks' services.

### Project Overview
There are three major sections to this project:

**Data Analysis and Visualization**: For data visualization, the libraries matplotlib, seaborn and wordcloud were used.

### Process Methodology
- **Data Collection**: A python library called Snscrape is used to scrape tweets from Twitter, while pandas is used to read in the scraped data. The data collected are tweets of contains banks name from january to May, 2023.
- **Data Cleaning and Preprocessing**: The libraries used are pandas (for data cleaning and analysis), textblob (for sentiment analysis), and nltk (natural processing language toolkit).
-  **Sentiment Analysis**: The tweets' polarity was determined using the TextBlob library. Polarity has a scale from -1 to 1, with a score below 0 being considered **negative**, 0 being considered **neutral**, and a score above 0 being considered **positive**.  On the other hand, subjectivity gauges the intensity of each tweet's emotions. These ratings reflect the general opinion expressed by twitter users about Nigerian banks.
- **Exploratory Data Analysis/Visualization** : Text mining and data wrangling were used in this stage to extract pertinent data and information and produce insightful findings. In order to make the results easier to understand, visualizations were created.

