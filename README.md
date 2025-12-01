**Restaurant Review Analytics**
A Complete NLP & Sentiment Analysis Project Across Multiple Restaurants

**Project Overview**
This project analyses customer reviews from multiple restaurants under the P&D Group.
Using Python, NLP, sentiment analysis, topic modelling, and data visualisation, the project uncovers:
1. Customer pain points
2. Monthly sentiment trends
3. Restaurant performance comparison
4. Most common complaints
5. Key themes behind negative and positive reviews

The goal is to deliver business insights useful for operations, customer experience, and decision-making.

**Key Objectives**

1. Clean and preprocess raw review data
2. Classify sentiment (Positive, Neutral, Negative)
3. Identify common keywords in negative reviews
4. Generate topics using LDA topic modelling
5. Track sentiment over time (month-to-month)
6. Compare restaurants across the group
7. Generate detailed case studies for each brand

**Tools & Libraries**

The project is built using:
1. Python
2. Pandas
3. NLTK (VADER Sentiment Analyzer)
4. Gensim (LDA Topic Modelling)
5. Matplotlib & Seaborn
6. WordCloud
7. OpenPyXL
8. Jupyter Notebook

**How to Run the Project**

Step 1 — Install dependencies
pip install -r requirements.txt

Step 2 — Open Jupyter Notebook
jupyter notebook

Step 3 — Run notebooks in this order
01_sentiment_analysis.ipynb
02_topic_modelling.ipynb
03_monthly_trends.ipynb

(Optional) Site-level analysis notebook

**Example Outputs**
You will find:
1. Sentiment Distribution - Bar charts visualising positive, neutral, and negative reviews.
2. Monthly Trend Analysis - Line charts showing how reviews change month to month.
3. Word Clouds - Most frequent words in negative reviews.
4. Topic Modelling - LDA-generated themes such as: Service issues, Food quality, Waiting time
5. Restaurant Comparison - Overall sentiment ranking across the P&D Group.

**Case Studies**
Each restaurant has a detailed case study, including:
1. Overview
2. Key themes
3. Sentiment patterns
4. Most common complaints
5. Recommendations

These are available in the /reports folder.

**About the Author**
This project was developed as part of a consulting-style analytical study, combining:
1. NLP
2. Data analysis
3. Business insights
4. Report writing
5. Visual storytelling

It demonstrates real-world problem-solving using data.

**Future Enhancements**
1. Build an interactive dashboard (Streamlit)
2. Apply BERT for deeper sentiment understanding
3. Automated alert system for negative reviews
4. Multi-language review analysis

