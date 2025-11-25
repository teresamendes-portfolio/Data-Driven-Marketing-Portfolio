# Teresa Mendes - Data-Driven Marketing Analytics Portfolio
Welcome to my Data Analyst Portfolio!
A collection of marketing analytics projects using Python, SQL and visualization to support real business decisions.

---

## Projects

### Instagram Engagement Analysis - Sephora Portugal

**Code:** [What Drives Engagement on Sephora Portugal’s Instagram](Python_Projects/instagram_engagement_analysis_sephora_pt.ipynb)

**Goal:** Identify the content formats, hashtags, and posting times that drive higher engagement for Sephora Portugal.

**Description:** Using public Instagram data collected via RapidAPI, this project builds a clean post-level dataset and analyzes performance across content types, hashtags, and posting schedule (weekday/hour). The analysis highlights what performs best and translates findings into actionable content strategy recommendations.

**Skills:** data collection via APIs (RapidAPI), data cleaning, feature engineering, exploratory data analysis (EDA), engagement metrics, data visualization.

**Technology:** Python, Pandas, NumPy, Matplotlib, RapidAPI.

**Results:** Carousels outperform reels in engagement; late-week daytime posts show the strongest engagement; a small set of hashtags consistently correlates with higher engagement.



## Instagram Comment Mining - Ronaldo’s Transfer to Al-Nassr

**Code:** [Ronaldo–Al-Nassr Transfer: What Fans Said on Instagram](Python_Projects/nlp_text_mining_ronaldo_alnassr_instagram.ipynb)


**Goal:**  
Analyze public reactions to Cristiano Ronaldo’s transfer to Al-Nassr using Instagram comments, identifying dominant themes, sentiment patterns, and conversation clusters.

**Description:**  
Academic project using public Instagram comments collected via RapidAPI. After cleaning the text, the notebook applies language detection, word frequency analysis, sentiment scoring, topic modeling (LDA), TF-IDF keyword extraction, co-occurrence analysis, and clustering to uncover the main narratives around the transfer.

**Skills:**  
Data collection via APIs (RapidAPI), text preprocessing, NLP (frequency, TF-IDF, LDA), sentiment analysis, clustering, network analysis, data visualization.

**Technology:**  
Python, Pandas, NLTK, TextBlob, Scikit-learn, NetworkX, Matplotlib, Seaborn, WordCloud, LangDetect, RapidAPI.

**Results (high level):**  
English comments are mainly supportive, dominated by admiration/legacy terms (e.g., “goat”, “best”, “love”). Sentiment is mostly neutral with a clear positive tail and very few strong negatives.  
LDA and clustering reveal narratives around admiration/legacy, season and performance at Al-Nassr, fan encouragement, and comparisons with Messi.
