# Singapore MRT Ridership Analysis

## Overview

This project analyzes Singapore's MRT ridership data to identify trends, peak periods, and growth patterns using **SQL CTEs** and **window functions**. Designed to showcase skills relevant to Singapore's data analyst job market (e.g., GovTech, LTA, or transport startups).

---

## 📊 Project Objectives

1. Calculate **month-over-month ridership growth** for MRT stations.
2. Identify stations with the **highest growth rates**.
3. Compare weekday vs. weekend ridership trends.
4. Practice **CTEs + window functions** for real-world analysis.

---

## 📂 Dataset

**Source**: [LTA DataMall - Train Ridership](https://www.mytransport.sg/content/mytransport/home/dataMall.html)  
**Key Columns**:

- `station` (e.g., "Jurong East", "City Hall")
- `month` (YYYY-MM format)
- `ridership` (number of passengers)

---

## 🛠️ Tools Used

- **SQL**: CTEs, `LAG()`, `RANK()`, window functions
- **Python**: `pandas` for data cleaning, `matplotlib` for visualization
- **SQLite**: Database management

---

## ❓ Business Questions  

### 1️⃣ **Find the month-over-month ridership growth for each station.**  
