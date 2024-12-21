# Power BI: Can You Turn a Ribbon Chart into a Bump Chart?
![image](https://github.com/user-attachments/assets/48a648fc-80e3-4f45-8bcb-3a4308fac68d)

## Introduction

This repository contains a solution for the **[Workout Wednesday 2021 Week 11](https://workout-wednesday.com/2021-week-11-power-bi-can-you-turn-a-ribbon-chart-into-a-bump-chart/#comment-23186)** challenge: turning a Ribbon Chart into a Bump Chart in Power BI. 

### Ribbon Chart

The Ribbon Chart is a built-in Power BI chart used to display rank changes with minimal setup. It:
- Displays rank as a stacked column chart.
- Shows measures as bar lengths with ribbons between bars indicating differences.
- Provides tooltips with additional data points.

### Bump Chart

The Bump Chart serves a similar purpose but is more challenging to create in Power BI. It requires:
1. Building a custom DAX ranking measure.
2. Faking an inverted Y Axis in the Line Chart to display rank 1 at the top.
3. Modifying tooltips to handle rank inversion.

---

## Requirements

### Dataset
Use the **Financials sample dataset**, available in Power BI Desktop from October 2020 onward.

### Tasks

1. **Create a Ribbon Chart**  
   - Fields: `Date`, `Country`, `Sales`.  
   
2. **Build a DAX Measure for Ranking**  
   - Use a combination of:
     - `SUM`
     - `CALCULATE`
     - `ALLSELECTED`
     - `RANKX`
   - Reference: [DAX Guide](https://dax.guide)  

3. **Add a Line Chart**  
   - Fields: `Date`, `Country`, custom sales rank measure.
   - Add markers to the line chart.

4. **Invert the Y Axis for Bump Chart**  
   - Adjust the custom rank measure to display rank 1 at the top of the Y Axis.

5. **Modify Tooltip**  
   - Ensure positive numbers appear in both the Y Axis and the Tooltip.

---

## Visualizations

### Ribbon Chart
- Displays rank and measure values directly.
- Automatically sorts the highest rank at the top.

### Bump Chart
- Displays rank using a line chart with markers.
- Rank inversion and tooltip adjustment require additional DAX logic.

---

## Hints
- Explore the `SUM`, `CALCULATE`, `ALLSELECTED`, and `RANKX` functions.
- Use examples from the [DAX Guide](https://dax.guide).
- If stuck, expand the solution in the challenge for reference.

---

## Steps to Recreate

1. Open **Power BI Desktop**.
2. Load the **Financials sample dataset**.
3. Create a Ribbon Chart with:
   - Axis: `Date`.
   - Legend: `Country`.
   - Values: `Sales`.
4. Create a DAX measure to rank countries by sales:
   ```DAX
   Sales Rank = 
   RANKX(
       ALLSELECTED(Financials[Country]),
       CALCULATE(SUM(Financials[Sales])),
       ,
       ASC
   )
