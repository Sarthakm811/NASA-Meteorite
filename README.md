Meteorite Landings Data Analysis (Python)
📌 Project Overview

This project performs exploratory data analysis (EDA) on the Meteorite Landings dataset to understand patterns related to meteorite discoveries across the world.

The analysis focuses on:

Distribution of meteorite falls and finds

Mass variations of meteorites

Year-wise discovery trends

Geographic spread of meteorite landings

🧰 Tools & Libraries Used

Python

Pandas – Data loading, cleaning, and manipulation

NumPy – Numerical operations

Matplotlib – Data visualization

Seaborn (if used) – Advanced visual analytics

📂 Dataset

Source: NASA Open Data (Meteorite Landings)

File Format: CSV

Key Features:

name – Meteorite name

mass – Mass of meteorite (grams)

year – Year of discovery

reclat, reclong – Latitude & longitude

fall – Fell or Found

recclass – Meteorite classification

🧹 Data Cleaning Steps

Removed missing and invalid values

Converted year column to proper datetime format

Handled outliers in meteorite mass

Filtered unrealistic latitude and longitude values

📊 Exploratory Data Analysis (EDA)
🔹 Meteorite Discovery Trend

Analyzed number of meteorites discovered per year

Observed increasing trend due to improved detection

🔹 Mass Distribution

Most meteorites have small mass

Very few meteorites are extremely heavy (outliers)

🔹 Fall vs Found

Compared meteorites that were observed falling vs found later

Majority are classified as Found

🔹 Geographic Analysis

Visualized meteorite landings across the globe

Higher density in accessible regions

📈 Visualizations Included

Meteorite count by year

Mass distribution (histogram)

Fall vs Found comparison (bar chart)

Scatter plot of meteorite locations

Top meteorite classes by frequency

🧪 Sample Code Snippet
plt.figure(figsize=(10,5))
meteorites['year'].value_counts().sort_index().plot()
plt.title("Meteorite Discoveries Over Time")
plt.xlabel("Year")
plt.ylabel("Count")
plt.show()

🔍 Key Insights

Detection rate increased significantly after 1900

Majority of meteorites are lightweight

Geographic discovery depends heavily on accessibility

Found meteorites dominate the dataset

🚀 Future Enhancements

Create interactive maps using Folium

Perform clustering on meteorite locations

Predict meteorite mass using ML models

Build a dashboard using Power BI / Tableau

▶️ How to Run the Project

Clone the repository

Install required libraries:

pip install pandas numpy matplotlib seaborn


Open meteriote.ipynb in Jupyter Notebook or Google Colab

Run all cells sequentially

👤 Author

Sarthak Mahajan
B.Tech CSE | Data Science & AI Enthusiast
