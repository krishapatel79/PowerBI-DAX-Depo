# DAX Depo – Advanced Calculations Using DAX in Power BI

## Project Overview

This project is part of the **DAX Depo** assessment and focuses on building a backend analytical model in **Power BI** using **DAX**. The goal is to generate advanced calculations on Sales and Returns data **without using visual charts**, except for **Matrix visuals**, as specified in the project instructions.

All insights are derived using:

* Calculated Columns
* Measures
* Quick Measures
* Time Intelligence
* Filter Context manipulation

---

## Dataset Used

The project uses the following tables from the provided Excel dataset:

* **Sales_Fact** – Sales transaction details
* **Returns_Fact** – Returned items data
* **Customer_Dim** – Customer attributes
* **Product_Dim** – Product information
* **Date_Dim** – Calendar and date fields
* **Region_Dim** – Regional mapping

---

## Data Model

* Star schema design
* One-to-many relationships from dimension tables to fact tables
* Single-direction filtering

---

## Measures Created

All measures are stored in a **dedicated Measures table**.

* Total Sales
* Total Cost
* Total Profit
* Return Rate (%)
* Average Sale per Transaction
* Sales (All Regions – using ALL)
* Sales (With Filters)

Iterator Functions:

* Total Profit using SUMX, AVERAGEX

---

## Time Intelligence Measures

* **Year-to-Date (YTD) Sales**
* **Same Period Last Year Sales**
* **Running Total Sales**

Functions used:

* TOTALYTD
* SAMEPERIODLASTYEAR
* DATESBETWEEN

---

## Filter Context & DAX Functions Covered

* CALCULATE
* FILTER
* ALL
* IF, AND, OR
* SWITCH
* SUM, AVERAGE, MAX
* COUNTX, DISTINCTCOUNT
* SUMX, AVERAGEX
* YEAR, MONTH, EOMONTH
* CONCATENATE, LEFT, UPPER

---

## Deliverable

* Power BI (.pbix) file
* All calculations created using DAX
* Fully compliant with project instructions

---

## Notes

This project is designed to demonstrate strong understanding of:

* DAX fundamentals
* Context transition
* Time intelligence
* Analytical modeling best practices

---