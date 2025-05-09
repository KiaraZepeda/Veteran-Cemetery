# Veteran Cemetery EDA and Non-Parametric Statistics

## Overview
This project performs exploratory data analysis (EDA) and applies non-parametric statistical methods to investigate patterns from National Cemetery data. The goal is to uncover meaningful insights about burial trends, demographics, and potential associations between variables.

## Dataset
The dataset contains burial and veteran-related data collected from U.S. National Cemeteries. Key variables include service branch, gender, era of service, and burial locations. The dataset is from [Kaggle](https://www.kaggle.com/datasets/kiarazepeda/national-cemetery-data), (totaling over 2 GB).

## Objectives
- Explore and visualize patterns in veteran cemetery data.
- Identify trends in burial counts by year, era, and service branch.
- Apply non-parametric statistical tests to determine the significance of observed differences.

## Methods Used

### Exploratory Data Analysis (EDA)
- Time-based trend analysis.

![Age Distribution](AgeDistribution.jpg)

![Birth and Death](BirthandDeath.jpg)
  
- Group comparisons using categorical variables.

![Cemeteries](Cemetery.jpg)
  
- Naming trends.

![Top 10 Last Names](LastNames.jpg)

![Top 10 First Names](FirstNames.jpg)


### Statistical Analysis
- Kaplan-Meier Curves for non-parametric group comparisons.
- Visual tools such as bar charts and boxplots for communicating results.

## Key Insights
- Certain service eras and branches show disproportionate burial counts.
- Temporal trends reflect historical events and veteran population shifts.

  ![Kaplan-Meier](Kaplan.jpg)

## Future Work
- Incorporate geospatial mapping for burial site locations.

![Scatter Plot](CemeteryLocation.jpg)
  
- Expand dataset to include additional years or regional breakdowns.
- Further cleansing of incorrectly inputed data. 
- Automate statistical reporting for faster insight generation.

## Acknowledgements
Special thanks to the U.S. Department of Vetern Affairs and documentation providers.
