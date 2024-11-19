# Atlanta Crime Analysis Power BI Project
![](https://github.com/Thomas-Nyanumba/Atlanta-PD-Power-BI-Group-Project/blob/main/Atlanta%20PD%20Background%20Image.png)

## Introduction
This project, developed as part of the **Analytics Extra Mentorship Program**, is a comprehensive analysis of crime trends in Atlanta from 2015 to 2020. It examines the impact of demographic factors, neighborhood population, and external influences like the COVID-19 lockdown on crime rates. The analysis was performed using Power BI and DAX to create interactive dashboards.

Our group, **AEM 9**, achieved a **Top 3 ranking out of 15 groups**, showcasing our expertise in data preparation, modeling, and visualization.

---

## Problem Statement
The Atlanta Police Department and city policymakers require detailed insights to:
1. Identify crime trends over time and forecast future occurrences.
2. Understand the influence of population density and demographic diversity on crime distribution.
3. Assess the impact of external events like COVID-19 lockdowns on crime rates.
4. Provide actionable intelligence to improve law enforcement and community safety.

---

## Skills and Concepts Applied
- **Power Query:** Cleaning and transformation of raw data.
- **Data Modeling:** Created a star schema for efficient querying and reporting.
- **DAX Calculations:** Developed advanced measures for trend analysis, ranking, and forecasting.
- **Interactive Visualizations:** Designed dashboards with drilldowns, slicers, and tooltips.
- **Time Series Analysis:** Forecasted crime trends using historical data.
- **Collaboration:** Worked as a team to deliver high-quality results within the two-week deadline.

---

## Data Overview
The analysis used data from multiple sources:
1. **Crime Table (Fact Table):**
   - Fields: Crime ID, Neighborhood, Occur Date, Crime Type, Race/Ethnicity, Population, and Location Details.
2. **Population Table (Dimension Table):**
   - Fields: Neighborhood, Total Population.
3. **Race and Ethnicity Table (Dimension Table):**
   - Fields: Race, Ethnicity, Population Count.
4. **Date Table (Dimension Table):**
   - Generated using DAX for time intelligence.

---

### **Data Model**
The project implemented a star schema with the following relationships:
- **Fact Table:** `Crime Table`
- **Dimension Tables:** `Population`, `Race and Ethnicity`, and `Date`
- **Relationships:** 
  - Many-to-One between `Crime Table` and `Population`.
  - Many-to-One between `Crime Table` and `Race and Ethnicity`.
  - Many-to-One between `Crime Table` and `Date`.

> **Data Model:** The data model image below
![Data Model](https://github.com/Thomas-Nyanumba/Atlanta-PD-Power-BI-Group-Project/blob/main/Atlanta%20PD%20Data%20Model%20Image.png)

---

## Dashboard Overview

### **1. Crime Trends**
   - Analyzed crime trends over five years and forecasted the next 18 months.
   - Visualized significant drops in crime during the COVID-19 lockdown and gradual recovery post-lockdown.
   
   ![](https://github.com/Thomas-Nyanumba/Atlanta-PD-Power-BI-Group-Project/blob/main/Crime%20Trend%20Image.png)

### **2. Crime by Type**
   - Provided a breakdown of crime occurrences by type, highlighting the largest increases (e.g., homicide and aggravated assault).

  ![](https://github.com/Thomas-Nyanumba/Atlanta-PD-Power-BI-Group-Project/blob/main/Crime%20By%20Type%20Image.png)
     
### **3. Neighborhood Crime Rankings**
   - Ranked neighborhoods by crime rates (crimes/population).
   - Identified Downtown and Midtown as high-crime areas, while others like Regency Trace reported zero crime rates.

  ![](https://github.com/Thomas-Nyanumba/Atlanta-PD-Power-BI-Group-Project/blob/main/Neighbourhood%20Crime%20Ranking%20Image.png)
     
### **4. Geographic Crime Distribution**
   - Displayed crime occurrences on an interactive map with drilldowns from neighborhoods to specific locations.

  ![](https://github.com/Thomas-Nyanumba/Atlanta-PD-Power-BI-Group-Project/blob/main/Geographic%20Crime%20Distribution%20Image.png)

### **5. Demographic Insights**
   - Explored crime rates across racial and ethnic groups, revealing disparities and highlighting areas for community-based intervention.
 
  ![](https://github.com/Thomas-Nyanumba/Atlanta-PD-Power-BI-Group-Project/blob/main/Demographic%20Insight%20Image.png)
     
### **6. Population Impact**
   - Analyzed the correlation between population size and crime rates, identifying zones where smaller populations experienced higher crime densities due to other factors.

  ![](https://github.com/Thomas-Nyanumba/Atlanta-PD-Power-BI-Group-Project/blob/main/Population%20Impact%20Image.png)

### **7. Lockdown Impact**
   - Evaluated crime rates during pre-lockdown, lockdown, and post-lockdown phases, illustrating significant reductions during restricted movement periods.

  ![](https://github.com/Thomas-Nyanumba/Atlanta-PD-Power-BI-Group-Project/blob/main/Lockdown%20Impact%20Image.png)

---

## Published on Power BI Fabric
This project was published on my **Power BI Fabric workspace**, allowing for streamlined development, testing, and production stages. The Fabric platform facilitated:
- **Development Stage:** Initial creation and refinement of the dashboards.
- **Testing Stage:** Collaborative testing to validate accuracy and usability.
- **Production Stage:** Final deployment and public sharing.

### Public Dashboard Access
The interactive dashboard is accessible via this [Power BI Fabric link](https://app.powerbi.com/view?r=eyJrIjoiMzBmNTZiNGEtNjU3NS00MzRjLTliNjYtMWYwNmZkZjRhMjYwIiwidCI6IjgwZTliY2Y3LTczYTYtNGI5OS1iZWFkLTA2MmNmZjE2MmY5NiJ9). Stakeholders can explore crime trends, rankings, and demographic insights in real time.

> **BI Fabric Deployment Pipeline:**
![](https://github.com/Thomas-Nyanumba/Atlanta-PD-Power-BI-Group-Project/blob/main/Atlanta%20PD%20BI%20Fabric%20Deployment%20Pipeline%20Image.png)

---

## Results and Insights
Key findings from the analysis include:
1. **Lockdown Impact:** Crime dropped drastically during COVID-19 lockdowns, showcasing the effect of restricted movement.
2. **High-Risk Areas:** Downtown and Midtown had the highest crime rates, warranting increased law enforcement focus.
3. **Demographic Disparities:** Certain racial and ethnic groups experienced disproportionate crime rates.
4. **Population Influence:** While crime generally increased with population size, some smaller zones exhibited higher crime densities due to other factors.

---

## Recommendations
1. **Targeted Resource Allocation:** Focus law enforcement resources on high-crime neighborhoods.
2. **Community Engagement Programs:** Collaborate with local leaders to address demographic-specific issues contributing to crime.
3. **Surveillance During Peak Crime Hours:** Increase patrols during late evening and night hours.
4. **Monitor Emerging Hotspots:** Continuously track crime trends in neighborhoods to preempt future spikes.

---

## Repository Contents
1. **Power BI File:** [Download the .pbix file](https://github.com/Thomas-Nyanumba/Atlanta-PD-Power-BI-Group-Project/blob/main/Atlanta%20PD%20BI%20Crime%20Analysis.pbix).
2. **Dataset:** [Download the crime dataset](https://github.com/Thomas-Nyanumba/Atlanta-PD-Power-BI-Group-Project/blob/main/Atlanta%20Crime%20Statistics%20Analysis%20with%20Power%20BI.pdf).
3. **Screenshots:** All visuals included in this report.
4. **Public Dashboard Link:** [Access the published dashboard here](https://app.powerbi.com/view?r=eyJrIjoiMzBmNTZiNGEtNjU3NS00MzRjLTliNjYtMWYwNmZkZjRhMjYwIiwidCI6IjgwZTliY2Y3LTczYTYtNGI5OS1iZWFkLTA2MmNmZjE2MmY5NiJ9).

---

## Contact
Feel free to connect with me for further inquiries:
- [LinkedIn Profile](https://www.linkedin.com/in/thomasnyanumba) or email thomas.nnyanumba@gmail.com
