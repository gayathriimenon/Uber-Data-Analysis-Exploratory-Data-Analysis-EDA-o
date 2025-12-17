# Uber-Data-Analysis-Exploratory-Data-Analysis-EDA

## Project Overview

This repository contains a complete Exploratory Data Analysis (EDA) project on Uber pickup data from 2015. The goal is to extract meaningful insights from raw timestamp data by deriving temporal features and visualizing demand patterns.

## Dataset

Source: Uber Pickups in New York City (2015) – based on publicly available datasets.

## Requirements

- textpandas
- numpy
- seaborn
- matplotlib


## Key Steps in the Analysis

### Data Loading & Cleaning:

- Load datasets using Pandas.
- Handle duplicates, missing values, and convert Pickup_date to datetime.
- Extract features: month, weekday, day, hour, minute.

### Temporal Analysis (2015 Data):

- Monthly pickups: Bar plot showing peak in June.
- Hourly pickups per day: Pivot table and heatmap.
- Daily pickups per month: Pivot table and heatmap.
- Weekday-hour rush: Heatmap of journeys by weekday and hour.

### 2014 Data Analysis:

- Concatenate monthly files.
- Similar feature extraction and rush hour visualization (heatmap).

### Full Dataset Analysis:

- Combine 2014-2015 data.
- Merge with taxi zones for borough-level insights.
- Visualizations: Bar plots for trips per borough/day/hour/weekday.
- Pairplot and boxplots to check correlations and outliers.

## Visualization 

### 1: Bar Plot of Pickup Counts by Month





<img width="1021" height="715" alt="Screenshot 2025-12-17 163713" src="https://github.com/user-attachments/assets/a5757481-40d7-42c2-a998-7eaa6e27e977" />

### 2: Bar Plot of Pickup Counts by Month broken down by day of the week




<img width="1048" height="779" alt="Screenshot 2025-12-17 164204" src="https://github.com/user-attachments/assets/e62b6aa7-f3d9-4864-9520-f2a1bb8d76f2" />

### 3. Total number of Uber pickups per hour of the day





<img width="1060" height="682" alt="py71" src="https://github.com/user-attachments/assets/53069b59-a8c1-4676-bdb3-2844bbd14fa7" />

### 4. Heat Map




<img width="1360" height="761" alt="py7" src="https://github.com/user-attachments/assets/f562ca85-909f-404a-81eb-adf8250c6514" />

### 5. Styled Pivot Table (Day vs. Hour Pickup Counts)



<img width="1002" height="822" alt="py8" src="https://github.com/user-attachments/assets/05d6b305-82f5-4104-8471-a5969eae2fda" />





