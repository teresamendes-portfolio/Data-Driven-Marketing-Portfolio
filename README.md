# Teresa Mendes - Data-Driven Marketing Analytics Portfolio
Welcome to my Data Analyst Portfolio!
A collection of marketing analytics projects using Python, SQL and visualization to support real business decisions.

---

## Projects

- ### What Drives Engagement on Sephora Portugal’s Instagram

**Code:** [Notebook – Sephora IG Engagement Analysis](https://github.com/teresamendes-portfolio/PortfolioProjects/blob/main/Python_Projects/instagram_engagement_analysis_sephora_pt.ipynb)

**Goal:** Identify the content formats, hashtags, and posting times that drive higher engagement for Sephora Portugal.

**Description:** Using public Instagram data collected via RapidAPI, this project builds a clean post-level dataset and analyzes performance across content types, hashtags, and posting schedule (weekday/hour). The analysis highlights what performs best and translates findings into actionable content strategy recommendations.

**Skills:** data collection via APIs (RapidAPI), data cleaning, feature engineering, exploratory data analysis (EDA), engagement metrics, data visualization.

**Technology:** Python, Pandas, NumPy, Matplotlib, RapidAPI.

**Results:** Carousels outperform reels in engagement; late-week daytime posts show the strongest engagement; a small set of hashtags consistently correlates with higher engagement.



- ### Ronaldo–Al-Nassr Transfer: What Fans Said on Instagram

**Code:** [Notebook – Ronaldo Transfer to Al-Nassr Instagram Comment Mining](https://github.com/teresamendes-portfolio/PortfolioProjects/blob/main/Python_Projects/nlp_text_mining_ronaldo_alnassr_instagram.ipynb)

**Goal:** Analyze public reactions to Cristiano Ronaldo’s transfer to Al-Nassr using Instagram comments, identifying dominant themes, sentiment patterns, and conversation clusters.

**Description:** Academic project using public Instagram comments collected via RapidAPI. After cleaning the text, the notebook applies language detection, word frequency analysis, sentiment scoring, topic modeling (LDA), TF-IDF keyword extraction, co-occurrence analysis, and clustering to uncover the main narratives around the transfer.

**Skills:** Data collection via APIs (RapidAPI), text preprocessing, NLP (frequency, TF-IDF, LDA), sentiment analysis, clustering, network analysis, data visualization.

**Technology:** Python, Pandas, NLTK, TextBlob, Scikit-learn, NetworkX, Matplotlib, Seaborn, WordCloud, LangDetect, RapidAPI.

**Results (high level):** English comments are mainly supportive, dominated by admiration/legacy terms (e.g., “goat”, “best”, “love”). Sentiment is mostly neutral with a clear positive tail and very few strong negatives.  
LDA and clustering reveal narratives around admiration/legacy, season and performance at Al-Nassr, fan encouragement, and comparisons with Messi.

- ### Hotel H Guest Segmentation (K-Means + PCA + Hierarchical Validation)

**Code:** Notebook 01 – Data Prep & EDA | Notebook 02 – K-Means + PCA | Notebook 03 – Hierarchical Clustering

**Goal:** Build a data-driven guest segmentation for a Lisbon hotel case study, beyond simple country-of-origin grouping.

**Description:** Cleaned and prepared the dataset, encoded categorical features, applied PCA to reduce dimensionality, and clustered guests using K-Means. Cluster selection was supported with elbow + silhouette diagnostics, and hierarchical clustering was used as a robustness cross-check.

**Skills:** Data cleaning, feature engineering, encoding, EDA, PCA, clustering (K-Means & hierarchical), silhouette/elbow evaluation, segmentation profiling.

**Technology:** Python, Pandas, NumPy, Scikit-learn, Matplotlib.

**Results:** Identified 6 guest segments with clear differences across channel mix, lead time, stay intensity, revenue signals, and no-show rate.
