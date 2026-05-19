# 🐐 Goat Farm Data Analysis Project

## 📌 Project Overview
This project is a data analysis system built using Python and Pandas.  
It analyzes goat farm records including health, feeding cost, breeding, and valuation.

---

## ⚙️ Features
- Load and merge multiple datasets (Goats, Health Records, Feeding Cost)
- Calculate total days using date difference
- Compute total feeding cost
- Handle missing values
- Calculate goat valuation
- Find top and low valued goats
- Group analysis by gender
- Sorting by valuation

---

## 🧰 Tools Used
- Python
- Pandas

---

## 📊 Key Calculations
- Total Days = End Date - DOB
- Total Cost = Daily Cost × Total Days
- Valuation = (Kids × Kids Age × 3000) - Total Cost

---

## 📈 Outputs
- Top Valuation Goat
- Lowest Valuation Goat
- Gender-wise Valuation Summary
- Sorted Goat Data

---

## 🚀 How to Run
1. Install pandas:
   pip install pandas

2. Place CSV files in same folder:
   - Goats.csv
   - Feeding_Cost.csv
   - Health_Record.csv

3. Run script:
   Goat_Farm_Data_Analysis.ipynb

---

## 👨‍💻 Author
Mohsin Yaseen

---

## 📌 Note
This project is for learning purposes and can be extended into a full farm management system.
