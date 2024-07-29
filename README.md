# README

## Overview

This README provides an overview of the research and data analysis conducted to evaluate the effectiveness of the "Cool it! NYC" initiative in mitigating heat vulnerability across New York City. The study utilizes various data sources and analytical methods to assess the impact of public cooling infrastructure on community-level heat resilience.

## Data Sources

1. **Heat Vulnerability Index (HVI) Data**
   - 2018 HVI: Pre-implementation baseline.
   - 2023 HVI: Post-implementation assessment.
   - HVI Change: Differences in HVI values between 2018 and 2023.

2. **Cooling Facilities Locations**
   - Spray Showers
   - Drinking Fountains
   - Cooling Sites

3. **Demographic and Environmental Data**
   - Population data for 2022
   - Community Districts boundaries

## Analytical Methods

1. **Hotspot Analysis**
   - Tool: QGIS and the Getis-Ord Gi* statistic.
   - Purpose: Identify spatial clusters of cooling facilities and their concentration in high heat vulnerability areas.

2. **Regression Analysis**
   - Tool: R.
   - Purpose: Assess the impact of cooling facilities on the reduction of HVI in 2018 and 2023.
   - Variables: Log-transformed counts of spray showers, drinking fountains, and cooling sites.


## Findings

- **Heat Vulnerability Analysis**: Significant changes in HVI were observed in some neighborhoods, highlighting the impact of cooling interventions.
- **Effectiveness of Cooling Facilities**: Spray showers showed a significant positive relationship with the reduction in HVI, while drinking fountains and cooling sites did not show significant effects.

## Recommendations

1. **Expand Coverage**: Increase the number of spray showers in high HVI areas such as the South Bronx, Mott Haven, and Hunts Point.
2. **Optimize Facility Types**: Prioritize additional spray showers, and further investigate the optimization of drinking fountains and cooling sites.
3. **Long-term Monitoring**: Continuously assess and adjust cooling strategies to ensure continued effectiveness and responsiveness to community needs.

## Conclusion

The "Cool it! NYC" initiative has had a mixed impact on reducing heat vulnerability across New York City. While spray showers have proven effective, there is a need for continued efforts and optimization of other cooling facilities to enhance urban resilience to extreme heat.

## Notes

Since this CSV file was integrated locally, I imported it from my local machine. If you need to rerun this code, please first download the HVI_Change.csv file locally, then update the file path in the original code to reflect its saved location. I apologize for any inconvenience this may cause. I have saved all the useful layers in QGIS as individual GeoPackage files and uploaded them. However, I am concerned that there might be issues opening the documents. Therefore, I have taken screenshots of each page. If you encounter any difficulties opening my files, please feel free to contact me. Thank you!
