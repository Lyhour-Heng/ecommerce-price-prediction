# 🇰🇭 Cambodia Flood Risk Data Cleaning – ML Project (Data Cleaning Only)

This project focuses on **cleaning and preparing a flood risk dataset for Cambodia**. The goal is to preprocess raw environmental data (rainfall, river level, etc.) and prepare it for future machine learning tasks such as flood prediction.

> 🔍 This is a **data cleaning only** project — no ML model is trained as per assignment requirements.

---

## 🧠 Project Overview

| Item                      | Description                                      |
|---------------------------|--------------------------------------------------|
| **Title**                 | Cambodia Flood Risk Data Cleaning                |
| **Societal Impact**       | Helps improve disaster preparedness & response   |
| **Problem Statement**     | Raw flood-related data is messy and unusable     |
| **Research Questions**    | What: Flood risk patterns? Why: Predict disasters? How: Clean data for ML |
| **Contribution**          | Cleaned, structured dataset for Cambodia floods  |
| **Dataset Type**          | Synthetic / Simulated (Secondary)               |
| **ML Use**                | No model training (Data Cleaning only)           |

---

## 📁 Dataset Features

| Column Name            | Description                                |
|------------------------|--------------------------------------------|
| `ID`                   | Entry identifier                           |
| `Date`                 | Date of data entry                         |
| `Region`               | Province or region in Cambodia             |
| `Rainfall_mm`          | Rainfall amount in millimeters             |
| `River_Level_m`        | River height in meters                     |
| `Soil_Saturation_pct`  | Soil saturation percentage                 |
| `Temperature_C`        | Temperature in Celsius                     |
| `Flood_Occurred`       | Whether a flood occurred (Yes/No)          |
| `Season`               | Automatically assigned: Rainy or Dry       |

---

## 🧼 Cleaning Steps

- Removed duplicate records
- Converted dates to proper format
- Renamed columns for clarity
- Standardized region names
- Handled missing values
- Added a new `Season` column based on month
- Sorted dataset by date
- Saved the cleaned data into CSV format

---

## 🛠️ Tools Used

- Python
- Pandas
- NumPy
- Visual Studio Code

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/YOUR_USERNAME/cambodia-flood-cleaning.git
   cd cambodia-flood-cleaning
