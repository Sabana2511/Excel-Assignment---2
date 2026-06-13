# 📊 Excel Assignment 2 – Data Cleaning and Transformation

## 📌 Project Overview

This project focuses on cleaning, transforming, and formatting a product dataset using Microsoft Excel. 
The objective is to improve data quality by handling missing values, correcting inconsistencies, removing duplicates, 
splitting and merging data, applying number formatting, and using conditional formatting techniques.

---

## 🎯 Objectives

* Handle missing values in the dataset.
* Correct inconsistent text formats and category typos.
* Identify and remove duplicate records.
* Split and merge columns for better data organization.
* Apply appropriate number and date formatting.
* Use conditional formatting for enhanced data visualization.

---

## 📂 Dataset Information

The dataset contains the following fields:

| Column Name  | Description                                                       |
| ------------ | ----------------------------------------------------------------- |
| Product ID   | Product identifier containing manufacturing date and country code |
| Product Name | Name of the product                                               |
| Brand Name   | Brand associated with the product                                 |
| Price ($)    | Product price                                                     |
| Quantity     | Available quantity                                                |
| Category     | Product category                                                  |

---

## 🛠 Tasks Performed

### 1️⃣ Handling Missing Values

* Identified missing values in the **Price ($)** column & **Category** column.
* Replaced or imputed missing prices using appropriate Excel techniques.
* Filled missing categories based on similar products and existing category patterns.

**Functions Used:**

* `IF`
* `IFERROR`
* `ISBLANK`
* `AVERAGE`
* `INDEX`
* `MATCH`

---

### 2️⃣ Correcting Inconsistent Data

* Standardized text formatting in the **Product Name** column.
* Corrected spelling mistakes and inconsistencies in the **Category** column.
* Used Excel's **Find & Replace** feature for bulk corrections.

**Examples:**

* laptop → Laptop
* electroni → Electronics

---

### 3️⃣ Removing Duplicates

* Checked the dataset for duplicate records.
* Removed duplicate rows using Power Query's **Remove Duplicates** feature.

---

### 4️⃣ Splitting and Merging Data

#### Product ID Split

Extracted:

* **Manufacturing Date**
* **Country Code**


#### Product Brand Creation

Merged:

* Brand Name
* Product Name

into a new column:

**Product Brand**

Example:

* Dell Laptop
* Nike Sneakers

**Functions Used:**

* `&`

---

### 5️⃣ Number Formatting

* Formatted **Price ($)** as Currency.
* Formatted **Manufacturing Date** as **DD-MM-YYYY**.

---

### 6️⃣ Conditional Formatting

Applied:

* Data Bars on the **Price ($)** column.
* Highlighting rule for products belonging to the **Electronics** category.

This improves data visualization and helps identify key records quickly.

---

## 📈 Skills Demonstrated

* Data Cleaning
* Data Transformation
* Missing Value Treatment
* Text Standardization
* Duplicate Management
* Excel Functions
* Conditional Formatting
* Data Formatting
* Data Preparation

---

## 🔧 Excel Features & Functions Used

* IF
* IFERROR
* ISBLANK
* Find & Replace
* Remove Duplicates
* Conditional Formatting
* Currency Formatting
* Date Formatting

---

## ✅ Outcome

The dataset was successfully cleaned, standardized, and transformed into a more accurate and analysis-ready format. 
This project demonstrates practical Excel data-cleaning techniques commonly used in data analytics and business reporting workflows.

---

### 👩‍💻 Author

**Sabana Asmi**

Data Analytics Learning Project | Data Cleaning & Transformation
