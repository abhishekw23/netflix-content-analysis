 Project Overview
Exploratory Data Analysis (EDA) on a Netflix dataset to understand how content is distributed across types, ratings, countries, and release years. The goal is to uncover trends in Netflix's content library and viewer-facing patterns.

 Objective

Compare the volume of Movies vs TV Shows on Netflix
Analyze the distribution of content ratings (TV-MA, TV-14, PG, etc.)
Study movie duration patterns
Track yearly content growth for Movies and TV Shows
Identify Top 10 countries producing the most Netflix content


 Dataset
DetailInfoFilenetflix1.csvColumnsshow_id, type, title, country, release_year, rating, duration

Tools & Libraries
ToolPurposePythonCore programmingPandasData loading, cleaning, manipulationMatplotlibData visualization

Data Cleaning Steps

Dropped rows with missing values in type, release_year, rating, country, duration
Reset index and regenerated show_id for clean sequencing
Converted duration column to integer for numeric analysis


 Visualizations
ChartDescriptionBar ChartMovies vs TV Shows countPie ChartDistribution of content ratingsHistogramMovie duration spread (in minutes)Scatter PlotNumber of titles released per yearHorizontal Bar ChartTop 10 countries by content countLine Chart (2 subplots)Movies and TV Shows released over the years

 Key Insights

Netflix library contains significantly more Movies than TV Shows
TV-MA is the most common content rating, indicating adult-focused content
Most movies have a duration between 80–120 minutes
Content production saw a sharp rise from 2015 onwards
The United States leads in content production, followed by India and the UK


 Project Structure
netflix-content-analysis/
│
├── Netfilx.ipynb        # Main analysis notebook
├── netflix1.csv         # Dataset
├── README.md            # Project documentation

How to Run

Clone this repository
Install required libraries:

bash   pip install pandas matplotlib

Open Netfilx.ipynb in Jupyter Notebook or VS Code
Run all cells
