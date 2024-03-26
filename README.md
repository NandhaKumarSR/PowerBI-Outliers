# Handling outliers in Data Visualization - Microsoft Power BI
## Overview
These Power BI reports demonstrates how to effectively manage outliers using the Interquartile Range (IQR) method. By implementing this technique, we ensure that our data visualizations remain accurate and insightful.

## Key Steps
1. **Data Preparation:**
   - The dataset used in this report contains sample data manually created for demonstration purposes
   - It is a star schema model.

2. **IQR Method Implementation:**
   - We calculated the first quartile (Q1) and third quartile (Q3) using DAX measures.
   - The IQR (Q3 - Q1) was computed to define the middle 50% of the data.
   - Outliers were identified based on the IQR range.

3. **Visualizations:**
   - Our visualizations filtered to exclude or include outlier data points based on the lower and upper limit.
   - We've highlighted outliers for further analysis.

## How to Use This Report
1. Open the "Outliers from Measures.pbix" or Outliers in data.pbix file in Power BI Desktop.
2. Explore the visualizations and interact with the data.
3. Pay attention to the outlier detection and handling.

## Additional Notes
- Customize the report as needed for your specific use case.
- Feel free to share your insights and findings with the team.

Happy analyzing! 🚀🔍
