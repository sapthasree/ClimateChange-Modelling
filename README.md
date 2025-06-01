# Climate Change Modeling Using Machine Learning (2024)
## Tools & Technologies  
**Platform**: Jupyter Notebook  

**Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  

**Techniques**: Machine Learning, Time Series Analysis, Feature Engineering  

**Domain**: Climate Science & Data Science  

## Objective
This project performs sentiment and engagement analysis on sample Facebook comments related to climate change, inspired by posts from NASA’s page. The goal is to understand public opinion and interaction trends over time.

### Main Goals:
Analyze how people feel (positive, negative, or neutral) about climate change topics  

Measure and visualize engagement trends (likes & comments)  

Identify the most common words and patterns in climate discussions  

Explore how sentiment influences user engagement  

## 1. Data Collection
The data was collected from reliable sources such as NASA, NOAA, and the IPCC, and includes:  

Atmospheric indicators: CO₂, SO₂, CH₄  

Geographical coordinates: Latitude, Longitude  

Climate variables: Temperature, Solar Radiation, Cloud Cover  

Facebook interaction data: Date, LikesCount, CommentsCount, Text (comment body)  

Public sentiment toward NASA’s climate-related posts  

## 2. Data Exploration  
Dataset includes 76 features and over 79,000+ observations  

Summary statistics, missing values, and the distribution of key variables (like emissions) were analyzed  

Average likes and comments per post calculated  

Distribution of sentiment labels observed  

## 3. Data Preprocessing  
Converted date columns into proper datetime format  

Chronologically sorted the comments  

Extracted year and month for time series analysis  

Created a basic sentiment classifier using keyword matching (Positive, Negative, Neutral)  

## 4. Exploratory Data Analysis (EDA)  
Descriptive statistics for likes and comments  

Checked for and handled missing values  

Visualized engagement trends over time  

Analyzed sentiment distribution with pie charts  

Extracted word frequency using regular expressions  

## 5. Visualization
Time Series Plots: Average likes and comments per month  

Bar Charts: Engagement levels grouped by sentiment  

Boxplots: Distribution of likes/comments per sentiment type  

Pie Chart: Overall sentiment distribution  

Word Cloud: Common words in Facebook comments  

## 6. Sentiment Analysis
A rule-based approach using predefined lists of positive and negative words was applied.  

Results:  
Positive: ~60%  

Neutral: ~30%  

Negative: ~10%  

Positive comments generally received more likes on average  

## 7. Engagement vs. Sentiment Insights
Positive comments had slightly higher average likes and comments  

Sentiment remained fairly stable over time, with a small increase in positive sentiment in 2023  

Comments expressing concern (e.g., "worried", "alarming") had lower engagement levels  

## 8. Text Analysis: Most Common Words
Top keywords included: climate, change, data, temperature, planet, science  

Indicates high public awareness and use of scientific terminology  

Potential for future clustering of comments by theme (fear, praise, call to action)  

## 9. Summary of Key Insights
Public sentiment was mostly positive or concerned  

Engagement (likes & comments) has slightly increased over time  

Frequent terms reflect a mix of scientific discussion and emotional concern  

Sentiment analysis can guide effective climate communication strategies  

## 10. Conclusion
This project showcases how simple text analysis and sentiment classification can provide meaningful insights into public discourse on climate change. Using tools like Pandas and Matplotlib, it's possible to track shifts in engagement and perception — offering valuable data for climate communicators, researchers, and policymakers.

