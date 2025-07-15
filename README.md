# 🗃️ Data Anomalies – First Normal Form (1NF)

This repository contains practical exercises and SQL scripts designed to explore **database normalization** up to the **First Normal Form (1NF)**. The goal is to demonstrate how to restructure data to reduce redundancy, enforce atomicity, and prevent common data anomalies.

## 📚 Overview

**Database normalization** is a design strategy that organizes data to minimize redundancy and improve data integrity. In this notebook and its associated exercises, we walk through the transformation of a denormalized dataset into 1NF.

The exercises focus on:

- Identifying non-atomic columns.
- Splitting composite columns into atomic values.
- Duplicating rows where necessary to ensure each field contains a single value.
- Understanding how normalization reduces insert/update/delete anomalies.

## 🎯 Learning Objectives

- Understand the **First Normal Form (1NF)** and its rules.
- Practice **column splitting** and **row duplication** in SQL to enforce atomicity.
- Explore **data anomalies** and how 1NF addresses them.
- Prepare the database for further normalization (2NF and 3NF).

## 🧰 Tools & Requirements

- **SQLite3** or **DB Browser for SQLite**
- **SoftDevEmployees.db** (included or downloadable)
- SQL environment (Notebook, SQLite CLI, or integrated tool like VS Code or DBeaver)

> ⚠️ This project modifies the database. Please keep a backup copy of the original `SoftDevEmployees.db` file if you wish to redo exercises.

## 📂 Folder Structure

```text
.
├── README.md
├── SoftDevEmployees.db         # SQLite database file
├── 1NF_Normalization.sql       # SQL scripts for transforming to 1NF
├── 1NF_Data_Anomalies.md       # Markdown notes and reflection
└── notebook_1NF_exercise.ipynb # Optional Jupyter Notebook version
```
## 🛠️ Setup & Usage
1. Clone this repository:
```
git clone https://github.com/your-username/1NF-normalization-anomalies.git
cd 1NF-normalization-anomalies
```
2. Open the database file with your preferred SQL editor (e.g., DB Browser for SQLite).

3. Run the SQL script step-by-step to transform the data structure.

4. Review and reflect on anomalies before and after 1NF normalization.

## 📈 Sample Concepts Covered
- `SUBSTR()` and `INSTR()` functions in SQL for string manipulation.

- Use of `CASE WHEN` to handle multi-valued fields.

- Duplicate row generation to normalize multi-valued columns.

- Data integrity improvements via atomic columns and primary keys.

## ✅ Outcomes
By the end of this project, you'll have hands-on experience with:

  - Identifying and resolving data anomalies (insertion, deletion, update).
  
  - Applying 1NF normalization principles to real-world datasets.
  
  - Building a clean base for progressing toward 2NF and 3NF.

📫 Contact
**Author**: Ibrahim Ambale
📍 Nairobi, Kenya
🔗 LinkedIn: [Ibrahim Ambale](https://linkedin.com/in/ibrahim-ambale/)
🌐 Website: [Ibrahim Ambale](https://tikeyambale.wixsite.com/ibrahim-ambale)
