# Workout Wednesday 2021 Week 4 | Power BI: Drill Through

![image](https://github.com/user-attachments/assets/3bc6b444-f84f-470a-9e6c-3da8789aaba4)
![image](https://github.com/user-attachments/assets/ced94145-5b31-4446-b4e4-83a7b2cd504b)



Welcome to my solution for the **Workout Wednesday 2021 Week 4** challenge! This repository showcases my approach to the fourth Power BI challenge of the year, which focuses on implementing drill through functionality in Power BI.

## Challenge Overview

This week's challenge involves adding drill through capabilities to an existing Power BI report that focuses on NCAA athletic department expenses and revenues. We will build on the previous reports created in Weeks 1, 2, and 3, and enable further analysis by allowing users to drill through from a summary view to a detailed school view.

### Requirements:
1. **Create a new "School View" tab:**
   - Replace the `[Conference Abb]` fields in your bar charts with `[School Abb]`.
   
2. **Enable Drill Through:**
   - Create drill through functionality from the `Summary View` tab to the new `School View` tab.

3. **Add a Card for Conference Display:**
   - Add a card to indicate which conference the user is viewing in the `School View`.

4. **Desynchronize Year Slicers:**
   - Ensure that year slicers are not synced between the `Summary View` and `School View` tabs.

5. **Analyze MAC Losses:**
   - Determine who contributed the most to the MAC's financial losses in 2016.

### Dataset:
- This week's dataset provides a breakdown of NCAA athletic department expenses and revenues by year. You can find the dataset [here at data.world](https://data.world/jbaucke/2021-w1-power-bi-wow-ncaa-financials).

## Solution

The solution includes:
- A new `School View` tab with drill through capabilities from the `Summary View`.
- A card that dynamically displays the selected conference in the `School View`.
- Independent year slicers on both the `Summary View` and `School View` tabs.
- Analysis of the MAC conference's losses in 2016, identifying the main contributors.

Thank you for checking out my solution. I hope it helps you with your own Power BI projects!
