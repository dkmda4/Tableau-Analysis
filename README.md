# 🌍 Global Population, Environmental Stress, and Resource Risk  
**Tableau Data Visualisation Project**


## 📌 Project Overview
This project explores global patterns in population pressure, environmental stress, energy demand, and resource consumption using country-level data sourced from Kaggle. The analysis was built in Tableau to identify regions and countries facing compounded environmental and demographic risk.

The focus is on how population dynamics interact with environmental and resource-related pressures, rather than treating these factors in isolation.



## 📂 Data Sources
The analysis uses multiple CSV files sourced from Kaggle, each covering a different dimension of population and environmental risk:


- **global_population_risk.csv** – Population pressure, environmental stress, climate vulnerability, economic resilience  
- **population_growth.csv** – Population growth rates and population density  
- **population_goods_resources.csv** – Energy demand, CO₂ emissions, water consumption, resource dependency  
- **population_ozone_environment.csv** – Ozone risk indicators and atmospheric environmental metrics

All datasets are structured at country level and were connected in Tableau using logical relationships.



## 🧩 Data Modelling Approach
The datasets were connected in Tableau using **relationships** based on the `country` field rather than physical joins.

This approach was chosen to:
- Preserve the original structure of each dataset  
- Avoid duplication or inflation of country-level metrics  
- Allow Tableau to dynamically resolve aggregations across multiple domains  

This modelling strategy supports cross-country and regional comparison, which is the core focus of the analysis.



## 🛠 Tools Used
- **Tableau** – data modelling, analysis, and interactive dashboards  
- **GitHub** – version control and project documentation  



## 🔍 Key Analytical Questions
This project explores the following questions:

- Which countries face both high population pressure and high environmental stress?
- How are energy demand and CO₂ emissions distributed across continents?
- Do high energy demand countries also exhibit greater resource dependency?
- How does per-capita water consumption vary with population density?
- Are the most environmentally stressed countries also less economically resilient?



## 📊 Visualisations and Key Insights

### 1️⃣ Top 10 Countries by Population Pressure and Environmental Stress

<img width="1323" height="777" alt="Screenshot 2026-01-25 at 18 14 51" src="https://github.com/user-attachments/assets/7d2497a2-28f9-45d9-be6b-b39a03e54dc4" />

This scatter plot compares average population pressure with average environmental stress for the ten highest-pressure countries. A trend line is included to show the overall direction of the relationship.

**Key insight:**  
Countries with the highest population pressure tend to also show elevated environmental stress, indicating that demographic strain and environmental vulnerability often appear together.


### 2️⃣ Energy Demand and CO₂ Emissions by Continent

<img width="1233" height="781" alt="Screenshot 2026-01-25 at 23 00 17" src="https://github.com/user-attachments/assets/3f1c1db8-25f7-49cc-a0b3-48930e19be35" />

This visual compares total energy demand and total CO₂ emissions across continents to show where environmental impact is most concentrated.

**Key insight:**  
Energy demand and emissions are unevenly distributed globally, with Asia showing a noticeably larger share compared with other regions.


### 3️⃣ Energy Demand vs Resource Dependency (Top 20 Countries)

<img width="1234" height="774" alt="Screenshot 2026-01-25 at 22 55 25" src="https://github.com/user-attachments/assets/10011a48-70b6-4d92-aa22-3a994f59d0dc" />

This scatter plot explores whether countries with the highest energy demand also show greater reliance on external resources.

**Key insight:**  
High energy demand does not consistently align with lower dependency. Some high-demand countries remain highly resource-dependent, while others diverge from this pattern.


### 4️⃣ Water Consumption vs Population Density

<img width="1234" height="777" alt="Screenshot 2026-01-25 at 22 56 42" src="https://github.com/user-attachments/assets/c3b3eee6-c51c-4815-a0ef-de7bbcc24b20" />

This chart compares per-capita water consumption with population density to highlight different pathways to water stress.

**Key insight:**  
Population density does not automatically translate into higher per-capita water use. Water pressure can arise either from dense populations or from high individual consumption.


### 5️⃣ Top Countries by Environmental Stress (with Economic Resilience Overlay)

<img width="1237" height="779" alt="Screenshot 2026-01-25 at 22 59 15" src="https://github.com/user-attachments/assets/e098a113-0318-4f66-8372-be5cbc0c37ef" />

This ranked bar chart shows countries with the highest average environmental stress, with colour representing economic resilience. This makes it easier to distinguish high-stress countries with stronger coping capacity from those likely to be more vulnerable.

**Key insight:**  
Several highly stressed countries also show comparatively lower economic resilience, suggesting that environmental exposure can be compounded by reduced capacity to respond effectively.


## 🧠 Key Takeaways
- Environmental and demographic risks often co-occur, creating compounded vulnerability  
- Environmental pressure is unevenly distributed across regions and countries  
- Resource demand and population density represent different risk pathways  
- Economic resilience helps differentiate high-stress countries with stronger coping capacity from those more exposed  



## ⚠️ Limitations
- This analysis is descriptive rather than causal  
- Composite indices simplify complex real-world dynamics  
- Results depend on reporting consistency and data quality across countries

## 🧾 Conclusion

This analysis reveals that environmental and demographic pressures rarely occur in isolation. Population pressure and environmental stress often align in the same countries, and regions with high energy demand tend to show elevated emissions. Water consumption patterns vary by density, and countries with both high stress and lower resilience may be particularly vulnerable. These insights highlight the value of considering multiple risk indicators together rather than individually.

Future work could expand into temporal trend analysis or incorporate economic and policy variables to better understand drivers behind these patterns.


## 📬 Contact
If you’d like to discuss this project or provide feedback, feel free to connect via GitHub or LinkedIn.
