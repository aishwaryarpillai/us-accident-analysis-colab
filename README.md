# us-accident-analysis-colab
This data analysis project explores the U.S. Accidents dataset using Python and Google Colab. Includes visualizations, geospatial heatmaps, and insights into accident patterns by time, location, and weather related factors.

#  Project Overview
This repository contains an in-depth Exploratory Data Analysis (EDA) of traffic accidents across the United States. Using a dataset with millions of accident records, we uncover patterns and trends that can help improve road safety and inform policy decisions.

# Key Features:
Comprehensive Data Analysis: Statistical analysis of more than 2.24+ million accident records
Interactive Visualizations: Dynamic charts and plots using Seaborn and Plotly
Geospatial Analysis: Heat maps showing accident hotspots across different states and cities
Temporal Pattern Analysis: Insights into accident trends by time of day, day of week, and seasonal patterns
Weather Impact Study: Analysis of how weather conditions affect accident frequency and severity
Google Colab Integration: Ready-to-run notebooks for easy collaboration and sharing

# Dataset Information
The dataset used in this project contains:

Size: 2,243,939 accident records (127+ million data points)
Time Period: 2015 to 2019
Geographic Coverage: Contiguous United States
Data Sources: Real-time traffic APIs
Features: 57 columns including location, time, weather conditions, and severity

# Technologies Used

Python : Primary programming language
Pandas: Data manipulation and analysis
NumPy: Numerical computing
Matplotlib: Basic plotting and visualization
Seaborn: Statistical data visualization
Plotly: Interactive visualizations and maps
Folium: Geospatial visualization
Google Colab: Cloud-based development environment

# Analysis Highlights
# 1. Temporal Analysis

> Peak accident hours and days of the week
> Seasonal variations in accident frequency
> Impact of holidays and special events
> Weekend vs. weekday patterns

# 2. Geographical Analysis

> State-wise accident distribution
> City-level hotspot identification
> Highway vs. city street comparisons

# 3. Severity Analysis

> Distribution of accident severity levels
> Factors contributing to severe accidents
> Time and location patterns for high-severity incidents

# Getting Started
# Prerequisites
1. Python 3.7 or higher
2. Google Colab account (recommended)
3. Basic knowledge of data analysis and Python

# Dataset Access
Due to the large size of the dataset, you'll need to:
> Download the US Accidents dataset from Kaggle
> Upload it to your Google Colab environment or local directory
> Update the file path in the notebook accordingly


# Key Findings & Insights
# Traffic Patterns
1. Most accidents occur during rush hours (7-9 AM and 4-6 PM)
2. On Mondays, like other weekdays, the most number of accidents occur between 7am to 10am and between 4pm to 7pm which is most likely the hours people commute for work.
3. On Sundays the peak number of accidents occur during the afternoons between 10 am and 3pm unlike weekdays.

# Geographic Hotspots
1. As per the dataset, the top 5 states with most number of accidents are california(CA), Texas(TX), Florida(FL), North Carolina(NC), New York(NY)
2. The number of accidents are higer in the cities closer to the coastal lines as the population there is higher than that in the cities in the central region of America.

# Weather Correlations

1. Clear weather paradoxically shows high accident rates (higher traffic volume)
2. Temperature extremes correlate with increased accident frequency

# Contributing
Contributions are welcome! Here's how you can contribute:

1. Fork the repository
2. Create a feature branch (git checkout -b feature/amazing-analysis)
3. Commit your changes (git commit -m 'Add amazing analysis')
4. Push to the branch (git push origin feature/amazing-analysis)
5. Open a Pull Request

# Contribution Guidelines
> Ensure code is well-documented
> Add appropriate visualizations for new analyses
> Update README if adding new features
> Test notebooks thoroughly before submission

# References & Data Sources

Dataset: US Accidents Dataset(https://www.kaggle.com/datasets/sobhanmons/analysis-of-us-accidents) on Kaggle
Research Paper: Moosavi, Sobhan. "A Countrywide Traffic Accident Dataset." 
Traffic APIs: MapQuest, Bing Maps, and other traffic data providers

# Author
Aishwarya R Pillai
GitHub: @aishwaryarpillai (https://github.com/aishwaryarpillai)


# Acknowledgments

> Kaggle community for providing the comprehensive dataset.
> Google Colab for providing free GPU/TPU resources.
> Python community for excellent data science libraries.
> All contributors and users who provide feedback.


⭐ If you found this project helpful, please consider giving it a star! ⭐
*This project is for educational and research purposes. Always follow traffic safety guidelines and local regulations.*
