# Analyzing Customer Perception: A Comparative Study of Airlines

In the ever-evolving world of air travel, understanding customer perception is vital for airlines seeking to enhance their services. In this GitHub repository, we delve into a comparative analysis of customer reviews for two prominent airlines—Singapore Airlines and Malaysian Airlines. The analysis spans three key steps: data collection, exploratory data analysis, and sentiment analysis.

## Step 1: Data Collection

### Packages Used:
- **Web Scraping:** `requests` and `BeautifulSoup` for extracting reviews from [Airline Quality](https://www.airlinequality.com/).
- **Data Manipulation and Visualization:** `pandas`, `matplotlib`, `plotly.express`, `seaborn`.
- **Natural Language Processing (NLP):** `nltk`, `scattertext`, `spacy`.
- **WordCloud Generation:** `WordCloud`.
  
The code collects customer reviews for both airlines, categorizes them into verified and non-verified, and saves the data into CSV files.

## Step 2: Exploratory Data Analysis (EDA)

### Key Findings:
- Explores the percentage of verified reviews for each airline.
- Utilizes Scattertext to visualize differences in reviews between Singapore Airlines and Malaysian Airlines.
- Identifies insights such as the frequency of specific words and common concerns.

## Step 3: Sentiment Analysis

### Key Steps:
1. Utilizes the VADER sentiment analysis tool from `nltk` to assign sentiment scores.
2. Generates WordClouds for both airlines to visually represent the most frequent words in positive and negative reviews.
3. Categorizes sentiment scores into positive, neutral, and negative.
4. Creates interactive bar plots using `plotly` to showcase the distribution of sentiment labels.

### Insights:
- Singapore Airlines receives more positive reviews, with words like "excellent" and "best" being prevalent.
- Malaysian Airlines attracts negative sentiments related to delays, while Singapore Airlines is associated with premium features like "Premium Economy" and "Book the Cook."

## Conclusion and Future Recommendations

The analysis provides valuable insights into customer perception for the two airlines. Further in-depth investigations, including customer-focused discussions and surveys, are recommended to understand specific attributes influencing satisfaction. This could encompass aspects such as flight ambiance, meal quality, lounge access, and how delays are handled. Conducting such surveys will offer a comprehensive understanding of factors influencing customer satisfaction within the specified demographic, guiding airlines towards more customer-centric strategies.
