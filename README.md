
# 📚 Library Management System

A **database-driven Library Management System** designed to manage book inventory, borrowers, loans, and library branches.
This project uses **SQL and Python** to analyze library data and generate **business insights** for better decision-making.

---

## 👨‍💻 About Me

**Akshaya Surwase**
Bachelor of Engineering (Computer Engineering)
Savitribai Phule Pune University

During my academic journey, I worked with **Python and SQL**, exploring data manipulation, analysis, and visualization.
This project reflects my interest in **data analysis and database systems**, focusing on real-world problem-solving.

---

## 🎯 Objective

To design and analyze a **Library Management System database** that:

* Tracks book inventory and copies
* Manages borrowers and loans
* Analyzes branch-wise activity
* Extracts insights using **SQL queries and Python visualizations**

---

## ❗ Problem Statement

Traditional library systems struggle with:

* Tracking book availability across branches
* Monitoring loan activity and borrower behavior
* Identifying seasonal borrowing trends
* Optimizing underutilized branches

This project addresses these challenges using a **relational database model** and data analysis.

---

## 🗂️ Database Tables

The system consists of the following tables:

* `tbl_book`
* `tbl_book_authors`
* `tbl_book_copies`
* `tbl_book_loans`
* `tbl_borrowers`
* `tbl_library_branch`
* `tbl_publisher`

---

## 🧩 ER Diagram

The database is designed using a structured **Entity Relationship (ER) Diagram** to clearly define:

* Relationships between books, authors, and publishers
* Loan transactions between borrowers and branches

*(ER diagram included in the project presentation)*

---

## 📊 Key Business Insights

### 🔹 High Loan Activity in January 2018

* Most book loans occurred in **January 2018**
* Indicates **seasonal borrowing trends**, likely aligned with academic calendars

### 🔹 Inconsistent Loan Activity Across Months

* Significant drop in activity in later months (e.g., February 2019)
* Possible reasons:

  * Data gaps
  * Operational changes
  * Lack of new inventory

### 🔹 Branch-wise Performance Variation

* Branches like **Ann Arbor** show consistently high loan volumes
* Branches such as **Sharpstown, Central, and Saline** are underutilized
* Highlights scope for **inventory redistribution and engagement strategies**

---

## ⚙️ Challenges Faced

### 📌 Date Import Issues

* `DateOut` and `DueDate` columns failed to import due to inconsistent formats (MM/DD/YY)
* Solution:

  * Temporarily converted columns to `VARCHAR`
  * Used `STR_TO_DATE()` in MySQL to convert and store proper date values

### 📌 Complex SQL Joins

* Faced difficulties while merging multiple tables
* Improved understanding of **JOIN operations** through practice and debugging

---

## ✅ Conclusion

This project successfully demonstrates:

* Database design using relational models
* SQL-based data analysis
* Identification of borrowing patterns and branch performance
* Practical problem-solving in real-world data scenarios

The insights derived can help libraries **optimize inventory**, improve user engagement, and enhance operational efficiency.



Just say the word 😄
