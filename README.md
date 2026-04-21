# 🚴 Paris Cycling Traffic Analysis — Python & Power BI

This project explores cyclist traffic patterns in Paris using data from 
bike counters installed across the city as part of the Plan Vélo: Act 2 
initiative launched in 2021. The analysis supports urban planning decisions 
by visualising traffic distribution by arrondissement and time of day.

---

## 🗃️ Data Sources

- **Cycling Traffic Data**: Hourly cyclist counts from 101 counters across 
  Paris (opendata.paris.fr), 945,000+ rows covering 2022–2024
- **Street Address Data**: Arrondissement mapping for counter locations

---

## 👤 My Contribution

This was a team project (3 members) completed as part of the 
DataScientest Data Analyst Bootcamp (September 2024 cohort).

**My individual work:**
- Loaded and explored the raw dataset (945,000 rows, 16 columns)
- Cleaned and structured the data using Python (Pandas, NumPy):
  - Renamed French columns to English
  - Converted datetime columns to correct format
  - Extracted date, time, day of week, month, year into separate columns
  - Separated geo-coordinates into latitude and longitude
  - Removed irrelevant columns
  - Identified and handled outliers (2 extreme values dropped)
  - Excluded incomplete data periods (2022, October 2024, Olympic months)
- Performed EDA and data visualisation:
  - Distribution of hourly counts (histogram, boxplots)
  - Missing readings analysis by month
  - Weekday vs weekend traffic patterns
  - Olympic and Paralympic period comparison
- Built data visualisations in Python (Matplotlib) to explore traffic patterns, including distribution of hourly counts (histogram and boxplots), missing readings analysis by month and weekday vs weekend traffic comparisons

**Team contribution:**
- K-Means clustering (4 clusters, 3 features) to identify main cycling routes
- HDBSCAN clustering as alternative method
- Linear regression to predict afternoon counts from morning counts
- Interactive Folium and GeoPandas maps

---

## 🔍 Key Insights (from full team analysis)

- Central arrondissements (2nd, 10th, 11th) see the highest cyclist volumes
- 59% of all cycling traffic occurs during weekday morning and afternoon 
  commute hours
- Cycling traffic follows a seasonal pattern: peaks in June, drops in 
  winter months
- The Olympic period (July–August 2024) showed decreased cycling, 
  likely due to road closures and Parisians leaving the city

---

## 🛠️ Tools Used

Python • Pandas • NumPy • Power BI • Scikit-learn (team)

---

## ✅ What I Learned

- Cleaning and structuring large real-world civic datasets with Python
- Handling datetime data, outlier detection, and missing value analysis
- Building exploratory data visualisations in Python to surface patterns and communicate findings to the team
- Collaborating on a data science team project with clear role attribution

