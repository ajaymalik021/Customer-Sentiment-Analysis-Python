# Customer Sentiment Analysis for iPhone 15 128GB

## Project Overview
This project aims to analyze customer sentiment towards the iPhone 15 128GB model by scraping, processing, and analyzing product reviews from Flipkart. The insights derived from this analysis will help Flipkart understand customer perceptions, identify potential areas for improvement, and enhance customer experience.

## Objectives
- **Scrape Customer Reviews**: Extract at least 300 reviews from Flipkart using Selenium and BeautifulSoup.
- **Clean and Preprocess Data**: Remove duplicates, handle missing values, and preprocess text data for analysis.
- **Perform Sentiment Analysis**: Use TextBlob to classify reviews as positive or negative based on sentiment polarity.
- **Analyze and Visualize Data**: Generate insights using Pandas, Matplotlib, and Seaborn.
- **Report Findings**: Summarize key trends and recommendations based on sentiment analysis.

## Tools & Libraries
- **Selenium**: Automates web interactions for scraping reviews.
- **BeautifulSoup**: Parses HTML to extract relevant review details.
- **Pandas**: Cleans and preprocesses data.
- **TextBlob**: Performs sentiment analysis.
- **Matplotlib/Seaborn**: Visualizes sentiment distribution and trends.

## Project Workflow
### 1. Data Collection (Web Scraping)
- Use Selenium to navigate to Flipkart’s iPhone 15 128GB product page.
- Extract review details (username, rating, review text) using BeautifulSoup.
- Handle pagination to collect at least 300 reviews.

### 2. Data Cleaning & Preprocessing
- Remove duplicate reviews.
- Handle missing values.
- Text preprocessing:
  - Convert text to lowercase.
  - Remove special characters and punctuation.
  - Tokenize and remove stop words.
  - Perform lemmatization.

### 3. Sentiment Analysis
- Use TextBlob to compute polarity scores for each review.
- Classify reviews as:
  - **Positive** (Polarity Score ≥ 0.1)
  - **Negative** (Polarity Score < 0.1)

### 4. Data Analysis & Insights
- **Sentiment Distribution**: Determine the percentage of positive vs. negative reviews.
- **Average Rating vs. Sentiment**: Analyze correlation between numerical ratings and sentiment scores.
- **Word Cloud**: Visualize frequently mentioned words in positive and negative reviews.
- **Review Length Analysis**: Assess how review length correlates with sentiment.

### 5. Reporting
- Overview of data collection and cleaning processes.
- Key findings from sentiment analysis.
- Actionable insights and recommendations for Flipkart.

## Installation & Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/customer-sentiment-analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd customer-sentiment-analysis
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the scraper:
   ```bash
   python scrape_reviews.py
   ```
5. Perform sentiment analysis:
   ```bash
   python sentiment_analysis.py
   ```
6. Generate visualizations:
   ```bash
   python visualize_results.py
   ```

## Dataset
The dataset consists of scraped reviews, including:
- **Username**: Reviewer’s name.
- **Rating**: Rating (1-5 stars).
- **Review Text**: Customer feedback.
- **Sentiment Classification**: Positive/Negative.

## Results & Insights
- **Overall Sentiment Distribution**
- **Most Common Words in Reviews**
- **Correlation Between Ratings and Sentiment**
- **Key Product Strengths & Weaknesses**

## Future Enhancements
- Expand dataset by scraping more reviews.
- Use advanced NLP techniques (e.g., VADER, BERT) for sentiment analysis.
- Develop an interactive dashboard for real-time insights.

## Contributing
Contributions are welcome! If you'd like to improve this project, feel free to submit a pull request.

## License
This project is licensed under the MIT License.

---
