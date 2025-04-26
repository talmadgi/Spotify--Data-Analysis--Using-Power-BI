
# 🎵 Spotify Data Analytics Using Power BI
# 🔹 Project Overview
This project aims to analyze Spotify user listening patterns over time — specifically focusing on artists, albums, and tracks. By creating dynamic dashboards and interactive reports, the project provides deep insights into how users engage with music across different time periods, weekdays vs weekends, and different listening behaviors.

The goal is to enable stakeholders to:

Understand music consumption trends.

Identify the most popular artists, albums, and tracks.

Examine year-over-year growth.

Improve personalization strategies and platform engagement based on listening patterns.

# 🔹 Key Insights & Findings

Aspect	Key Insights
Artists Analysis	- Tracked total artists played over time.
- Identified min and max artists listened by year.
- Discovered Top 5 most played artists.
- Differentiated weekday vs weekend artist listening patterns.
- Analyzed Latest Year (LY) vs Previous Year (PY) trends with YoY Growth Analysis.
Albums Analysis	- Tracked album engagement over months/years.
- Found listening patterns differences between weekdays and weekends.
- Identified the Top 5 albums.
- Compared album trends LY vs PY.
Tracks Analysis	- Monitored track listening trends across time.
- Identified the most frequently played tracks.
- Weekday vs weekend track playing behavior explored.
- Top 5 tracks recognized.
Listening Patterns	- Created Heat Map of peak listening hours.
- Used Scatter Plot Quadrant Analysis:
→ High Frequency + High Listening Time = Highly engaging tracks.
→ Low Frequency + High Listening Time = Niche tracks.
→ High Frequency + Low Listening Time = Short, catchy tracks.
→ Low Frequency + Low Listening Time = Less popular tracks.
# 🔹 Data Preprocessing & Cleaning Steps
Requirement Gathering:

Clear understanding of artist, album, and track metrics needed.

Data Walkthrough:

Studied data formats, fields, null values, and data types.

Data Connections:

Connected datasets from Spotify source or existing database.

Data Cleaning:

Handled missing values (e.g., missing artist names, track durations).

Standardized date formats.

Removed duplicates (e.g., duplicate song plays).

Ensured consistency across text fields (e.g., artist names capitalization).

Created derived columns (e.g., Weekday/Weekend flag based on play date).

Quality Check:

Manual validation and sanity checks on record counts and key attributes.

# 🔹 Technologies & Tools Used

Category	Technologies
Data Collection & Connection	Power BI Dataflows, DirectQuery/Import from CSV, SQL
Data Cleaning & Preprocessing	Power Query (M Language), DAX for transformations
Data Modeling	Star Schema (Fact tables and Dimension tables)
Data Processing	DAX Measures for KPIs like LY/PY comparison, YoY Growth
Visualization & Reporting	Power BI Desktop (Dashboards, Drill Down/Up, Drill Through Reports)
Export Options	CSV export from Drill Through for detailed records
# 🔹 Conclusion
This Spotify data analytics project successfully achieved its objective of visualizing and understanding music listening behaviors.

🔹Stakeholders can now easily track user engagement with artists, albums, and tracks over time.

🔹Weekday vs Weekend patterns offer actionable insights for personalized playlist curation.

🔹Top 5 entities and year-on-year growth allow deeper analysis into trending artists and changing music tastes.

🔹Drill Through features offer granular data exploration, enhancing the overall analytical experience.
