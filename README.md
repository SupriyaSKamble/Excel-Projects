<a href="https://www.microsoft.com/en-us/microsoft-365/excel" target="_blank"><img src="https://img.icons8.com/color/48/000000/microsoft-excel-2019--v1.png" width="36" height="36" alt="Excel" /></a>
![Excel Logo](https://upload.wikimedia.org/wikipedia/commons/7/73/Microsoft_Excel_2013_logo.svg)
![Excel Logo](excel.png)
# Workbook Summary

**Name:**  
**Course Date:**  

...

**Name:**  
**Course Date:**  

---

## Table of Contents

- [Day 1: Task 1](#day-1-task-1)
- [Day 2: Task 1](#day-2-task-1)
- [Day 2: Task 2](#day-2-task-2)
- [Day 3: Task 1](#day-3-task-1)
- [Day 3: Task 2](#day-3-task-2)
- [Day 3: Task 3](#day-3-task-3)
- [Course Notes](#course-notes)
- [Additional Information](#additional-information)

---

## Day 1: Task 1

Research and respond to key data protection laws and their relevance in customer data handling:
- **Data Protection Act**
- **GDPR**
- **Freedom of Information Act**
- **Computer Misuse Act**

Each section should cover:
- What it is  
- Why it’s important  
- Real-world example  
- Data work impact  
- Consequences of breaching  

---

## Day 2: Task 1

Tasks to be completed in `retail-sales_dataset.xlsx`:
1. Convert data (columns A–H) into a table.
2. Apply filter: Sort ‘Age’ from largest to smallest.
3. Use `SUM` to calculate total commission in cell `P10`.
4. Use `AVERAGE` to find average commission in cell `P11`.

Screenshots of results were added in workbook.

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
