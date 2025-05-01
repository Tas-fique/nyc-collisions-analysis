# nyc-collisions-analysis
“Analyzing NYC motor vehicle collisions using Python and Tableau to uncover traffic safety insights.”
# 🚗 NYC Motor Vehicle Collisions Analysis

## 🧠 Problem Statement
What are the most dangerous locations and times for motor vehicle collisions in NYC? How can we use this data to inform traffic safety decisions?

## 📊 Dataset
- **Source:** NYC Open Data — [Motor Vehicle Collisions - Crashes](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95)
- Size: ~1.7 million records
- Preprocessing included:
  - Removing nulls for key fields (location, date/time)
  - Converting date/time to datetime objects
  - Aggregating by borough, hour, and street name

## 🔧 Tools Used
- Python (Pandas, Matplotlib, Seaborn)
- Tableau (for interactive dashboards)
- Jupyter Notebook

## 🛠 Methods
- Time-based trend analysis (injuries by hour/day)
- Spatial hotspot detection (top intersections by injuries)
- Correlation analysis between contributing factors and outcomes
- Dashboard created for stakeholder visibility

## 🔍 Key Findings
- Accidents spike around 5–6 PM (rush hour)
- Manhattan has the highest number of collisions but fewer fatal ones
- Driver inattention/distraction is the top contributing factor
- Certain intersections consistently rank among the most dangerous

## 📎 Deliverables
- 📓 [Notebook: Data Cleaning + EDA (GitHub)](link-to-notebook)
- 📈 [Interactive Tableau Dashboard](link-to-tableau)
- 📄 Summary Report (PDF or Google Doc — optional)

## 🙌 Reflection
This project taught me how to handle large, messy public datasets and use visual storytelling to highlight actionable patterns. In the future, I’d like to expand this with predictive modeling using time series forecasting (Prophet or ETS).
