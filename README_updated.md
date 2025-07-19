
# ✈️ 101 Years of Air Accidents (1908–2009)

This project presents an interactive analysis of over 5,000 airplane accidents from the years 1908 to 2009.  
The goal was to visualize long-term trends in aviation safety, identify common causes, and explore patterns based on time, location, and type of accident using **Power BI**.

---

## 📁 Dataset

- Source: [Kaggle – Airplane Crashes and Fatalities Since 1908](https://www.kaggle.com/code/melissamonfared/airplane-crashes-analysis-eda/input?select=Airplane_Crashes_and_Fatalities_Since_1908.csv)
- Total records: 5,231
- Fields included (from model):
  - `Date`, `Year`, `Month`, `MonthNumber`, `Weekday`, `Time`, `Day Part`, `Decade`
  - `Country`, `Location`, `Operator`, `Type`, `CauseType`
  - `Aboard`, `Fatalities`, `Ground`, `Total Fatalities`, `Survivors`, `Fatality Rate`, `Survivors Rate`

⚠️ **Disclaimer**: Some values were manually categorized or created for the purposes of visualization and storytelling. These include:
- Grouped and interpreted `CauseType` (accident causes)
- Approximate classification of `Day Part` (time of day)

These additions are not part of the original dataset and are not intended to represent authoritative classifications.

---

## 🎯 Project Goals

- Visualize the number of accidents over time
- Analyze fatalities vs. survivors by year
- Identify the most affected countries and airlines
- Break down the most frequent causes of crashes
- Explore accident distribution by month, weekday, time of day, and decade
- Enable interactive filtering and deep exploration of the dataset

---

## ❓ Key Questions

- How did the number of accidents evolve over the 20th century?
- Which countries and operators had the most incidents?
- What were the most common causes of crashes?
- What was the survival rate across time?
- Are there any patterns by month, season, or time of day?

---

## 🧰 Tools Used

- [Power BI Desktop](https://powerbi.microsoft.com/)
- Power Query for data cleaning and transformation
- DAX for calculated measures and ratios
- Excel (for initial data inspection)

---

## 📌 Project Summary

- The number of air accidents peaked in the 1970s and has declined since.
- Pilot error is the most frequent cause of accidents, followed by mechanical failure and weather conditions.
- The survival rate across accidents is low – over 83% of cases involved fatalities.
- The dashboard allows users to explore these trends interactively and filter data by country, airline, cause, and more.

---

## 📂 Files Included

- `Airplane_Crashes.pbix` – Power BI report
- `Airplane_Accidents.pdf` – PDF version of the dashboard with key visuals
- `10_Model_View.png` – Screenshot of Power BI data model
- `README.md` – This description

---

### 👤 Author

**Tomáš Král**  
[LinkedIn Profile](https://www.linkedin.com/in/tomas-kral-/)  
📍 Czech Republic  
