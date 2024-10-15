# Workout Wednesday 2021 Week 7 | Power BI: Ice Coverage by Lake

![image](https://github.com/user-attachments/assets/76355eea-b1c2-45e0-8880-59d9b0d3c915)


Welcome to my solution for the **Workout Wednesday 2021 Week 7** challenge! This repository showcases my approach to the fourth Power BI challenge of the year, which focuses on transforming and visualizing ice coverage data for the Great Lakes.

## Challenge Overview

This week's challenge involves transforming data on maximum ice coverage across the Great Lakes and creating a matrix visual in Power BI. The matrix will show ice coverage for each lake by year, with additional conditional formatting and supporting visuals to enhance the report.

### Requirements:

1. **Data Transformation:**
   - Convert individual lake columns into rows (pivot) so that only three columns remain in the data model: `Lake`, `Year`, and `Ice Coverage`.

2. **Matrix Visual:**
   - Create a matrix visual displaying ice coverage by lake (columns) and year (rows).
   - Apply major formatting, such as removing row and column totals.
   - Filter out a specific lake using a page-level or report-level filter.

3. **Matrix Conditional Formatting:**
   - **Background Color:** Build custom rules for background color based on ice coverage percentages (five ranges: 0-24.99, 25-49.99, 50-74.99, 75-99.99, 100).
   - **Font Color:** Apply font color (black or white) to ensure contrast with background colors meets WCAG AA accessibility standards.
   - **Icons:** Add a star next to any value where the ice coverage reaches 100%.

4. **Supporting Visuals:**
   - Add at least two supporting visuals to complement the matrix, using the three fields in creative ways.

5. **Analysis Questions:**
   - Identify which lake has frozen completely over most often.
   - Analyze if ice coverage is trending *upward* for any lake over time.

### Dataset:
- The dataset contains maximum ice coverage data from NOAA’s Great Lakes Environmental Research Laboratory. Ice coverage for each lake ranges from 0 (no ice) to 100 (completely frozen).
- You can get the raw data from [Data.World](https://data.world/dataveld/wow2021week07) or download the Excel version from [GitHub](https://github.com/dataveld/WorkoutWednesday/blob/main/Great%20Lakes%20Historical%20Ice%20Coverage%201973%20to%202020.xlsx).

## Solution

The solution includes:
- A **data transformation** step using Power Query to pivot lake columns into rows.
- A **matrix visual** that dynamically displays ice coverage data by year and lake.
- **Conditional formatting** with customized background colors based on coverage ranges, accessible font colors, and star icons for 100% coverage values.
- **Supporting visuals** that provide additional insights, such as trends over time and total frozen days by lake.
- **Analysis** identifying which lake has frozen over the most and whether any lake shows an upward trend in ice coverage.

### Key Visuals:
- Matrix with year-by-lake ice coverage data.
- Visuals showing ice coverage trends and the lake with the most frequent complete freezes.

Thank you for checking out my solution. I hope this helps you with your Power BI projects!


