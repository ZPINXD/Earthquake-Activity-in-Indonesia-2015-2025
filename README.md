# Earthquake Activity in Indonesia (2015–2025)
![Dahsboard Earthquake Analytics](https://github.com/user-attachments/assets/1ae9cd29-3df1-494d-b1db-5d8d1a9e602b)


## Overview

This project analyzes earthquake activity in Indonesia using historical seismic data covering the period **2015–2025**. The main objective is to explore temporal patterns, magnitude characteristics, and spatial distribution of earthquakes, and to present the results through an interactive **Power BI dashboard**.

The project focuses on data cleaning, transformation, exploratory analysis, and visualization to generate insights that are easy to understand for a general audience.

---

## Objectives

* Analyze earthquake frequency and trends over time
* Understand magnitude distribution and extreme events
* Identify regions most frequently affected by earthquakes
* Build an interactive dashboard for exploration and storytelling

---

## Dataset

* **Platform Source:** Kaggle
* **Original Data Provider:** United States Geological Survey (USGS)
* **Data Type:** Earthquake catalog (time, location, magnitude, depth, and metadata)
* **Original Time Range:** 2008–2025
* **Analysis Time Range:** 2015–2025 (filtered)
* **Geographic Scope:** Indonesia

> The dataset is publicly available and used for educational and analytical purposes only.

---

## Tools & Technologies

* **Python (Jupyter Lab)**: Data cleaning and preprocessing

  * pandas, numpy
* **Microsoft Excel**: Initial exploration and pivot-based summaries
* **Power BI**: Interactive dashboard and visual analytics
* **GitHub**: Project documentation and version control

---

## Data Preparation Steps

1. Imported raw earthquake data from Kaggle
2. Selected relevant columns (event ID, datetime, latitude, longitude, depth, magnitude, location)
3. Converted data types:

   * Datetime to proper datetime format
   * Latitude, longitude, magnitude, and depth to numeric values
4. Removed records with missing critical values (datetime, magnitude, location)
5. Filtered data to the period **2015–2025**
6. Exported cleaned dataset to a new CSV file for visualization

---

## Key Insights 🔍

### Earthquake Overview 🌍

* **Total Earthquakes:** 90,629 recorded events
* **Average Magnitude:** ~3.5
* **Maximum Magnitude:** 7.9 (Java, Indonesia)
* **General Pattern:** Frequent low to moderate earthquakes with occasional high-impact events

### Magnitude Characteristics 📊

* Most earthquakes fall within the **2.0 – 4.0 magnitude range**
* High-magnitude earthquakes (>6.0) are **rare but critical**
* Magnitude distribution is **right-skewed**, dominated by smaller events

### Most Frequent Locations 🗺️

1. Minahassa Peninsula, Sulawesi
2. Sulawesi, Indonesia
3. Sumbawa Region, Indonesia
4. Java, Indonesia
5. Northern Sumatra

**Interpretation:**

* These regions lie along major tectonic plate boundaries
* High frequency reflects active subduction zones and fault systems
* Frequent low-magnitude earthquakes indicate continuous tectonic stress release

---

## Dashboard Description (Power BI)

The Power BI dashboard includes:

* **Time-based analysis:** Earthquake trends by year
* **Magnitude analysis:** Distribution and filters by magnitude range
* **Spatial analysis:** Earthquake locations across Indonesia
* **Interactive filters:**

  * Time Range (Year)
  * Magnitude Range
  * Location

The dashboard is designed for exploratory analysis and high-level insight generation.

---

## Repository Structure

```
├── data/
│   ├── raw/               # Original dataset from Kaggle
│   └── processed/         # Cleaned dataset used for analysis
├── notebooks/             # Jupyter notebooks for data cleaning
├── dashboard/             # Power BI file (.pbix)
├── README.md
```

---

## Limitations

* Earthquake data completeness depends on reporting accuracy
* Smaller earthquakes may be underreported in certain regions
* Analysis focuses on frequency and magnitude, not damage or casualties

---

## Future Improvements

* Add depth-based analysis
* Integrate tectonic plate boundary data
* Compare pre- and post-2015 seismic activity
* Deploy dashboard to Power BI Service for public access

---

## Data Source Attribution

* Data obtained from **Kaggle**
* Original data provided by the **United States Geological Survey (USGS)**

---

## Author

**Geovano Galan W.P.**
Data Analytics / Data Visualization Project

---

## License

This project is for educational and non-commercial purposes only.
