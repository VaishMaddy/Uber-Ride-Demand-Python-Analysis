# NYC Uber Data Analysis Project

This repository contains a comprehensive analysis of Uber ride data in New York City from 2014-2015, exploring patterns in ride demand, weather impacts, and competition with traditional taxi services.

## Analysis Components

### 1. EDA and Clustering Analysis
- Exploratory data analysis of Uber pickup patterns
- K-means clustering to identify high-demand zones
- Temporal analysis (hourly, daily, monthly patterns)
- Feature engineering for improved insights

### 2. Demand Analysis and Competitive Dynamics
- Analysis of ride demand patterns
- Impact of weather on ride frequency
- Competition analysis with yellow/green taxis
- Temporal and spatial fixed effects analysis

## Key Findings

1. Temporal Patterns
   - Clear peaks in demand during commuting hours
   - Distinct weekend vs weekday patterns
   - Seasonal variations in ride frequency

2. Spatial Distribution
   - Identified high-demand zones through clustering
   - Airport and business district concentration
   - Borough-specific demand patterns

3. Competition Dynamics
   - Strong correlation between Uber and yellow cab demand
   - Weather has minimal impact on ride distribution
   - Location-specific competitive patterns

## Technologies Used

- Python 3.x
- Key Libraries:
  - Pandas
  - NumPy
  - Scikit-learn
  - Statsmodels
  - Matplotlib
  - Seaborn

## Data Sources

- FiveThirtyEight's Uber Pickup Data (2014-2015)
- NYC Taxi & Limousine Commission
- Weather data for precipitation analysis

## Visualization Examples

The notebooks include various visualizations:
- Temporal heatmaps
- Spatial clustering plots
- Demand pattern graphs
- Correlation matrices

## Acknowledgments

- FiveThirtyEight for the dataset
- NYC TLC for additional data
- Uber for inspiring this analysis
