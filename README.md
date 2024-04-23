<h1>Project Overview</h1>

This project delves into the world of YouTube channel analysis, aiming to understand the factors that contribute to a channel's success. It compares two popular channels, StudyIQ and World Affairs, using Python, SQL, and Excel to uncover hidden trends and gain valuable insights.

<h2>Data Acquisition</h2>

Tool: Python
Method: YouTube Data API v3
Data Extracted:
Video Titles
Number of Views
Upload Dates
Number of Likes
Number of Comments


Data Storage:
The most suitable data storage solution depends on the volume and complexity of your data.
For smaller datasets: Consider storing the extracted data in a Python data structure like a list or dictionary.
For larger datasets: Explore options like CSV files, JSON files, or a database (e.g., SQLite) for efficient storage and retrieval.


<h2>Exploratory Data Analysis (EDA) with SQL</h2>

Create a Database: If you're using a database like SQLite, you'll need to create a schema (structure) to hold your data. This typically involves tables with columns for each data point (e.g., video_id, title, views, upload_date, likes, comments).
Import Data: Use Python's built-in database libraries (e.g., sqlite3) or a third-party library to connect to the database and import the extracted data into the tables.
SQL Queries: Write SQL queries to analyze the data. Some examples include:
Find average views per video for each channel.
Identify videos with the highest number of views or likes.
Calculate upload frequency per month for each channel.
Analyze trends in viewership over time.

<h2>Data Visualization with Excel</h2>

Export Cleaned Data: Export the processed data from your database or Python data structure into a format suitable for Excel import (e.g., CSV).
Create Charts and Graphs: Use Excel's built-in charting tools to visualize your findings. Examples include:
Bar charts to compare average views or upload frequency between channels.
Line charts to show viewership trends over time for each channel.
Scatter plots to explore potential correlations between video titles and view counts.
Analysis and Interpretation

Upload Frequency vs. Viewership: Analyze how upload frequency relates to viewership. The finding that World Affairs maintained competitive viewership with fewer uploads highlights the importance of content quality and audience engagement.
Host Change Impact: Investigate the impact of the host change on StudyIQ. The unexpected viewership increase despite lower uploads suggests potential audience preference for the new host's content style or a strategic shift in content focus. World Affairs' viewership decline might be unrelated to the host change, requiring further investigation.
