
# Aircraft Safety Analysis for Business Decisions

## Overview
This project analyzes historical aviation accident data to determine which aircraft models are the safest for purchase by a company expanding into the aviation industry. The findings provide data-driven insights that help the head of the aviation division make informed decisions on aircraft acquisitions, with a focus on improving operational safety and managing risks.

## Business Understanding
As the company plans to enter the aviation market, understanding the risks associated with aircraft models is crucial for making safe and cost-effective acquisitions. Executives and safety officers are particularly interested in identifying the aircraft models with the best safety records and understanding the factors that influence aviation accidents.

### Key Business Questions:
- **Which aircraft models have the best safety records?**
- **What factors contribute most to aviation accidents, and how do they differ across aircraft types?**
- **How can the company reduce risks when operating specific aircraft models?**

## Data Understanding and Analysis

### Data Source
The data comes from the National Transportation Safety Board (NTSB) and spans from 1962 to 2023. It includes detailed records of civil aviation accidents and select incidents.

### Key Data Fields:
- **Event.Id**: Unique accident identifier.
- **Investigation.Type**: Type of investigation (e.g., accident, incident).
- **Event.Date**: Date of the accident.
- **Location and Country**: Geographical information about where the accident occurred.
- **Injury.Severity**: The severity of injuries resulting from the accident.
- **Aircraft.damage**: The extent of damage to the aircraft.
- **Make / Model**: Aircraft manufacturer and model involved in the accident.
- **Weather.Condition**: Conditions during the time of the accident.

### Analysis Process:
1. **Data Cleaning**: Removed missing or inconsistent data points.
2. **Exploratory Data Analysis (EDA)**: Investigated key patterns and relationships within the dataset.
3. **Visualization**: Developed charts to visualize the findings.

## Summary of Findings and Visualizations

- **Analyzed Accident Severity and Uninjured Passengers by Aircraft Make**:
    - Examined the severity of accidents and the number of uninjured passengers across different aircraft makes to identify safety trends.
  
- **Calculated the Ratio of Fatalities to Aircraft Make**:
    - Determined the ratio of fatalities for each aircraft make to understand which aircraft have higher or lower risks.
  
- **Identified Top 10 Aircraft Makes by Frequency**:
    - Ranked the top 10 aircraft makes based on the frequency of accidents, providing insight into which models are most commonly involved.
  
- **Applied Normalization Techniques to Assess Distribution Errors**:
    - Used normalization techniques to evaluate how accident causes and severity are distributed across different aircraft makes, ensuring that the analysis accounts for variations in usage and other factors.

### Visualizations:
1. **Accident Frequency by Aircraft Model**:
   - This graph shows the number of accidents by model, helping identify which aircraft models are more prone to incidents.

2. **Severity of Injuries Across Aircraft Models**:
   - A visual comparison of injury severity for different aircraft models, highlighting those with fewer fatal or serious injuries.

3. **Weather Condition Impact on Accident Rates**:
   - This visualization shows how different weather conditions affect accident rates, revealing patterns that may influence safety decisions.

## Conclusion

### Summary of Findings:
1. **Accident Severity**: Certain aircraft makes tend to have more severe accidents, while others have fewer fatalities and injuries.
2. **Top 10 Aircraft Makes by Frequency**: The most frequently involved aircraft models have been identified, allowing for targeted safety assessments.
3. **Normalized Distribution of Errors**: By normalizing the data, the analysis accounts for varying factors like flight hours or aircraft usage, providing a fair comparison of accident rates across models.

For further discussions or clarifications, please feel free to reach out!
