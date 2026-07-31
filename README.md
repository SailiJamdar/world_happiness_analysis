# World Happiness Report Analysis (2021)

## Overview
SQL and Python analysis of the 2021 World Happiness Report, examining 
happiness scores across 149 countries and identifying key explanatory factors.

## Tools Used
Python (Pandas) for cleaning → SQLite for querying and analysis

## Key Insights
- Finland ranks happiest overall (7.84), with Nordic/Western European 
  countries dominating the top 10
- North America/ANZ has the highest regional average (7.13) but with 
  only 4 countries in the sample; Western Europe's 6.91 average across 
  21 countries is a more statistically robust result
- Sub-Saharan Africa and South Asia rank lowest (4.49, 4.44)
- GDP per capita doesn't fully explain happiness: Singapore and Hong Kong 
  have very high GDP but noticeably lower happiness scores than similarly 
  wealthy nations like Switzerland and Denmark
- Hong Kong's gap aligns with lower social support and freedom scores; 
  Singapore's gap remained partially unexplained by GDP, social support, 
  or freedom — but its notably low (negative) Generosity score may be 
  a contributing factor

## Files
- `world_happiness_analysis.ipynb` - Full analysis notebook
- `happiness_cleaned.csv` - Cleaned dataset
