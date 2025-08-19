# prodigy-infotech-task-5-
#  Road Accident Data Analysis (UK Vehicles Dataset)

This project analyzes UK road accident data using the **Vehicles0515 dataset**.  
The goal is to uncover patterns in accident occurrences such as **time, location, weather conditions, severity, and vehicle involvement**.  
Visualizations and geospatial heatmaps are used to make the analysis more intuitive.  

---

##  Dataset
- **File:** `Vehicles0515.csv`  
- Contains detailed records of road accidents in the UK.  
- Includes columns such as:
  - `Date`, `Time` (when accident happened)  
  - `Latitude`, `Longitude` (location of accident)  
  - `Weather_Conditions` (conditions during accident)  
  - `Vehicle_Type`, `Casualty_Severity`, etc.  

---

##  Tech Stack
- **Python 3.9+**
- **Libraries Used:**
  - `pandas` → data manipulation  
  - `numpy` → numerical processing  
  - `matplotlib`, `seaborn` → data visualization  
  - `folium` → geospatial mapping (heatmaps)  

---

## Visualizations
The notebook/script generates the following insights:

1. **Accidents by Year** – how accident numbers change yearly.  
2. **Accidents by Hour of Day** – peak accident times (rush hours).  
3. **Accidents by Day of Week** – weekdays vs weekends comparison.  
4. **Accidents by Weather Conditions** – top conditions linked to accidents.  
5. **Severity Distribution** – how severe most accidents are.  
6. **Monthly Accident Trends** – line graph showing seasonal changes.  
7. **Day vs Hour Heatmap** – heatmap showing accident frequency.  
8. **Top Vehicle Types Involved** – which vehicles are most often in accidents.  
9. **Severity by Hour** – do late-night/early-morning accidents tend to be more severe?  
10. **Severity by Weather** – how bad weather impacts accident severity.  

---

##  Geospatial Hotspot Map
- A **heatmap** of accident hotspots is generated using `folium`.  
- The output file is saved as:  
