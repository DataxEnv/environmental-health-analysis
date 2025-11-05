# Environmental Health Analysis: Exploring the Relationship Between Air Pollution (PM2.5) and Respiratory Health outcomes in Nigeria (2018-2023)
## Abstract
Air pollution has become one of the most pressing public health challenged in Nigeria’s urban environments. Rapid urban growth, industrial emissions, and increased vehicular movement have led to higher concentrations of fine particulate matter (PM2.5), raising the risk of respiratory health issues among people living in urban areas (Okudo _et al_., 2022; Health Effects Institute, 2019).

This project explores the relationship between ambient PM2.5 levels and respiratory disease outcomes across major Nigerian cities, following the methodology described in Obani I. P. (2025)— *Air pollution and public health: Examining the correlation between PM2.5 levels and respiratory diseases in major cities in Nigeria.*

Using publicly available environmental air quality data and public health records (2018–2023), the analysis investigates how PM2.5 exposure correlates with the incidence of respiratory diseases such as asthma, chronic bronchitis, and chronic obstructive pulmonary disease (COPD). Statistical and visualization methods are used to identify links between pollution and health, highlight high-risk regions, and draw attention to vulnerable populations.



## Problem Statement & Objectives
Although global studies have established strong links between PM2.5 exposure and increased hospital visits or respiratory-related mortality, data-driven research in Nigeria is still quite limited. Simultaneously, many urban hospitals report a steady rise in respiratory cases, yet there is limited empirical evidence connecting these trends to air quality. Hence, this research seeks to answer:
**How does air pollution (PM2.5) correlate with respiratory disease prevalence in Nigeria’s major urban cities over a five-year period (2018 and 2023)?**

It also examines which cities face the highest pollution–health burden, and whether factors like population size or seasonal variations (wet and dry seasons) influence the severity of these health outcomes.

### Research Questions
1. What are the average PM2.5 levels in Lagos, Abuja, Port Harcourt, and Kano between 2018 and 2023?
2. Is there a statistically significant relationship between PM2.5 concentrations and the prevalence of respiratory diseases such as asthma, bronchitis, and COPD?
3. How do PM2.5 levels and health outcomes vary across different seasons and urban zones?
4. Which population groups appear most vulnerable to air pollution–related respiratory risks?



## Methodology
### Data Sources
The data were manually extracted and compiled from the **WHO Ambient Air Quality Database (2023)**,** OpenAQ**, and **National public health records**.

### Tools & Libraries
All analysis was carried out using `Python` within a `Jupyter Notebook` environment.
- **Core Libraries**: Pandas, NumPy, Matplotlib, Seaborn, SciPy
- **Workflow**: Data Cleaning → Exploratory Data Analysis (EDA) → Correlation Analysis → Visualization → Insight Generation

### Analysis Methods
- **Data Cleaning & Preprocessing**: Handling missing values, correcting inconsistencies, and standardizing units across datasets.
- **Exploratory Data Analysis (EDA):** Visualizing PM2.5 trends across cities and years to detect temporal or regional patterns.
- **Statistical Analysis:** using **Pearson correlation** and **simple linear regression** to assess the relationship between PM2.5 levels and respiratory disease rates.
- **Visualization:** **scatter plots** and **box plots** to compare seasonal and city-level differences.

### Skills & Techniques
1.	**Python for Data Analysis**
    - Data wrangling and cleaning with **Pandas**
    - Descriptive statistics and correlation analysis with **NumPy** and **SciPy**
    - Data visualization with **Matplotlib** and **Seaborn**

2.	**Environmental Research**
    - Identifying and linking environmental and health indicators
    - Statistical interpretation for scientific reporting
    - Research storytelling and result translation for policy and  public health relevance


## Results & Insights

## Recommendations

## Next Steps

--- 
## References
Health Effects Institute. (2019). *Nigeria: State of Global Air 2019 Country Factsheet.* Health Effects Institute. Retrieved from [https://www.stateofglobalair.org/sites/default/files/soga_2019_nigeria.pdf](https://www.stateofglobalair.org/sites/default/files/soga_2019_nigeria.pdf)

Obani, I. P. (2025). *Air pollution and public health: Examining the correlation between PM2.5 levels and respiratory diseases in major cities in Nigeria.* *Journal of Healthcare and Life-Science Research, 4*(4). University of Derby.

Okudo, C. C., Ekere, N. R., & Okoye, C. O. B. (2022). Evaluation of particulate matter (PM2.5 and PM10) concentrations in the dry and wet seasons as indices of air quality in Enugu Urban, Enugu State, Nigeria. *Journal of the Chemical Society of Nigeria, 47*(5).

WHO. WHO Ambient Air Quality Database (update 2024). Version 6.1. Geneva, World Health Organization, 2024.
