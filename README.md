# Opay-Google-Play-Store-Sentiment-Analysis



This project analyzes user reviews from the Google Play Store to understand customer sentiment towards Opay mobile app. It leverages natural language processing (NLP) techniques and the VADER sentiment analysis tool to categorize reviews as positive, negative, or neutral.

## Project Steps

1. **Data Collection:** Fetch user reviews from the Google Play Store using the `google-play-scraper` library.
2. **Data Cleaning:** Preprocess the text data by removing unnecessary characters, converting to lowercase, and handling missing values.
3. **Sentiment Analysis:** Utilize VADER to calculate sentiment scores (negative, neutral, positive, compound) for each review.
4. **Categorization:** Classify reviews into sentiment categories based on the compound score.
5. **Word Frequency Analysis:** Tokenize and lemmatize the text, remove stop words, and count word frequencies for each sentiment category.
6. **Visualization:** Create visualizations (e.g., bar charts, word clouds) to gain insights from the sentiment and word frequency data.

## Libraries Used

- `google-play-scraper`
- `pandas`
- `numpy`
- `nltk`
- `vaderSentiment`
- `matplotlib`
- `seaborn`
- `wordcloud`
## Tools Uses
- `Python`
- `Power BI`

## Opay App Review Analysis Dashboard

### Overview
This project involves scraping reviews from the Google Play Store for the Opay app, analyzing the data, and visualizing the insights using Power BI.

### Key Insights
1. **Overall Sentiment**: The Opay app has a positive sentiment score of 85.53%, with an average rating of 4.28/5 from 258K reviews.
2. **Frequent Feedback**:
   - Positive keywords: "good", "best", "awesome"
   - Common issues: transaction problems, transfer delays, network issues, and customer service concerns.
3. **Rating Distribution**:
   - 5-star: 179.02K reviews
   - 4-star: 30.46K reviews
   - 3-star: 14.53K reviews
   - 2-star: 8.05K reviews
   - 1-star: 25.69K reviews

### Interactive Dashboard
Explore the full interactive dashboard [here](https://app.powerbi.com/view?r=eyJrIjoiYzNjZGNiMmUtODM5ZC00ZDE0LTgxYjAtYzQzYTJlZDBkOTIwIiwidCI6IjFiYTIwODY1LWY3ZWYtNGM0Mi1hOTNjLTlhNGFjZGI0YzM2ZSJ9&pageName=ReportSection).

### Recommendations

1. **Enhance Customer Service**:
   - Improve response times and resolution efficiency for customer inquiries and issues.
   - Implement better training programs for customer service representatives to handle common issues more effectively.

2. **Optimize Transaction Processes**:
   - Address and fix bugs related to transaction failures and delays.
   - Streamline the transaction process to ensure a faster and more reliable experience for users.

3. **Network and App Performance**:
   - Invest in improving the app's network stability to reduce connectivity issues.
   - Regularly update the app to enhance speed and performance, particularly for loading and transaction times.

4. **User Feedback Integration**:
   - Actively monitor and analyze user feedback to identify and prioritize areas for improvement.
   - Implement a feedback loop where users are informed about how their feedback is being used to make changes.

5. **Communication and Transparency**:
   - Increase transparency about app updates and maintenance schedules to keep users informed.
   - Provide clear communication about any ongoing issues and expected resolution times.
