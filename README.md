# Weather-Data-Analysis-Exploratory-Data-Profiling

# 1. Project Overview

This project involved a deep-dive analysis of an hourly weather dataset containing over 8,700 records. Using Python and Pandas, I performed data cleaning and exploratory analysis to identify significant weather patterns, extreme weather events, and atmospheric correlations. The goal was to transform raw time-series data into a structured report of meteorological insights.

# 2. Tools and Technology Used

anguage: Python 3.10+

Libraries: Pandas (Data Wrangling)

Environment: Jupyter Notebook

# 3. Dataset Description

The dataset contains 8,784 hourly records for the year 2012.

Variables: 8 (Temperature, Dew Point, Humidity, Wind Speed, Visibility, Pressure, and Weather Condition).

Data Integrity: 0 null values found across all key columns after initial auditing.

Categorical Diversity: 50+ unique weather conditions identified (e.g., Clear, Snow, Fog, Thunderstorms)

# 4. Analysis Performed

Data Auditing: Executed .shape and .count() to verify the dataset size of 8,784 rows and ensured no missing values were present.

Data Standardization: Cleaned "bad data" in the 'Weather' column (e.g., standardized lowercase 'fog' to 'Fog') to ensure 100% accuracy in grouping.

Schema Optimization: Renamed the 'Weather' column to 'Weather Condition' and optimized data types for statistical analysis.

Multi-Variate Filtering: Developed complex logical filters using & (AND) and | (OR) operators to isolate specific environmental scenarios.

Statistical Variance Analysis: Calculated the volatility of humidity and pressure using .var() and .std() functions.

# 5. Key Insights
Unique Weather Patterns: Identified 34 unique wind speed profiles and 24 distinct visibility levels across the dataset.

Clear Sky Frequency: Isolated exactly 1,326 instances where the weather was "Clear," representing approximately 15% of the total year.

Wind Speed Analysis: Found that 474 times during the year, the wind speed was recorded at exactly 4 km/h.

Visibility Insights: Calculated a Mean Visibility of 27.66 km across all records, establishing a baseline for regional atmospheric clarity.

Atmospheric Stability: Measured a Pressure Standard Deviation of 0.84 kPa, indicating relatively stable barometric conditions throughout the recording period.

Extreme Condition Mapping: Identified 583 instances of "Snow" related weather, allowing for a precise analysis of sub-zero temperature trends.

High-Wind Visibility Outliers: Successfully queried 308 instances where Wind Speed exceeded 24 km/h while maintaining a Visibility of exactly 25 km, identifying specific "High-Wind Clear Day" patterns.

Frequency Distribution: Identified the Top 3 Weather Conditions:

Mainly Clear (2,106 records)

Mostly Cloudy (2,068 records)

Cloudy (1,728 records)

---

## ⭐ If you find this useful
Feel free to ⭐ the repository or fork it!
