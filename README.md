# Aircraft Accident Analysis Project
## Overview
This project is a comprehensive analysis of aircraft accidents, utilizing data to uncover trends, correlations, and insights into the causes and patterns of accidents. The goal is to provide actionable insights to assist in making a data-driven decision by the company in purchase of a low-risk aircraft.

## Objectives
Identify trends and patterns in aircraft accidents over time.
Correlate weather conditions, aircraft models, and other factors with accident severity.
Provide visual insing Python visualizations.
Offer actionable recommendations for stakeholders within the organization.

## Data Source
The dataset is Kaggle AviationData.csv
It contains detailed information about aircraft accidents, including:
Aircraft make and model
Weather conditions
Locations
Injury severity
Date and time of accidents
Aircraft damage and category

## Data Cleaning
The dataset underwent rigorous cleaning to ensure accurate analysis:

## Missing Values:
Addressed some missing data by replacing missing values with median and mode, and dropping values.
Column Adjustments:

Extracted numerical data from complex fields (e.g., Fatal(2)).
Removed redundant or irrelevant columns like Unavailable in injury severity.
Deduplication:

Dropped duplicate rows for cleaner analysis.

## Key Visualizations

### Trends Over Time

Line chart showing accidents over the years to identify spikes and declines.
Accident Locations

Heatmap and area charts to reveal high-risk areas and their weather patterns.
Aircraft Makes and Models

Bar and pie charts highlighting the most accident-prone aircraft.
Weather Conditions

Correlation analysis between weather and accident frequency using scatter plots.
Injury Severity by Aircraft Make

Clustered bar charts showing injury severity for each aircraft type.
Tableau Dashboards
Interactive dashboards were created to provide dynamic and detailed insights. Key features:

Filters for weather conditions, injury severity, and aircraft category.
Drill-down functionality to explore accidents by location and year.
Comparisons between accident frequency and onboarded passenger counts.

## Insights and Recommendations
### High-Risk Weather Conditions- Most accidents occur during specific weather patterns (e.g., IMC conditions).
     Recommendation: Enhance weather forecasting tools and pilot training.
     
### Aircraft Models with High Accident Rates
    Certain models and makes are associated with more accidents.
    Recommendation: purchase with preference on a specific model

### Location-Specific Trends - Some regions exhibit higher accident rates due to weather or terrain.
      Recommendation: Improve airport infrastructure and navigation aids.
### Engine Types and Safety - Engine types influence accident likelihood.
     Recommendation: purchase with preference on low-risk engines

## Technology Stack
Data Cleaning and Analysis: Python (Pandas, NumPy)
Visualization: Matplotlib, Tableau
Version Control: Git and GitHub

## How to Run the Project
Clone the repository:
git clone https://github.com/<username>/aircraft-accident-analysis
Install dependencies:
pip install -r requirements.txt
Run the Python scripts for data analysis.
Open the Tableau dashboard to interact with the visualizations.

## Future Work
Integrate machine learning models for accident prediction.
Explore deeper correlations between maintenance schedules and accidents.
Develop a web application for stakeholders to access insights in real-time.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request.

## Contact
For inquiries or suggestions, please reach out to:

Name: Linet Okinyi
Email: linetawino2018@gmail.com
This README provides a detailed and professional overview of the project, suitable for stakeholders, collaborators, and anyone interested in exploring the analysis. Let me know if you need further adjustments!
