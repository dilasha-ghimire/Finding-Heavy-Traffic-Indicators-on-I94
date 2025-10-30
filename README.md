# Indicators of Heavy Traffic on I-94

## Overview

This project analyzes the **Metro Interstate Traffic Volume** dataset to identify **key indicators influencing heavy traffic** on the westbound section of the I-94 highway. The goal is to uncover how factors such as **weather conditions, time of day, and day of the week** affect traffic volume patterns.

The analysis is performed using **Python** in a **Jupyter Notebook**, leveraging data visualization and statistical analysis tools to extract insights and trends from real-world traffic data.

---

## Dataset

**File:** `Metro_Interstate_Traffic_Volume.csv`  
**Source:** [UCI Machine Learning Repository – Metro Interstate Traffic Volume](https://archive.ics.uci.edu/ml/datasets/Metro+Interstate+Traffic+Volume)  
**Author:** John Hogue

The dataset includes weather and traffic data collected from westbound traffic on Interstate 94 between Minneapolis and St. Paul, Minnesota.

**Key features include:**

- **Date/Time:** Timestamp of record
- **Temperature (°K)**
- **Rain/Snow/Clouds Indicators**
- **Weather Type**
- **Weather Description**
- **Traffic Volume**
- **Holiday**

---

## Project Files

- `Basics.ipynb` – Main Jupyter notebook containing data loading, cleaning, analysis, and visualizations
- `Metro_Interstate_Traffic_Volume.csv` – Dataset used for analysis
- `README.md` – Project documentation

---

## Tools and Technologies

**Language:** Python 3  
**Environment:** Jupyter Notebook

### Libraries Used

- `pandas` – Data manipulation and preprocessing
- `matplotlib` – Visualization and plotting
- `seaborn` – Advanced statistical visualizations

---

## Work Conducted

1. **Data Import and Exploration**

   - Loaded and inspected the dataset for structure, missing values, and data types.
   - Identified key variables affecting traffic volume.

2. **Data Cleaning**

   - Removed or handled null entries.
   - Formatted date and time fields for temporal analysis.

3. **Exploratory Data Analysis (EDA)**

   - Visualized traffic patterns by **hour, weekday, and month**.
   - Assessed correlations between **weather conditions** and **traffic volume**.
   - Detected peak hours and low-traffic intervals.

4. **Insights Extraction**
   - Compared traffic on **weekdays vs. weekends**.
   - Evaluated **weather effects** (e.g., rain, snow, clear skies) on volume levels.
   - Identified **time-of-day trends** (rush hours, off-peak).

---

## Key Findings / Conclusions

- **Traffic Volume Peaks**: Highest during **rush hours (7–9 AM and 4–6 PM)** on weekdays.
- **Weather Impact**: Traffic tends to be **heavier during certain bad weather conditions** such as _shower snow, light rain and snow, or proximity thunderstorms with drizzle_ because unfavorable weather makes people prefer driving instead of walking, biking, or using public transport.
- **Weekend Trends**: Reduced traffic flow observed on **Saturdays and Sundays**.
- **Temperature Correlation**: Mild temperatures correspond to higher traffic activity.

These findings can inform **infrastructure planning**, **traffic control systems**, and **policy decisions** for urban mobility optimization.

---

## References

- UCI Machine Learning Repository: [Metro Interstate Traffic Volume Dataset](https://archive.ics.uci.edu/ml/datasets/Metro+Interstate+Traffic+Volume)
- Wikipedia: [Interstate 94](https://en.wikipedia.org/wiki/Interstate_94)
