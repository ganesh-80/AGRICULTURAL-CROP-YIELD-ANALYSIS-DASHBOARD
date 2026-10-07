# 🌾 Agricultural Crop Yield Analysis Dashboard

An interactive **Microsoft Excel dashboard** that analyzes crop yield data across seven Indian states (2010–2022). It uses PivotTables, PivotCharts, calculated fields, KPI cards and slicers to compare crop performance by state, district, season, irrigation method, fertilizer and soil type.

<img width="1673" height="860" alt="Dashboard " src="https://github.com/user-attachments/assets/8fb650e9-a3c1-4b90-9f17-947a68085cc7" />


---

## 📌 Table of Contents

- [Project Objective](#-project-objective)
- [Dataset](#-dataset)
- [Tools & Features Used](#-tools--features-used)
- [Data Cleaning & Preparation](#-data-cleaning--preparation)
- [Analysis Performed](#-analysis-performed)
- [Dashboard Overview](#-dashboard-overview)
- [Key Insights](#-key-insights)
- [Challenges & Solution](#-challenges--solution)
- [Limitations](#-limitations)
- [Future Enhancements](#-future-enhancements)
- [Repository Structure](#-repository-structure)
- [How to Use](#-how-to-use)

---

## 🎯 Project Objective

To turn raw agricultural data into an interactive dashboard that answers questions such as:

1. Which state and district have the highest and lowest yield?
2. Which season gives the best yield?
3. Which crop performs best?
4. Which irrigation type is more productive?
5. Which fertilizer type gives better yield?
6. How do soil type, rainfall and temperature relate to yield?
7. Which crop, fertilizer, irrigation and season combinations look most productive?

---

## 📂 Dataset

- **File:** `Agricultural_Crop_Yield project.xlsx`
- **Records:** 500+
- **Period:** 2010 – 2022
- **Coverage:** Uttar Pradesh, Punjab, Bihar, Haryana, Maharashtra, Karnataka, West Bengal
- **Crops:** Cotton, Maize, Pulses, Rice, Sugarcane, Wheat

| Column | Description |
|---|---|
| Crop ID | Unique ID for each record |
| Date / Year | Date and year of the record |
| State / District | Location of cultivation |
| Season | Kharif, Rabi or Zaid |
| Crop Name | Cultivated crop |
| Area | Area in hectares |
| Production | Production in tonnes |
| Yield | Yield in Kg/Ha |
| Irrigation Type | Borewell, Canal, Drip, Rainfed |
| Fertilizer Type | Urea, DAP, NPK, Compost, Vermicompost |
| Rainfall | Rainfall in mm |
| Soil Type | Alluvial, Black, Laterite, Red, Sandy |
| Temperature | Temperature in °C |

---

## 🛠 Tools & Features Used

**Microsoft Excel**

- Excel Tables and formulas
- PivotTables and PivotCharts
- Bar, column, line, donut/pie and scatter charts
- Slicers for interactive filtering
- KPI cards
- Conditional formatting

---

## 🧹 Data Cleaning & Preparation

- Standardized the **Date** column into a consistent Excel date format
- Removed **duplicate** records
- Removed unnecessary **null/blank** values
- Corrected **data types** for Area, Production, Yield, Rainfall and Temperature
- Created calculated columns:

| Column | Formula |
|---|---|
| Yield per Acre | `Yield / 20` |
| Productivity | `Production / Area` |
| Efficiency | Input vs. output comparison measure |

---

## 📊 Analysis Performed

PivotTable analyses include:

- State vs Yield
- District vs Yield
- Season vs Yield
- Crop vs Yield
- Fertilizer vs Yield
- Irrigation vs Yield
- Soil Type vs Area / Production / Yield / Temperature
- Rainfall and Temperature vs Yield
<img width="1372" height="812" alt="Pivot Table" src="https://github.com/user-attachments/assets/a7b95b0f-5a44-4b0b-b702-1557717abeb5" />




---

## 🖥 Dashboard Overview

**KPI cards**

| KPI | Value |
|---|---|
| Total Yield | 19,97,353.9 Kg/Ha |
| Total Area | 24,847.23 Hectares |
| Total Rainfall | 3,52,135.12 mm |

**Charts**

- Total yield across states
- State/district highest vs lowest yield
- Seasonal yield trend
- Yield by crop category
- Yield per acre
- Fertilizer use vs yield
- Irrigation coverage
- Crop-wise yield by season
- District-wise fertilizer quantity
- Rainfall vs yield

**Slicers:** Crop Name, District, State, Year, Fertilizer Type, Irrigation Type

---

## 💡 Key Insights

- 🏆 **Best state:** Maharashtra (~3,12,625), followed by Bihar (~3,05,326). Karnataka was lowest (~2,43,159).
- 🌦 **Best season:** Rabi (~7,24,643), ahead of Zaid and Kharif.
- 🌱 **Top crops:** Sugarcane (~3,69,758) and Cotton (~3,52,441).
- 💧 **Irrigation:** Canal and Rainfed recorded higher yield values than Drip in this dataset.
- 🧪 **Fertilizer:** Urea and Compost showed strong performance.
- 🗺 Yield varies considerably between states and districts, suggesting geography and environment matter.

> These are patterns in this dataset and not proof of cause and effect.

---

## ⚠️ Challenges & Solution

**Problem:** Several PivotTables were placed on one worksheet and overlapped, which caused reference errors and saving/upload problems.

**Solution:** Follow the rule **one PivotTable = one worksheet**, and use the Dashboard sheet only for charts, KPI cards and slicers.

---

## 🚧 Limitations

- Results are based only on the available dataset
- Only seven states are covered
- Findings should not be generalized to all agricultural conditions
- Other factors affecting yield are not in the data
- Fertilizer and irrigation comparisons show association, not causation

---

## 🔮 Future Enhancements

- Add more states, districts and years
- Include crop prices and farmer income
- Add weather/climate and pesticide data
- Build a **Power BI** version
- Add geographic maps
- Machine-learning yield prediction and crop recommendation

---

## 📁 Repository Structure

```
├── Agricultural_Crop_Yield project.xlsx                          # Dataset, PivotTables and Dashboard
├── Agricultural Crop Yield Analysis Dashboard Project Documentation.docx   # Full project documentation
├── Dashboard .png                                                # Dashboard screenshot
├── Pivot Table.png                                               # PivotTable screenshot
└── README.md
```

**Workbook sheets:** `Agricultural_Crop_Yield` (raw data) · `Agricultural_crop_yield cleaned` · `Pivottable_1` · `Dashboard`

---

## ▶️ How to Use

1. Clone or download this repository:
   ```bash
   git clone https://github.com/<your-username>/AGRICULTURAL-CROP-YIELD-ANALYSIS-DASHBOARD.git
   ```
2. Open `Agricultural_Crop_Yield project.xlsx` in **Microsoft Excel** (2016 or later recommended for slicers).
3. Go to the **Dashboard** sheet.
4. Use the slicers to filter by crop, state, district, year, fertilizer or irrigation type.

---

## 👤 Author

**Your Name**
Kothapalli Ganesh

⭐ If you found this project useful, consider giving it a star!
