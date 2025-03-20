# Datacleaning_movies
This repository is about data cleaning and manipulation as a comprehensive analysis for movies

# CSV Files Project - AQI India

## Project Overview
This project involves processing and analyzing CSV files related to movies. 

## File Structure
watch_history.csv
movies.csv
subscriptions.csv
users.csv
ratings.csv

## How to Use
### 1. Open the Raw CSV File
- Load `watch_history.csv` in Jupyter Notebook using Pandas:
  ```python
  import pandas as pd
  df = pd.read_csv("C:/Users/kasir/OneDrive/Documents/csv files project/CSV files/watch_history.csv")
  ```

### 2. Save and Access the Cleaned CSV File
- The cleaned file is saved as `watch_history_clean.csv`:
  ```python
  clean_path = "C:/Users/kasir/OneDrive/Documents/AQI India/csv files project/CSV files/watch_history_clean.csv"
  df.to_csv(clean_path, index=False)
  ```
- Open the cleaned CSV file in Tableau:
  1. Open **Tableau Desktop**.
  2. Click **"Text File"** under "Connect".
  3. Select `watch_history_clean.csv` and click **Open**.

## Requirements
- **Python 3.x**
- **Pandas** for data processing (`pip install pandas`)
- **Tableau Desktop** for visualization

## Future Enhancements
- Automate the cleaning process with a script.
- Add data visualizations and dashboards in Tableau.
- Perform deeper statistical analysis on AQI trends.

---
**Author:** Kasi Ramji Yalamarthi, Ramcharan Madineni
**Date:** March 2025
