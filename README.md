# Aviation Accident Analysis

## 📌 Overview
Aviation safety is a global priority, and accident data provides valuable insights for identifying patterns and preventing future incidents.  
This project explores historical aviation accident records to analyze **trends, causes, and risk factors** associated with flight safety.  

The analysis leverages Python (Pandas, Seaborn, Matplotlib) to visualize accident trends, highlight high-risk flight phases, and examine factors such as weather and aircraft manufacturers.  

---

## 🎯 Objectives
The primary goals of this project are:
1. **Trend Analysis** – Track aviation accidents over time to evaluate improvements or risks.  
2. **Geographic Patterns** – Identify countries with the highest accident counts.  
3. **Flight Phase Risk** – Examine which flight phases (e.g., takeoff, cruise, landing) are most accident-prone.  
4. **Weather Impact** – Understand how weather conditions contribute to accidents.  
5. **Aircraft Manufacturer Analysis** – Highlight manufacturers with the most recorded accidents.  
6. **Fatality Trends** – Differentiate between fatal and non-fatal accidents and how they vary by phase of flight.  

---

## 📂 Dataset
- **File:** `AviationData.csv`  
- **Encoding:** `latin1`  
- **Size:** ~80,000+ records (varies by source)  
- **Source:** Aviation accident and incident records (public data)  

### Key Columns
| Column Name              | Description |
|---------------------------|-------------|
| `Event_Date`             | Date of the accident or incident |
| `Country`                | Country where the event occurred |
| `Broad_Phase_Of_Flight`  | Phase of flight (Takeoff, Climb, Cruise, Approach, Landing) |
| `Weather_Condition`      | Reported weather condition at the time of the accident |
| `Make`                   | Aircraft manufacturer |
| `Total_Fatal_Injuries`   | Number of fatalities in the accident |
| `Total_Serious_Injuries` | Number of serious injuries |
| `Total_Minor_Injuries`   | Number of minor injuries |
| `Total_Uninjured`        | Number of uninjured occupants |

---

## 🛠️ Tools & Requirements
This project uses **Python 3.8+** with the following libraries:  

```bash
pip install pandas seaborn matplotlib
pandas → Data cleaning & analysis

seaborn → Advanced statistical visualizations

matplotlib → Plot customization and charts

⚙️ Methodology
The project follows the CRISP-DM (Cross-Industry Standard Process for Data Mining) workflow:

Business Understanding

Define problem: aviation accidents remain a global safety concern.

Objectives: identify trends, high-risk factors, and actionable insights.

Data Understanding

Explore dataset structure, size, completeness, and quality.

Identify missing values, duplicates, and inconsistencies.

Data Preparation

Clean column names (Event.Id → Event Id).

Handle missing values (e.g., replacing with "Unknown" or 0).

Convert dates into datetime objects for trend analysis.

Analysis & Visualization

Accident counts by year, country, weather, and flight phase.

Fatal vs non-fatal accident distributions.

Manufacturer-level accident statistics.

Insights & Recommendations

Summarize findings and propose improvements.

🔑 Insights (Example Findings)

Accident frequency has declined over recent decades, indicating improved safety.

Landing and Takeoff phases show the highest number of accidents.

Weather conditions such as fog, storms, and rain contribute significantly to accidents.

A handful of manufacturers dominate accident records, largely because they produce the most aircraft

📌 Recommendations

Strengthen pilot training in high-risk phases (Takeoff & Landing).

Invest in weather prediction systems to reduce weather-related incidents.

Encourage aircraft manufacturers to adopt advanced safety designs.

Support global data sharing for continuous monitoring and trend detection

📁 Project Structure
Aviation-Accident-Analysis/
│── AviationData.csv         # Dataset
│── README.md                # Project documentation
Tableau Link :https://public.tableau.com/app/profile/edgar.james/viz/AviationDataAnalysisProject/AVIATIONANALYSISDASHBOARD
✍️ Author

Edgar Owuor
Data Science & Analysis Enthusiast

