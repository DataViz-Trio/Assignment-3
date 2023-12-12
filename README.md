# Data Visualization Assignment 3 Report

## Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Data Pre-Processing](#data-pre-processing)
- [Objective of Data Analysis](#objective-of-data-analysis)
- [Tasks](#tasks)
- [Analytics Workflow](#analytics-workflow)
- [Visualizations](#visualizations)
    - [Bar Chart - Distribution of Crime Counts Across Areas](#bar-chart---distribution-of-crime-counts-across-areas)
    - [Heatmap of Crime Incidents Across Los Angeles](#heatmap-of-crime-incidents-across-los-angeles)
    - [Seasonal Crime Comparison Across Areas](#seasonal-crime-comparison-across-areas)
    - [Yearly Crime Trends Over Days](#yearly-crime-trends-over-days)
    - [Moving Average - Small Multiples of Crimes Across Months Per Area](#moving-average---small-multiples-of-crimes-across-months-per-area)
    - [Bubble Map within each Area per Year](#bubble-map-within-each-area-per-year)
    - [Bar Graph of Arrests in the Detected Area Name](#bar-graph-of-arrests-in-the-detected-area-name)
- [Inferences](#inferences)
- [Work Distribution](#work-distribution)
- [References](#references)
- [Functions](#functions)

## Introduction
This README accompanies the Data Visualization Assignment 3 report, detailing the analysis, tasks performed, visualizations created, and insights derived from crime and arrest data in Los Angeles.

## Dataset
The dataset includes crime and arrest data from Los Angeles spanning from January 2020 to December 2023.

## Data Pre-Processing
The data underwent preprocessing steps, including cleaning and filtering out entries with unknown location coordinates.

## Objective of Data Analysis
The primary objective was to determine the impact of location and time on crime counts within various areas of Los Angeles.

## Tasks
Two main tasks were identified:
1. Identifying temporal periods when crime counts surged in different areas.
2. Examining the impact of crime surges on the quantity of arrests within specific areas.

## Analytics Workflow
The workflow encompassed various stages, including data loading, preprocessing, analysis, visualization, and deriving insights.

## Visualizations
Detailed visualizations were created to analyze crime patterns, including bar charts, heatmaps, seasonal comparisons, yearly trends, moving averages, and spatial distribution maps.

### Bar Chart - Distribution of Crime Counts Across Areas
This visualization illustrates the total number of reported crimes across different areas in Los Angeles. Each bar represents a distinct area, providing a visual comparison of crime frequency among various areas.

### Heatmap of Crime Incidents Across Los Angeles
The heatmap visualizes the spatial distribution and intensity of reported crime incidents across different areas in Los Angeles. It showcases the geographical concentration of crime incidents, offering insights into crime hotspots or patterns based on location coordinates.

### Seasonal Crime Comparison Across Areas
Small multiples showcase the comparison of seasonal crime incidents across different areas in Los Angeles. The plot comprises subplots representing distinct seasons—Fall, Spring, Summer, and Winter—depicting the count of reported crimes within various areas during these seasons.

### Yearly Crime Trends Over Days
This visualization presents the yearly trends of reported crime incidents from 2020 to 2023, demonstrating how the count of reported crimes fluctuates over the days of the respective years.

### Moving Average - Small Multiples of Crimes Across Months Per Area
The moving average plots visualize the 7-day average of crimes in each area for each year as a line chart. These plots help in understanding trends by smoothing out short-term fluctuations.

### Bubble Map within each Area per Year
This visualization uses unsupervised clustering to identify crime clusters within each area for each year. Each cluster represents the concentration of crimes, plotted on the Los Angeles map based on location coordinates.

### Bar Graph of Arrests in the Detected Area Name
Bar graphs depict the number of arrests in specific areas during particular time frames, helping understand the impact of crime surges on arrest quantities.


## Inferences
Insights were derived, highlighting specific periods and areas experiencing notable spikes in crime counts and analyzing the correlation between crime spikes and arrest quantities.

## Contributors
- Munagala Kalyan Ram
- Vikas Kalyanapuram
- Ramsai Koushik

## References

1. Crime Data 2020 to Present in Los Angeles: [Crime Data Link](https://catalog.data.gov/dataset/crime-data-from-2020-to-present)
2. Crime Dataset Description: [Crime Dataset Description Link](https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/2nrs-mtv8)
3. Arrest Data 2020 to Present in Los Angeles: [Arrest Data Link](https://catalog.data.gov/dataset/arrest-data-from-2020-to-present)
4. Arrest Dataset Description: [Arrest Dataset Description Link](https://data.lacity.org/Public-Safety/Arrest-Data-from-2020-to-Present/amvf-fr72/about_data)
5. Matplotlib Tutorial: [Matplotlib Tutorial Link](https://matplotlib.org/stable/tutorials/pyplot.html)
6. Seaborn Tutorial: [Seaborn Tutorial Link](https://seaborn.pydata.org/tutorial.html)
7. Folium Tutorial: [Folium Tutorial Link](https://python-visualization.github.io/folium/latest/getting_started.html)
8. A1 Report: [A1 Report Link](https://iiitbac-my.sharepoint.com/:b:/r/personal/kalyanram_munagala_iiitb_ac_in/Documents/A3/DV_Assginment_1_Report.pdf?csf=1&web=1&e=6jRABG)

## How to Run

### Prerequisites

Ensure you have the following installed:
- Python (version 3.x)
- Jupyter Notebook
- Required libraries: pandas, matplotlib, seaborn, folium, scikit-learn

### Steps

1. **Clone the Repository:**
```
git clone https://github.com/DataViz-Trio/Assignment-3.git
```
```
cd Assignment-3
```
2. **Install Dependencies:**
Ensure the required libraries are installed using the following command:
```
pip install pandas matplotlib seaborn folium scikit-learn
```
3. **Run the Notebook:**
Open Jupyter Notebook and navigate to the cloned repository.
Run the `DataVisualizationAssignment3.ipynb` notebook.

4. **Exploring Visualizations:**
- The notebook contains different sections, each generating specific visualizations. Execute each cell to generate the visualizations.
- Modify parameters or input data as needed to explore different aspects of the data or adjust the visualizations.

5. **Understanding Outputs:**
- The notebook generates various visualizations showcasing crime patterns, seasonal trends, spatial distributions, and more.
- Explore each visualization to understand the insights derived from the data.

<!-- 6. **Interacting with Visualizations:**
- Some visualizations might be interactive or customizable. Refer to specific cells or sections to understand their interaction capabilities.
- Follow provided instructions within the notebook for any interactive elements or user-defined parameters. -->



