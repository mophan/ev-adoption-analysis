# Electric Vehicle (EV) Adoption Analysis 🚗⚡
Exploratory data analysis of electric vehicle (EV) adoption patterns in Washington State, using Python to uncover geographic, manufacturer, and performance trends that can inform infrastructure planning and policy decisions.

---

## 🎯 Project Objective
The goal of this project is to understand how electric vehicle adoption varies across regions, manufacturers, and vehicle characteristics in Washington State, and to translate data insights into actionable recommendations for stakeholders such as policymakers, utility providers, and businesses.

---

## 📂 Dataset
- **Source:** Washington State Department of Licensing (DOL) EV Registration Data  
- **Scope:** 260,000+ registered electric vehicles  
- **Key features:**  
  - Vehicle type (BEV vs. PHEV)  
  - Make & model  
  - Model year  
  - Electric range  
  - Base MSRP  
  - County & city  

Each row represents a unique registered electric vehicle.

---

## 🛠️ Tools & Skills
- **Python** (Pandas, NumPy)
- **Exploratory Data Analysis (EDA)**
- **Data cleaning & preprocessing**
- **Data visualization** (Matplotlib, Seaborn)
- **Google Colab & Jupyter Notebook**

---

## 🔍 Analysis Approach
This analysis follows a structured exploratory data analysis process:
1. **Understand the Problem & Data:** defined research questions and assessed dataset scope and limitations.
2. **Import & Inspect Data:** reviewed variable types, distributions, and overall data quality.
3. **Handle Missing Data:** identified missing and zero values (e.g., electric range and base MSRP) and applied appropriate cleaning strategies.
4. **Explore Data Patterns:** used descriptive statistics and grouped aggregations by geography, manufacturer, vehicle type, and model year.
5. **Transform Data:** created derived variables and encoded categorical features to support analysis.
6. **Visualize Relationships & Correlations:** examined key relationships using correlation analysis and visual exploration.
7. **Handle Outliers:** detected and removed extreme values to avoid distortion in pricing and performance insights.

---

## 📈 Key Insights
- **Battery Electric Vehicles (BEVs) dominate EV adoption**, accounting for the majority of registered electric vehicles.
- **King County and the Seattle area lead EV adoption**, reflecting the influence of higher population density and charging infrastructure availability.
- **Tesla Model Y and Model 3 are the most popular EV models**, indicating strong consumer preference for range and brand recognition.
- **Higher electric range generally corresponds to higher MSRP**, though price is influenced by multiple factors beyond range alone.
- **Utility providers such as Puget Sound Energy serve the largest share of EV owners**, highlighting opportunities for targeted infrastructure investment.


---

## 📊 Visual Highlights

---

## What I Learned from the EDA Process
- Visual inspection was essential for identifying data issues early, especially zero values representing missing data.
- Meaningful patterns only emerged after addressing missing values and outliers.
- Separating Tesla from non-Tesla vehicles revealed clearer market dynamics that were obscured in aggregate views.

## Limitations & Next Steps
### Limitations
- The analysis does not include demographic, socioeconomic, or political data, limiting causal interpretation.
- CAFV eligibility effects are examined descriptively and do not establish causation.
- Recent model years contain incomplete registration and range data.

### Next Steps
- Integrate demographic and housing data to better explain regional adoption differences.
- Incorporate charging infrastructure availability to assess its impact on city-level adoption.
- Extend analysis to legislative districts to explore links between clean-energy policies and EV adoption.

## Project Files
- [EV_Adoption_Washington_EDA.ipynb](EV_Adoption_Washington_EDA.ipynb) — Main exploratory data analysis notebook
- [EV_Adoption_Washington_EDA.pdf](EV_Adoption_Washington_EDA.pdf) — Project presentation / summary slides
- [README.md](README.md) — Project overview

## Author
**Annie Phan**
Data Analyst | MS AI @ San José State University

