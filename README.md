# 🛳️ Titanic Survival Analysis — Historical Data Exploration & Insight Generation  

## 🧭 Project Overview  

This project performs a **data-driven exploration of the RMS Titanic disaster** using both **Python** and **SQL** to uncover the factors that influenced passenger survival.  

Each analysis step (named as `figureX`) represents a distinct exploration or visualization, for example, comparing survival by gender, class, or age group.  
The repository demonstrates the full **data analysis workflow**, from data extraction and transformation (SQL) to visualization and insight generation (Python).  

**Key objective:** Combine technical EDA with historical interpretation to tell a meaningful data story.  


## 💡 Highlights  

✅ **Dual Approach** — Analysis performed using both SQL (for data manipulation) and Python (for EDA & visualization).  
✅ **Historical Insight** — Connects data patterns to real-world social and economic factors of the Titanic tragedy.  
✅ **Modular Structure** — Each “figure” file can be run independently for reproducible results.  
✅ **Practical Skills** — Demonstrates SQL joins, aggregation, filtering, and Python libraries for data visualization.  

---

## 🧰 Tools & Technologies  

| Category | Tools Used |
|-----------|-------------|
| **Programming Languages** | Python, SQL |
| **Libraries** | pandas, numpy, matplotlib, seaborn |
| **Data Handling** | CSV files for intermediate results |
| **Version Control** | Git & GitHub |
| **Visualization** | Bar charts, histograms, heatmaps, and survival comparison plots |

---

## 📂 Repository Structure  

├── fig15a.sql # SQL variant of Figure 15 analysis
├── figure15.sql # SQL query for survival by age/class
├── figure15.py # Python script generating Figure 15 visualizations
├── figure15.csv # CSV output from Figure 15 analysis
├── figure15a.csv # Extended version of Figure 15 results
│
├── figure2.py # Python EDA for basic survival distributions
├── figure2.sql # SQL equivalent for Figure 2
├── figure2.csv # Data output from Figure 2 analysis
│
└── README.md # Project documentation


## ⚙️ How to Run  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/ssrivatsava7/Titanic-Survival-Analysis-Historical-Data-Exploration-and-Insight-Generation.git
cd Titanic-Survival-Analysis-Historical-Data-Exploration-and-Insight-Generation
```

2️⃣ Install Dependencies
```bash
pip install pandas numpy matplotlib seaborn
```

3️⃣ Run Python Scripts
```bash
python figure2.py
```

4️⃣ Run SQL Queries
Use your preferred SQL environment (SQLite, PostgreSQL, etc.):
```bash
.read figure15.sql
```
Make sure your Titanic dataset (e.g., train.csv) is available in your local environment.

📊 Analytical Focus
This analysis investigates:
-Survival probability by gender, class, and age
-Correlation between fare amount and survival rate
-Influence of embarkation point and family size
-Comparison of Python vs SQL data transformations

🔍 Sample Insights
-📈 Gender: Female passengers had a survival rate over 70%, far higher than male passengers.
-🏷️ Class: First-class passengers were more than twice as likely to survive as third-class passengers.
-👶 Age: Younger passengers (especially under 10) had higher survival odds.
-💰 Fare: Passengers who paid higher fares generally had higher survival chances.
-🧭 Embarkation Port: Differences suggest socioeconomic disparities among passengers.

📘 Key Learning Outcomes
-Applying SQL for structured data extraction and aggregation
-Performing EDA in Python with pandas and seaborn
-Data storytelling: turning numeric results into historical insights
-Understanding feature relationships in real-world datasets
-Strengthening reproducibility through modular code and clear structure

🔮 Future Enhancements
-Build a predictive model (e.g., logistic regression or random forest) for survival prediction
-Create an interactive dashboard using Streamlit or Plotly Dash
-Integrate automated SQL-to-Python pipelines
