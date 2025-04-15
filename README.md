<a href="https://www.microsoft.com/en-us/microsoft-365/excel" target="_blank"><img src="https://img.icons8.com/color/48/000000/microsoft-excel-2019--v1.png" width="36" height="36" alt="Excel" /></a>

# Workbook Summary

**Name:**  

## Table of Contents

- [Day 1: Task 1](#day-1-task-1)
- [Day 1: Task 2](#day-1-task-2)
- [Day 2: Task 1](#day-2-task-1)
- [Day 2: Task 2](#day-2-task-2)
- [Day 2: Task 3](#day-2-task-3)


---

## Day 1: Task 1

Tasks to be completed in `retail-sales_dataset.xlsx`:
1. Convert data (columns A–H) into a table.
 ![image](https://github.com/user-attachments/assets/916252e7-2d37-41e4-be1b-4ec696aea449)

3. Apply filter: Sort ‘Age’ from largest to smallest.
 ![image](https://github.com/user-attachments/assets/8127847a-2ca9-4f45-a43e-92eaed49f5f6)

5. Use `SUM` to calculate the total commission in cell `P10`.
![image](https://github.com/user-attachments/assets/38602e30-cabb-4802-ac0d-10d36fac8e1c)
 
7. Use `AVERAGE` to find the average commission in cell `P11`.
![image](https://github.com/user-attachments/assets/19e81fca-5069-4ea9-a11c-e5ed33523f2d)






---

## Day 2: Task 2

Work on **Task 2 worksheet** in the same Excel file. Task involves dataset manipulation and screenshot submission.

---

## Day 3: Task 1

Dataset: `Day_3_Task_1_Bike_Sales_Pivot_Lab.xlsx`

- Explore and practice Pivot Table creation.
- Answer reflection questions:

**Findings:**
- Germany has customers in the 35–64 age group.
- Australia has sales in all markets.
- Most profitable markets: Australia, Female, Young Adults & Adults.
- Additional insights:
  - USA has limited demand.
  - Youth purchases are limited to Australia, France, and some parts of the UK.
  - Most customers are 35–64.
  - Bikes are more popular among females.

---

## Day 3: Task 2

### Dataset Provided:

| County            | Product      | Sales Volume |
|------------------|--------------|--------------|
| Yorkshire         | Laptops      | 500          |
| Cornwall          | Laptops      | 700          |
| ...               | ...          | ...          |

### Instructions:
1. Create a Pivot Table (County as Rows, Product as Columns, Sales Volume as Values).
2. Add a column using the `SWITCH` function to classify Sales Volume:
   - `>600` → **High**
   - `300–600` → **Medium**
   - `<300` → **Low**

**Formula Example:**
```excel
=SWITCH(TRUE, C2 > 600, "High", C2 >= 300, "Medium", "Low")
