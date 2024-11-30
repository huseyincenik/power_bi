# Workout Wednesday 2021 Week 10 | Power BI: Violin Plot Custom Visual

![image](https://github.com/user-attachments/assets/4683c644-ccae-4c90-b21d-15f770b80e95)

Welcome to my solution for the **Workout Wednesday 2021 Week 10 challenge**! This repository highlights my approach to visualizing average temperature data using the **Violin Plot custom visual** in Power BI.

## Challenge Overview
This week's challenge involves creating a violin plot to show the distribution and density of daily average temperatures in Denver, Colorado, during 2020. The visualization combines individual data points and statistical measures to provide meaningful insights.

### Requirements
#### Data Visualization:
- **Chart Type:** Violin Plot (Barcode/Strip plot).
- **Data Grouping:** Display average temperatures grouped by month names.
- **Kernel Density:** Use the Epanechnikov kernel with high sampling resolution.
- **Statistical Lines:** Include lines for the first and third quartiles and the median.
- **Tooltip Formatting:** Ensure all measures display as integers (zero decimal places).
- **Text Styling:** Use a text size of at least 12 points for axis labels.
- **Color Contrast:** Ensure a contrast ratio of at least 3:1 for all chart elements.

#### Additional Analysis:
- Identify months with the highest and lowest standard deviation of temperatures.

#### Dataset:
The dataset contains 2020 daily average temperature data (in Fahrenheit and Celsius) for [Denver, Colorado, sourced from NOAA’s Denver/Boulder Weather Forecast Office](https://onedrive.live.com/?authkey=%21AF7wsa%2DjlBnFetI&cid=D11AFF22A72ECFD0&id=D11AFF22A72ECFD0%21128274&parId=D11AFF22A72ECFD0%21128273&o=OneUp).

## Solution
The solution includes:
1. **Violin Plot Creation:**
   - Grouped by month name with average temperature values.
   - Barcode plot to display individual data points.
   - Kernel density shaped using the Epanechnikov function.

2. **Statistical Insights:**
   - Highlighted quartiles and median lines for deeper analysis.
   - Identified months with maximum and minimum standard deviations in temperature values.

3. **Formatting & Accessibility:**
   - Tooltips formatted to display integers.
   - Colors selected to meet WCAG accessibility standards for contrast.

4. **Title:** The chart is titled “2020 Daily Average Temperatures in Denver, Colorado” for clarity and context.

## Key Visuals
- **Violin Plot:** Shows temperature distribution and density by month.
- **Supporting Analysis:** Insights into monthly standard deviations for variability assessment.

## Conclusion
This challenge showcases the power of custom visuals in Power BI to deliver comprehensive and accessible insights. The violin plot effectively visualizes both data distribution and density, offering a clear understanding of temperature patterns in Denver throughout 2020.

Thank you for exploring my solution! I hope it inspires your Power BI projects.
