# Mexico Restaurant Rating Analysis

## Project Overview
This capstone project analyzes restaurant ratings in Mexico using a 
customer survey dataset collected in 2012. As a contracted Data Analyst, 
the goal was to extract meaningful insights to help business entrepreneurs 
and investors make informed decisions about the restaurant industry.

---

## Dataset Description
The dataset contains 5 tables:
- **Ratings** — Overall, food and service ratings (scale 0–2)
- **Restaurants** — Location, price, alcohol service, parking info
- **Consumers** — Age, occupation, budget, marital status
- **Consumer Preferences** — Preferred cuisines per consumer
- **Restaurant Cuisines** — Cuisines served per restaurant

---

## Tools Used
- **Power BI Desktop** — Data transformation, modeling & dashboard
- **Power Query** — Data cleaning & transformation
- **DAX** — Calculated measures and columns

---

## Data Cleaning Process
- Removed trailing spaces using Trim
- Fixed restaurant name spellings and accents
- Replaced "Fine_Dining" with "Fine Dining"
- Merged all 5 tables into a unified ratings table
- Created Age Group DAX column for demographic analysis

---

## Key Insights & Findings

### Question 1 — Highest Rated Restaurants & Consumer Preferences
- **Emilianos, Michiko Restaurant Japones and Restaurant Las Mañanitas** 
achieved a perfect rating of **2.00**
- When cuisine **matches** consumer preference, average rating = **1.09**
- When cuisine **doesn't match**, average rating drops to **0.73** 
— a **33% difference**
- **Japanese cuisine** drives the highest consumer satisfaction
- **High-priced restaurants (0.85)** outperform medium-priced ones (0.69), 
suggesting quality perception matters to consumers

### Question 2 — Consumer Demographics & Data Bias
- **81.88% of consumers are students** — revealing heavy demographic bias
- The **18-25 age group** dominates overwhelmingly
- **65.94% operate on a medium budget**
- Employed consumers rate restaurants significantly higher **(1.58)** 
vs students **(0.70)** — confirming the student-heavy sample pulls 
overall ratings downward

### Question 3 — Demand & Supply Gap Analysis
- **Mexican cuisine** is both highest in demand (949) and supply — 
saturated market, high competition
- Major gaps identified in:
  - **Coffee Shop** — 94 consumer demand, very low supply 
  - **Family** — 95 demand, very low supply 
  - **Japanese** — 85 demand, low supply 
  - **Italian** — 83 demand, low supply 
- These represent strong **market entry opportunities**

### Question 4 — Investment Recommendation
Based on the analysis, the ideal restaurant investment profile is:

> *Invest in a High-End Japanese, Italian or Coffee Shop restaurant 
> in San Luis Potosi or Ciudad Victoria, WITHOUT necessarily serving 
> alcohol, with parking facilities, targeting employed consumers aged 26-45.*

**Key characteristics:**
- **Price:** High (avg rating 0.85 — highest performer)
- **Cuisine:** Japanese, Italian or Coffee Shop (high demand, low supply)
- **Location:** San Luis Potosi or Ciudad Victoria
- **Parking:** Essential facility
- **Alcohol:** Not necessary (no alcohol scores 0.81 vs alcohol 0.69)
- **Target:** Employed consumers aged 26-45

---

## Dashboard Preview

### Page 1 — Highest Rated Restaurants & Consumer Preference Analysis
![Page 1](Page1_Highest_Rated_Restaurants.png)

### Page 2 — Consumer Demographics & Data Bias Analysis
![Page 2](Page2_Consumer_Demographics.png)

### Page 3 — Demand & Supply Gap Analysis
![Page 3](Page3_Demand_Supply_Gap.png)

### Page 4 — Investment Recommendation
![Page 4](Page4_Investment_Recommendation.png)

---

## Conclusions
This analysis reveals that success in the Mexican restaurant market 
depends heavily on matching consumer cuisine preferences, targeting 
the right demographic, and identifying underserved cuisine categories. 
The data strongly suggests that high-end Japanese, Italian or Coffee 
Shop restaurants in key cities represent the most promising investment 
opportunities.

---

*Capstone Project — DigitaleyDive Data Analytics Bootcamp 2026*
