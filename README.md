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







