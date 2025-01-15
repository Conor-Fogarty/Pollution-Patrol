# Pollution-Patrol

Pollution Patrol: Air Quality Analysis in NYC and Boston
Overview
Pollution Patrol is a data-driven project focused on analyzing air quality trends in NYC and Boston. The project utilized the OpenAQ API to collect data on PM2.5 and ozone (O₃) levels, leveraging Python, SQLite, and Pandas for data processing, analysis, and visualization.

Goals
Analyze PM2.5 trends across NYC and Boston to identify patterns and periods of high or low pollution.
Compare ozone levels between the two cities, investigating how urban factors like sunlight and traffic affect air quality.
Determine the days with the highest and lowest PM2.5 levels, exploring the factors contributing to these variations.
Data Collection and Preprocessing
Data Source: OpenAQ API (Nov 16, 2024 – Dec 16, 2024).
Selected 8 monitoring locations (3 in NYC, 5 in Boston) for comprehensive urban coverage.
Data stored in a SQLite database, structured with locations and measurements tables.
Preprocessing included handling missing data and standardizing pollutant measurements.
Key Tasks
Database Setup: Designed a robust SQLite schema with Python, enabling structured data storage and retrieval.
PM2.5 Analysis: Developed SQL-driven analytical functions to identify trends and visualize daily averages.
Ozone Comparison: Created functions to compare ozone levels across cities, incorporating visualizations for insights.
Extremes Identification: Analyzed peak and low PM2.5 levels to uncover impactful events and trends.
Challenges
Inconsistent data reporting from Boston's monitoring stations required additional locations and validation.
API documentation inaccuracies highlighted the need for real-time verification.
Results and Insights
PM2.5 Trends: Brooklyn experienced the highest pollution levels, while Manhattan and Queens showed similar, moderate patterns.
Ozone Comparison: Both cities demonstrated similar ozone trends, suggesting shared environmental and urban factors.
Extreme Days: NYC showed 40% higher pollution levels on its worst days compared to Boston.
Future Directions
Extend the analysis to explore seasonal pollution trends across multiple years.
Investigate the impact of major events (e.g., parades or holidays) on air quality.
Apply machine learning models to predict air pollution based on historical and environmental data.
Repository Features
Codebase: Includes Python scripts for data collection, database setup, analysis, and visualization.
Documentation: Comprehensive README detailing setup instructions, API usage, and analysis methods.
Visual Outputs: Plots and figures highlighting trends and comparisons in air quality metrics.
This project showcases advanced data engineering, analytical techniques, and collaborative problem-solving.
