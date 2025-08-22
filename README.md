# Netflix Content Strategy Analysis 
This project analyzes Netflix’s 2023 content strategy using Python to uncover insights about release timing, content types, languages, seasons, weekdays, and viewership performance. By exploring patterns in how, when, and what Netflix releases, we identify strategies that drive audience engagement and maximize viewership.

**Objectives**
 - Analyze total viewership hours by content type (Movies vs Shows)
 - Identify the most popular languages and regions
 - Detect seasonal and monthly viewership trends
 - Evaluate release strategies across weekdays and holidays
 - Visualize correlations between release frequency and viewership impact
 - Highlight high-performing titles and content scheduling strategies

**Dataset**
 - Source: Netflix Content Dataset (2023)
 - Features:
    - - Title: Name of the content
    - - Content Type: Movie or Show
    - - Language Indicator: Language of content
    - - Release Date: Original release date
    - - Hours Viewed: Total hours content was watched in 2023

**Data Preparation**
 - Cleaned Hours Viewed (removed commas and converted to float)
 - Converted Release Date to datetime
 - Extracted:
    - - Release Month
    - - Release Day (weekday)
    - - Release Season (Winter, Spring, Summer, Fall)

**Key Visualizations & Insights**

**1. Viewership by Content Type**
 - Bar chart comparing total hours watched for Shows vs Movies
 - Shows dominate overall viewership on Netflix

**2. Viewership by Language**
 - Highlights the dominance of English content, followed by Korean, indicating global reach

**3. Monthly & Seasonal Trends**
 - Peaks observed in June and December
 - Fall season drives maximum engagement across the year

**4. Top 5 Titles by Viewership**

| Title                         | Type  | Language | Hours Viewed |
| ----------------------------- | ----- | -------- | ------------ |
| The Night Agent: Season 1     | Show  | English  | 812.1M       |
| Ginny & Georgia: Season 2     | Show  | English  | 665.1M       |
| King the Land: Limited Series | Movie | Korean   | 630.2M       |
| The Glory: Season 1           | Show  | Korean   | 622.8M       |
| ONE PIECE: Season 1           | Show  | English  | 541.9M       |

**5. Weekday Release Patterns**
 - Most content is released on Fridays
 - Viewership also peaks on Fridays, aligning with audience weekend habits

**6. Holiday Impact**
 - Strategic releases around New Year’s, Valentine’s Day, Halloween, and Christmas result in higher viewership

**Conclusion**
 - Netflix leans heavily on shows to drive engagement
 - Audience engagement peaks in Fall and December
 - Friday is the most strategic day for new releases
 - Viewership isn’t driven just by volume but timing + content appeal
 - Language diversity, especially Korean and English, is key to global success
