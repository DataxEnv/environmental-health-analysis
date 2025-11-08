# Environmental Health Analysis: Correlation Between Air Pollution (PM2.5) and the prevalence of respiratory diseases in Major Nigerian cities (2018-2023)

## Abstract
Air pollution has become one of the most pressing public health challenged in Nigeria’s urban environments. Rapid urban growth, industrial emissions, and increased vehicular movement have led to higher concentrations of fine particulate matter (PM2.5), raising the risk of respiratory health issues among people living in urban areas (Okudo _et al_., 2022; Health Effects Institute, 2019).

This project explores the relationship between ambient PM2.5 levels and respiratory disease outcomes across major Nigerian cities, following the methodology described in Obani I. P. (2025)— *Air pollution and public health: Examining the correlation between PM2.5 levels and respiratory diseases in major cities in Nigeria.*

Using publicly available environmental air quality data and public health records (2018–2023), the analysis investigates how PM2.5 exposure correlates with the incidence of respiratory diseases such as asthma, chronic bronchitis, and chronic obstructive pulmonary disease (COPD). 

## Problem Statement & Objectives
There is still a dearth of data-driven research in Nigeria, despite the fact that studies conducted worldwide have shown a clear correlation between PM2.5 exposure and more hospital visits or respiratory-related mortality. Simultaneously, many urban hospitals  report a consistent increase in respiratory cases, yet there is little empirical evidence connecting these trends to air quality. Therefore, this study aims to respond to:
**How does air pollution (PM2.5) correlate with the prevalence of respiratory diseases in Nigeria’s major urban cities over a five-year period (2018 and 2023)?**

It also examines which cities have the highest pollution–health burden


### Research Objectives
1. To analyze the distribution and yearly trend of PM2.5 concentrations in Lagos, Abuja, Port Harcourt, and Kano between 2018 and 2023.
2. To identify the cities with the highest PM2.5 exposure.
3. To examine the relationship between PM2.5 levels and respiratory disease rates, using correlation and visual analysis.


## Methodology
### Data Sources
The data were manually extracted and compiled from the **WHO Ambient Air Quality Database (2023)**,** OpenAQ**, and **National public health records**.

### Tools & Libraries
All analysis was carried out using `Python` within a `Jupyter Notebook` environment.
- **Core Libraries**: Pandas, Matplotlib, Seaborn, and scipy.
- **Workflow**: Data Cleaning → Exploratory Data Analysis (EDA) → Correlation Analysis  → Results
  
### Analysis Methods
- **Data Cleaning & Preprocessing**: Handling missing values, correcting inconsistencies, and standardizing units across datasets.
- **Exploratory Data Analysis (EDA):** Visualizing PM2.5 trends across cities and years to detect temporal or regional patterns.
- **Statistical Analysis:** using **Pearson correlation**  to assess the relationship between PM2.5 levels and respiratory disease rates.
- **Visualization:** **scatter plots** and **distribution charts** to illustrate city-level differences, detect outliers, and reveal the patterns between pollution intensity and respiratory health outcomes.

### Skills & Techniques
1.	**Python for Data Analysis**
    - Data wrangling and cleaning with **Pandas**
    - correlation analysis with **SciPy.stats**
    - Data visualization with **Matplotlib** and **Seaborn**

2.	**Environmental Research**
    - Identifying and linking environmental and health indicators
    - Statistical interpretation for scientific reporting
    - Research storytelling and result translation for policy and  public health relevance


## Results & Recommendations
The analysis showed a **strong positive correlation (r = 0.92)** between annual PM2.5 concentration and respiratory disease rates across the major Nigerian cities (2018–2023). In simple terms, cities with higher air pollution levels also recorded higher rates of respiratory illnesses.

**Port Harcourt** and **Lagos** showed the highest pollution and respiratory case rates. Port Harcourt’s extreme pollution is likely due to its *industrial and oil-related activities*, reflecting the city’s well-known soot pollution problem. For Lagos, *traffic congestion* and *population density* remain major contributors. In contrast, **Kano** consistently had the lowest PM2.5 levels.

It’s worth noting that all cities still exceed the **WHO air quality guideline (5 µg/m³)**, showing how widespread the urban air quality challenge is. 

These findings aligns with global public health evidence: as PM2.5 levels increase, so do respiratory health problems like asthma, bronchitis, and COPD.

In conclusion, **higher pollution means higher health risks**. There’s a clear need for stronger air quality control policies, improved public health monitoring, and more awareness about the health impacts of urban air pollution in Nigeria.

<p align="center">
  <img width="500" alt="PM2.5 by city" src="https://github.com/user-attachments/assets/aee4605c-cc14-4892-af85-49dc14e4f33f" />
</p>

<p align="center">
  <img width="500" alt="PM2.5 vs Respiratory rate" src="https://github.com/user-attachments/assets/1d79e5d5-2744-480f-8267-36e7ce832a2e" />
</p>


## Next Steps
- Expand the dataset to more cities and years
- Explore additional pollutants (like NO₂ and SO₂)
- Add Geospatial or temporal modelling.
- Include population density data for deeper environmental health insights.


## References
Health Effects Institute. (2019). *Nigeria: State of Global Air 2019 Country Factsheet.* Health Effects Institute. Retrieved from [https://www.stateofglobalair.org/sites/default/files/soga_2019_nigeria.pdf](https://www.stateofglobalair.org/sites/default/files/soga_2019_nigeria.pdf)

Obani, I. P. (2025). *Air pollution and public health: Examining the correlation between PM2.5 levels and respiratory diseases in major cities in Nigeria.* *Journal of Healthcare and Life-Science Research, 4*(4). University of Derby.

Okudo, C. C., Ekere, N. R., & Okoye, C. O. B. (2022). Evaluation of particulate matter (PM2.5 and PM10) concentrations in the dry and wet seasons as indices of air quality in Enugu Urban, Enugu State, Nigeria. *Journal of the Chemical Society of Nigeria, 47*(5).

WHO. WHO Ambient Air Quality Database (update 2024). Version 6.1. Geneva, World Health Organization, 2024.
