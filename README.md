# 3MTT-Class-Documentation
## Data Visulaization
---
visualization is summed up in three key points:

. Simple

. Consistent

. Concise


Visualizing data gives meaning when your audience can understand your data at a glance. 

So, its not really about you, that is why the three points above should guide you in your data visualization.



The third point (concise), is very key, as "less is more", which is what our tutor Saviour Henry illustrated in our last class. 



Depth is very important, in fact that is where you showcase your data visualization skills:



. Adding legends

. Adding labels

. Formatting grid lines

. Changing the data fonts and colors

. Renaming the titles



All of these make the difference.



What is even more important in all these is knowing the right chart to use and when to use them. Here's how:



. When the goal is to make comparisons, use Bar chart.

. When the goal is to monitor trends and progressions, use Line charts.

. When the goal is to illustrate proportions, use Pie charts.

. When you want to reveal relationships between variables, use Scatter plots.



. Histogram is to show data distribution, while Heatmaps emphasizes data density and connections- I'm still figuring these two out. 



So, here's what I learned last week in my 3MTT program.


## Excel Assignment

<img width="952" alt="3mtt data answers" src="https://github.com/user-attachments/assets/16cd5cd8-96ad-4daf-9e5b-17849981609c">

## 1. Dynamic Calculations with Cell References
- Explain the importance of cell references in Excel formulas and how they can be used to create dynamic calculations that adapt to changes in the dataset.
- **Absolute Referencing:** This locks both row and column (A$1 or $A$1) so it doesn't change when the cell is copied to a new location.
- **Relative Referencing:** Keeps the cell open (A1), when copied to a new cell, it changes.
- **Mixed Referencing:** This is when it is neither absolute or relative, a mix of both. (B$1 or $B1) This locks only one column or row.
- Cell references allow the formulas to adapt to changes in the dataset, making the analysis more flexible and reusable.
   - Absolute, relative, and mixed referencing provide different ways to lock or adjust cell references as needed.

## 2. Revenue Analysis
- Calculate the total revenue for transactions where the quantity or products sold exceeds 10 units. This will help identify high volume sales.
  - Formula used: `=IF(G2>10,F2*G2,0)` to calculate revenue for each transaction, and `=SUM(H2:H4)` to get the total revenue for the first three transactions.
  - Then, a formula is created to compute the total revenue across all transactions: `=SUM(H2:H101)`.
 - Transactions with quantity or products sold exceeding 10 units are identified as high-volume sales.
  
## 3. Data Insights
- Determine the average age of customers and identify trends in customer demographics.
  - Formula used: `=AVERAGE(D2:D101)` to calculate the average age.
  - Minimum age: `=MIN(D2:D101)`, Maximum age: `=MAX(D2:D101)`.
  - Difference between min and max age: `=MAX(D2:D101)-MIN(D2:D101)`.
- Analyze the minimum and maximum ages of customers and calculate the difference, giving insights into the age range of your customer base.
- The average age of customers is 40, with a range from 18 to 64, indicating the products serve a diverse age group.
   - The age difference between the minimum and maximum ages is 46, showing a significant age disparity among the customer base.

## 4. Precision in Financial Calculations
- Round total revenues to the nearest whole number, down to the nearest integer, and up to the nearest integer, ensuring accuracy in financial reporting.
  - Nearest whole number: `=ROUND(SUM(F2:F101),0)`.
  - Down to nearest integer: `=ROUNDDOWN(SUM(F2:F101),0)`.
  - Up to nearest integer: `=ROUNDUP(SUM(F2:F101),0)`.
- Calculate the square root of total revenue and raise it to the power of 2 for advanced financial modeling.
  - Square root of total revenue: `=SQRT(SUM(F2:F101))`.
  - Raise to power of 2: `=(SQRT(SUM(F2:F101)))^2`.

## 5. Advanced Excel Functions
- Use Excel functions to find the number of non-empty cells in the "Product Category" column and calculate the standard deviation of total revenue to understand the variability in sales.
  - Number of non-empty cells in "Product Category": `=COUNTA(C2:C101)`.
  - Standard deviation of total revenue: `=STDEV.P(F2:F101)`.
 - The number of non-empty cells in the "Product Category" column is 96, indicating the presence of data in most cells.
   - The standard deviation of total revenue is 99,033.91251, which provides insight into the variability in sales.

# Reporting and Visualization

<img width="611" alt="3mtt data assignment" src="https://github.com/user-attachments/assets/c40f1386-a5ce-480a-95ad-3fa10b201871">


# Advanced Pivot Table/ Creating Models and connecting pipes
## Date: November 27, 2024

In this detailed note, I will cover the key concepts and techniques related to advanced pivot table usage, with a focus on extracting data from columns with different data types and leveraging various functions and features to gain deeper insights.

### 1. Data Types in Columns:
- When working with pivot tables, it's essential to understand the different data types present in the columns, as this affects how you can extract and manipulate the data.
- For numeric data types, you can use functions like `=YEAR()` to extract the year from a date-formatted number (e.g., 201901).
- For text-formatted numeric data, you can use the `=RIGHT(cell, number_of_characters)` function to extract the desired number of characters from the right side of the cell.

### 2. Leveraging Filtering and Search Options:
- Pivot tables offer powerful filtering and search capabilities that allow you to quickly find and analyze specific data points.
- Learn how to utilize the filter options, such as filtering by value, text, or number, to narrow down your analysis and focus on the most relevant information.
- Explore the search function within the pivot table to quickly locate and highlight specific data or insights.

### 3. Handling Data Uniformity:
- Maintaining data uniformity is crucial for accurate analysis and reporting. Ensure that numeric data is consistently formatted, with leading zeros (e.g., 01, 10, 12) instead of varying formats (e.g., 1, 2, 10).

### 4. Understanding Variance and Absolute Variance:
- Pivot tables allow you to calculate both variance and absolute variance, which are essential metrics for understanding the changes in data over time.
- Variance measures the relative change, while absolute variance focuses on the absolute difference between values.
- Analyze these metrics to identify significant shifts in your data and uncover potential areas for improvement or further investigation.

### 5. Interpreting Subtotals and Grand Totals:
- Pivot tables often include subtotals and grand totals, which are calculated columns.
- Subtotals are indicated by a line above the value, while grand totals have a thicker line both above and below the value.
- Understanding these visual cues can help you quickly identify calculated fields and differentiate them from raw data.

### 6. Dynamic Naming and Cross-Sheet Referencing:
- Pivot tables can leverage dynamic naming conventions to make it easier to reference specific data points or calculations.
- Learn how to use cell references to link data from other sheets or workbooks, enabling you to build comprehensive and interconnected financial models.
- 


  <img width="838" alt="FDM analysis" src="https://github.com/user-attachments/assets/4dffc0f3-39dd-42ea-84a1-dba2182253c2">


### 7. Building a Financial Delivery Model (FDM):Class Practise
- A Financial Delivery Model (FDM) was created by selecting key columns and adding data for 2015 and 2016.
- The model includes calculations for net profit, FDM, and gross profit, among other important metrics.
- Analyze the insights from this FDM, focusing on variables, absolutes, and any available slicers to uncover trends, identify areas for improvement, and craft a compelling story-driven report.
- 

  [FDM Report.docx](https://github.com/user-attachments/files/17934208/FDM.Report.docx)



##Important Notes: STEPS
-Create the model (the FDM, add formulars to the models, dont worry about the values. When the pivots are created it will be updated when connected to the pipeline)
_ Create the pipeline (Pivot table)
- Connect the pipeline using dynamic refencing
- Add slicers to the report
- Create the report to tell the story about your model.





