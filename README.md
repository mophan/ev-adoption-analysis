# Electric Vehicle (EV) Adoption Analysis 🚗⚡
This project explores **electric vehicle (EV) adoption patterns in Washington State** using Python. The analysis focuses on uncovering adoption patterns across **vehicle types, geography, manufacturers, pricing, performance, policy incentives (CAFV), and electric utilities.**

Completed as part of **ISE 201: Mathematical Foundations for Decision & Data Science** in the **MSAI program at San José State University.**

## Problem
How can policymakers and businesses understand EV adoption patterns
to improve infrastructure planning?

## Dataset
Washington State EV Registration Data (260K+ rows)

## Approach
This analysis follows a structured exploratory data analysis process:
1. **Understand the Problem & Data** — Defined research questions and assessed dataset scope and limitations.
2. **Import & Inspect Data** — Reviewed variable types, distributions, and overall data quality.
3. **Handle Missing Data** — Identified missing and zero values (e.g., electric range and base MSRP) and applied appropriate cleaning strategies.
4. **Explore Data Patterns** — Used descriptive statistics and grouped aggregations by geography, manufacturer, vehicle type, and model year.
5. **Transform Data** — Created derived variables and encoded categorical features to support analysis.
6. **Visualize Relationships & Correlations** — Examined key relationships using correlation analysis and visual exploration.
7. **Handle Outliers** — Detected and removed extreme values to avoid distortion in pricing and performance insights.

## Key Insights
1. What is the distribution of **Battery Electric Vehicles (BEVs)** vs. **Plug-in Hybrid Electric Vehicles (PHEVs)**?
- **BEVs dominate EV adoption (~80%)**, with consistent patterns across top counties and cities.
2. Which **counties and cities** have the highest concentration of EVs?
- **King County and Seattle lead EV adoption**, reflecting the influence of urban density and charging infrastructure.
3. Which **manufacturers and models** dominate the EV market?
- **Tesla dominates the EV market**, led by the Model Y and Model 3, and specializes almost entirely in BEVs.
4. How has EV adoption **evolved over time** by model year and vehicle type?
- EV adoption accelerated after **2017** and surged post-2020; recent dips likely reflect incomplete data.
5. How do **electric range and base MSRP** vary across manufacturers and models?
- Higher range often corresponds to higher MSRP, but **price is not driven by range alone**.
6. What is the relationship between **electric range and CAFV eligibility**?
- **Electric range strongly differentiates EV types** and is closely tied to CAFV eligibility.
7. Which **electric utilities** serve the largest EV populations?
- **Puget Sound Energy** serves the largest EV population, followed by City of Seattle and City of Tacoma utilities.

## Tech Stack
Python, Pandas, NumPy, Matplotlib, Seaborn

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

MSAI Student, San José State University

Background in Data Analytics, Marketing Analytics, and Applied AI
