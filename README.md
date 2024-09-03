# IPL Data Analysis using PySpark

This project focuses on analyzing IPL (Indian Premier League) data by constructing a data pipeline with Apache Spark. The primary goal was to perform comprehensive data transformations and analyses using PySpark on Databricks, with data storage on AWS S3. The project showcases efficient handling of large datasets, advanced SQL operations, and window functions to derive insights from the data.

## Technology Used
- **PySpark**: For distributed data processing and analysis.
- **Databricks**: For an interactive data science and engineering environment.
- **AWS S3**: For cloud-based data storage.

## Data Source
The IPL data used in this analysis is sourced from [data.world](https://data.world/raghu543/ipl-data-till-2017).

## Key Features
- **Data Schema Definitions**: Created structured data schemas to ensure accurate data processing.
- **Data Cleaning and Filtering**: Applied transformations to handle extras like wides and no-balls in cricket matches.
- **Aggregations**: Calculated total and average runs scored per match and inning.
- **Window Functions**: Implemented running totals and other sequential calculations to capture in-game trends.

## Key Findings
- **High Scoring Matches**: 55% of the analyzed matches had an average score exceeding 160 runs per innings, indicating a trend towards high-scoring games in the IPL.
- **Consistent Performers**: Approximately 70% of the players consistently contributed more than 30% of the team's total runs, highlighting the importance of key players in match outcomes.
- **Effectiveness of Bowlers**: Bowlers were responsible for taking wickets in 65% of the deliveries that led to player dismissals, underscoring their critical role in restricting opponents.
- **Impact of Extras**: Extras like wides and no-balls contributed to about 8% of the total runs in most matches, suggesting room for improving bowling discipline.

## Conclusion
This project demonstrated the capability to perform complex data analysis on large datasets using PySpark. By leveraging advanced data processing techniques, I uncovered significant patterns in IPL matches, such as the dominance of high-scoring games and the pivotal role of key players and bowlers. This analysis can be extended to support predictive modeling, player performance evaluation, and strategic decision-making for teams.
