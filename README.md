Project Overview:-

In today's fast-moving startup ecosystem, investor confidence and market perception can shift rapidly based on media coverage. This project analyzes real-time startup news articles, applies sentiment analysis using Python and NLP, and visualizes insights in an interactive Power BI dashboard.

The goal is to help investors, founders, and stakeholders understand:

->Which startups and sectors are gaining positive media traction

->Which ones are being flagged as risky or uncertain

->What media sources are optimistic or critical about startups

Objectives:-

Extract live startup-related news headlines and summaries using News API.

Analyze sentiment (positive, neutral, negative) using TextBlob NLP.

Categorize startups as:

--Promising

--Neutral

--At Risk

Visualize key trends across news sources, sentiment types, and polarity strength.

Build a business-ready dashboard using Power BI with KPIs, filters, charts, and summaries.

Tools & Technologies Used:-

Data Collection -	News API (via Python requests)
Data Processing	- Python, Pandas, TextBlob (NLP)
Data Visualization -	Power BI
AI Integration - Sentiment Polarity & Labeling
Interactivity -	Power BI Slicers, KPIs, Tooltips
Reporting -	Power BI Web URL & GitHub

Dataset Details:-

~100 startup-related articles fetched using NewsAPI based on keywords like startup, funding, valuation, Series A, etc.

Extracted fields: Title, Description, Source, Published Date, URL

Sentiment scores calculated using TextBlob polarity:

> 0.1 → Promising

-0.1 to 0.1 → Neutral

< -0.1 → At Risk
