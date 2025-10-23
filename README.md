# 🧹 Data Cleaning Excel Project – **U.S. Presidents Dataset**

This repository showcases my **Excel-based data cleaning project**, where I worked on a **real-world dataset** containing information about **U.S. Presidents**.  
The dataset initially had **duplicate records**, **inconsistent text formatting**, **extra spaces**, **special symbols**, and **irrelevant columns**.

The goal of this project is to demonstrate my **end-to-end Excel data-cleaning workflow** through a structured, step-by-step approach—transforming raw, inconsistent data into a **clean and analysis-ready** dataset.

---

## 🎯 **OBJECTIVE**

To **clean and organize** an unstructured U.S. Presidents dataset by:

- **Removing duplicate records**
- **Standardizing name formats** (Proper Case)
- **Correcting spelling inconsistencies** in political parties
- **Trimming extra spaces** in Vice President names
- **Converting salary values to numeric** format
- **Standardizing date formats** across records
- **Deleting irrelevant columns** (e.g., *Prior* details, redundant serial numbers)

---

## 🧾 **Problem Description**

The **raw dataset** was inconsistent and unsuitable for analysis. Key issues identified:

- **Duplicate entries** in the President records  
- **Mixed letter casing** (e.g., **GEORGE WASHINGTON** vs **George Washington**)  
- **Party name variations** (e.g., **Republican** vs **Republicans**)  
- **Extra spaces** in the **Vice President** column  
- **Salary values stored as text** with “$” and “cents”  
- **Inconsistent date formats**  
- **Unnecessary columns** that didn’t contribute to analysis

Because of these issues, the dataset required **significant cleaning** before visualization or reporting.

---

## 🧰 **Tools and Features Used**

All cleaning was performed in **Microsoft Excel**, using formulas and built-in tools:

### **Excel Features**
- **Remove Duplicates** → identify and eliminate repeated records  
- **Filter & Sort** → detect inconsistencies in categorical fields like **Party**  
- **Number Formatting** → convert salary **text** values to **numeric**  
- **Date Formatting (Short Date)** → unify inconsistent date patterns

### **Excel Formulas**
- ``=PROPER(cell)`` → **Proper Case** conversion (e.g., “**JAMES MONROE**” → “**James Monroe**”)  
- ``=TRIM(cell)`` → remove **leading/trailing/double spaces** (used on **Vice President** names)

### **Column Management**
- Deleted **irrelevant fields** (duplicate **Serial No.**, unnecessary **Prior** info) to keep the dataset **concise and readable**.

---

## 🪜 **Step-by-Step Cleaning Process**

1. **Removed Duplicate Records**  
   - Used **Data → Remove Duplicates**; identified and deleted one redundant record.

2. **Standardized Name Formatting**  
   - Applied ``PROPER()`` on the **President Name** column to fix all-caps entries.

3. **Corrected Party Spelling Errors**  
   - Fixed inconsistencies (e.g., **“Republicans”** → **“Republican”**; cleaned **Whig** entries with extra text).

4. **Trimmed Extra Spaces**  
   - Applied ``TRIM()`` to the **Vice President** column to eliminate unnecessary spaces.

5. **Converted Salary to Numeric Values**  
   - Removed **$** symbols and decimals; converted salaries from **text** to **numbers**.

6. **Standardized Date Formats**  
   - Unified all dates using **Short Date** under **Format Cells**.

7. **Removed Unnecessary Columns**  
   - Deleted duplicate **Serial No.** and **Prior** columns that didn’t add analytical value.

8. **Final Verification**  
   - Validated data consistency; ensured all columns follow standardized **formats and values**.

---

## 🧩 **Outcome**

- ✅ Dataset is **clean, structured, and analysis-ready**  
- ✅ **Duplicates, spelling inconsistencies, and extra spaces** removed  
- ✅ **Salary** and **Date** fields properly formatted  
- ✅ Consistent schema suitable for **Power BI**, **Tableau**, or **database** import

---

## 📚 **Learning Reflection**

Through this project, I learned to:

- **Identify and correct** real-world data inconsistencies through validation  
- Use **Excel formulas** effectively for text cleaning and standardization  
- Apply **filtering/formatting** to spot and resolve errors quickly  
- Maintain **data integrity** while transforming messy data into reliable inputs

This project strengthened my confidence in **data-cleaning fundamentals** and built a strong foundation for transitioning to **Python (Pandas)** and **Power BI** for advanced analytics and automation.

---

## 👩‍💻 **Author**

**Soundarya Poovaiah Kookanda**  
📧 **soundaryakookanda@gmail.com**  
🎓 **Master of Engineering in Computer Science — University of Cincinnati**


