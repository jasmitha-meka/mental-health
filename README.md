# Global Patterns in Mental Health

Author: Jasmitha Meka

### Executive summary
This project analyzes global mental-health disorder trends and investigates how socioeconomic factors relate to variations across countries and over time. Using exploratory data analysis, clustering, and dimensionality reduction techniques, the study identifies distinct country groups with similar mental-health profiles and highlights which disorders contribute most to global variation.

### Rationale
Mental health affects education, productivity, and quality of life, yet many countries lack a clear understanding of evolving mental-health burdens. By examining global patterns and associated socioeconomic drivers, this project provides insights that can support public-health planning, resource allocation, and early-intervention strategies.

### Research Question
How does the prevalence of mental-health disorders vary across countries and over time, and which socioeconomic factors are most strongly associated with these differences?

### Data Sources
* [Kaggle: Mental Health Dataset](https://www.kaggle.com/datasets/imtkaggleteam/mental-health/data?select=1-+mental-illnesses-prevalence.csv
)
* World Bank datasets for socioeconomic indicators such as GDP, population, and life expectancy

### Methodology
- **Data Preparation & Feature Engineering:** Merged datasets, handled missing values, standardized formats, and derived country-level and year-level aggregates.  
- **Exploratory Data Analysis (EDA):** Trend analysis, correlation analysis, time-series insights, and demographic comparisons.  
- **Clustering (K-Means):** Grouped countries based on mental-health disorder prevalence.  
- **Principal Component Analysis (PCA):** Reduced dimensionality and identified the most influential disorder patterns.

### Results
- Global averages for schizophrenia, bipolar disorder, and eating disorders remain largely stable from 1990–2019, with anxiety consistently the most prevalent and depressive disorders following closely.  
- Relative trends reveal meaningful differences: eating disorders rise by ~17%, anxiety increases by ~2%, depressive disorders decline by ~2.5%, and schizophrenia and bipolar disorder remain nearly unchanged.  
- Country-level patterns show clear variation: the U.S. leads in schizophrenia; African nations dominate the highest depressive-disorder rankings; Portugal, Brazil, and New Zealand show the highest anxiety levels; New Zealand records the highest bipolar prevalence; and Australia shows the fastest rise in eating disorders.  
- Low-GDP and low–life-expectancy countries consistently report higher depressive disorders, while high-GDP regions show slightly higher anxiety, bipolar, and eating-disorder levels—likely due to better detection and reporting.  
- High–life-expectancy countries show declining trends in anxiety, bipolar, and eating disorders, whereas schizophrenia remains stable across all demographic groups.  
- Smaller-population countries exhibit stronger upward trends in anxiety, bipolar, and eating disorders, while larger-population countries remain comparatively stable.  
- PCA shows that PC1 captures internalizing-disorder severity (anxiety, bipolar, eating disorders), while PC2 contrasts depressive disorders with schizophrenia, explaining the main axes of variation.  
- PCA visualization reveals clear separation between country groups, confirming meaningful structural differences in mental-health profiles.  
- K-Means identifies five clusters: a low-burden group, a moderate-burden group, an internalizing-heavy European cluster (19 of 30 countries), a high-burden outlier cluster (US, Australia, New Zealand), and a depression-dominant African cluster (39 of 68 countries).  
- Overall, global mental-health patterns reflect strong relationships with socioeconomic conditions, demographic structure, and region-specific disorder trends.

### Next steps

* Expand the analysis by incorporating additional socioeconomic indicators such as education index, unemployment rate, and healthcare spending to strengthen the relationship modeling.
* Evaluate the optimal number of clusters using the Elbow Method to validate the current K-Means grouping.
* Compare K-Means with an alternative clustering method such as DBSCAN to assess robustness

### Outline of project
- [mental-health](https://github.com/jasmitha-meka/mental-health/blob/main/mental-health.ipynb)


#### Contact and Further Information
For questions or collaboration, please contact m.jasmitha@gmail.com.
