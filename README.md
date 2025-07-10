# IPL-Data-Engineering-Project-End-to-End-Pipeline-Using-Databricks-PySpark

This project demonstrates an end-to-end data engineering workflow using IPL (Indian Premier League) data. The solution includes data ingestion, transformation using PySpark, SQL-based analysis, and visualization – all within the Databricks environment.

⚙️ Tech Stack Used

Apache Spark (PySpark) – Distributed data processing
Databricks – Unified analytics platform for Spark
Amazon S3 – Source of IPL dataset
Python – Programming language used
CSV Files – Input IPL data format

✅ Data Preprocessing
Loaded CSV files from DBFS (Databricks File System)
Casted columns to appropriate data types
Handled null values and removed unnecessary columns

📊 Exploratory Analysis Using Spark DataFrame APIs
Total Matches Played
Matches Played per Season
Most Successful Teams (based on win count)
Player of the Match Awards (top recipients)
Top Batsmen by Total Runs
Top Bowlers by Wickets Taken
Most Sixes Hit by Players
Matches Played at Different Venues
Toss Decisions and Outcomes
Win Percentage When Batting First vs Second

🧹 Transformations
GroupBy operations
Aggregations (count, sum, avg)
Filtering and ordering
Join operations between matches and deliveries datasets

🧠 Key Insights
The team with the most wins across all seasons.
Which player won the most "Player of the Match" awards.
Top venues by number of matches hosted.
Batting-first vs chasing win percentages.
Players with highest number of sixes and runs.
