# Twitter Sentiment Analysis Project

## Overview
This project focuses on analyzing public opinion on social media using sentiment analysis techniques. A dataset of 10,000 tweets was used to classify user opinions into **positive**, **negative**, and **neutral** sentiments. The project also explores how sentiment relates to user engagement such as likes and retweets.

---

## Objectives
- Analyze public opinion from Twitter data  
- Classify tweets into sentiment categories  
- Understand engagement patterns (likes & retweets)  
- Identify common words in positive and negative tweets  
- Visualize insights using Power BI  

---

## Dataset
The dataset contains the following columns:
- `Tweet_ID` – Unique identifier  
- `Username` – Twitter user  
- `Text` – Tweet content  
- `Likes` – Number of likes  
- `Retweets` – Number of retweets  
- `Timestamp` – Time of tweet  

---

## Technologies Used
- Python  
- Pandas  
- NLTK (VADER Sentiment Analyzer)  
- TextBlob  
- Matplotlib  
- Power BI  

---

## Methodology
1. **Data Preprocessing**
   - Removed missing values and duplicates  
   - Cleaned text (links, symbols, special characters)  

2. **Sentiment Analysis**
   - Used **VADER** to classify tweets  
   - Compared results with **TextBlob**  

3. **Feature Engineering**
   - Created `sentiment_strength`  
   - Calculated `Total_Engagement = Likes + Retweets`  

4. **Exploratory Analysis**
   - Sentiment distribution  
   - Engagement by sentiment  
   - Frequent words in tweets  

5. **Visualization**
   - Built dashboard in **Power BI**  

---

## Key Insights
- Majority of tweets are **positive**  
- Positive tweets tend to receive **higher engagement**  
- Most sentiments are **moderate or weak**, not extreme  
- Common words reveal user opinion trends  


---

## Challenges
- No predefined sentiment labels  
- Handling noisy social media text  
- Difficulty detecting sarcasm and context  
- Dataset imbalance  

---

## Future Work
- Compare with other GitHub sentiment analysis projects  
- Use machine learning / deep learning models  
- Improve handling of sarcasm and context  
- Integrate real-time Twitter API  

---

## Example Output

| Text                     | Sentiment | Strength |
|--------------------------|----------|----------|
| I love this product      | Positive | Strong   |
| It is okay               | Neutral  | Weak     |
| Worst experience ever    | Negative | Strong   |

---

## Conclusion
This project demonstrates how sentiment analysis and data visualization can be combined to understand public opinion from social media data. It provides meaningful insights into user behavior and engagement patterns.

---

## How to Run
1. Clone the repository  
2. Install required libraries:
```bash
pip install pandas nltk textblob matplotlib
