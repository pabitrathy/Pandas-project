This repository contains data cleaning and analysis projects done using **Pandas** as part of my Data Engineering preparation. Each dataset represents common real-world tasks like handling missing data, grouping, filtering, merging, and exporting to various formats.

---

## 📁 First Project

### 1. Employees Dataset
Tasks Completed:
1. Filled missing `Salary` values using the average salary.
2. Calculated **average salary by department** using `groupby`.
3. Filtered and displayed employees who **joined after 2021** using datetime conversion.

### 2. Sales Dataset
Tasks Completed:
1. Created a new column `Total_Amount` = `Quantity × Price`.
2. Grouped by **Category** and calculated **total sales per category**.
3. Sorted and displayed the **top 3 most expensive products**.

---

## 📁 Second Project

### 3. Students Dataset
Tasks Completed:
1. Filter all students from the **CS department**
2. Calculate the **average marks per department**
3. Show students who **joined after 2022**
4. Add a new column `Grade`:
   - ≥90 → A
   - 75–89 → B
   - <75 → C
5. Convert `Join_Date` to datetime and **extract the year**

### 4. Orders Dataset
Tasks Completed:
1. Create a new column: `Total_Amount = Quantity × Price`
2. Show **total sales by category**
3. Show all orders **after May 2023**
4. Find the **top 2 customers** by total amount spent
5. Sort the orders by `Order_Date` (newest first)

---

## 📁 Third Project

### Students.csv
1. Replaced missing `Total_Marks` with average marks
2. Filtered students who passed and scored more than 80
3. Calculated average marks per department
4. Counted number of students who passed vs failed
5. Created a new column `Performance`

### Orders.csv
1. Converted `Order_Date` to datetime & extracted month
2. Created `Total_Amount = Quantity × Unit_Price`
3. Calculated total sales per category
4. Displayed top 5 products by revenue
5. Counted number of orders per month

---

