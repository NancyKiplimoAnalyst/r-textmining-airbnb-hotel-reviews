##README
# Enhancing Hotel Services through Customer Review Insights  

This project analyzes customer feedback from TripAdvisor hotel reviews and Airbnb reviews using text mining and sentiment analysis techniques. The goal is to help hotels learn from positive Airbnb experiences while addressing negative feedback in their own reviews to improve service quality and remain competitive.  

##  Project Links  
Project Repository: [View on GitHub](https://github.com/NancyKiplimoAnalyst/r-textmining-airbnb-hotel-reviews)  
Project Report (PDF): [Final Project Report](https://github.com/NancyKiplimoAnalyst/r-textmining-airbnb-hotel-reviews/blob/main/Finalprojectreport_Nancy.pdf)  
Rendered Analysis (PDF): [Rendered Analysis](https://github.com/NancyKiplimoAnalyst/r-textmining-airbnb-hotel-reviews/blob/main/RenderedAnalysis.pdf)  

## Data Sources  
Both datasets were obtained from Kaggle:  
[TripAdvisor Hotel Reviews Dataset](https://www.kaggle.com/datasets/andrewmvd/trip-advisor-hotel-reviews/code)  
[Airbnb Reviews Dataset](https://www.kaggle.com/datasets/muhammadahmedansari/airbnb-dataset)  

### Dataset Overview  
Hotel Reviews (20,491 reviews): Contains text reviews and numerical ratings (1–5 scale).  
Airbnb Reviews (342,904 comments): Contains textual reviews with metadata (listing ID, reviewer ID, date, etc.).  

##  Methodology  
This project followed the CRISP-DM framework  
1.Business Understanding – Define how hotels can use insights from customer reviews.  
2.Data Understanding– Explore the structure of both datasets.  
3.Data Preparation – Handle missing values, tokenize text, and classify hotel ratings into positive/neutral/negative. Airbnb reviews were classified using the Bing lexicon.  
4.Modeling –  
   - Sentiment analysis (positive/negative/neutral classification).  
   - Term frequency (TF), TF-IDF, n-grams (bigrams, trigrams, quadgrams).  
   - Topic modeling (LDA) for negative hotel reviews.  
   - Seasonal trend analysis of Airbnb reviews.  
5.Evaluation – Compare Airbnb and hotel sentiment patterns.  
6.Deployment – Insights documented in reports and visualizations.  

## Key Findings  
Airbnb Positive Themes: Guests often praised location, cleanliness, host friendliness, and comfort.  
Hotel Negative Themes: Frequent complaints were about service, staff, and food.  
Airbnb Negative Themes: Complaints often related to specific amenities (e.g., water supply, property issues).  
Sentiment Distribution: Airbnb reviews had higher positive feedback overall but showed more variability than hotels.  
Seasonal Trends: Airbnb reviews peaked in summer months (May–August).  

##  Tools & Packages  
- R packages: tidytext, dplyr, ggplot2, quanteda, wordcloud, topicmodels, lubridate,tinytex  
- Approach: Text mining, sentiment analysis, topic modeling, visualization.  

## Recommendations  
- Hotels should adopt positive Airbnb practices (personalized stays, friendliness, cleanliness).  
- Improve staff training and service consistency.  
- Address recurring complaints (food, staff, service quality).  
- Leverage seasonal insights for marketing strategies.  

---

Author: Nancy Kiplimo  
