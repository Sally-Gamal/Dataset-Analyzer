# DatasetAnalyzer 

**DatasetAnalyzer** is a simple and powerful Python tool for **automatic data analysis** and **basic cleaning** of CSV datasets.  
It is designed to be **easy to use**, requires **no user input**, and is perfect for students, analysts, or beginners in data science.

---

## 🔹 Features

- Loads a predefined CSV dataset
- Displays **data overview**:
  - Number of rows and columns
  - First 5 rows
  - Column information and data types
- Checks for **missing values** and **duplicated rows**
- Removes **duplicated rows** automatically
- Saves a **cleaned version** of the dataset

---

## 🔹 How to Use

1. Put your CSV file in the same folder as `DatasetAnalyzer.py`  
2. Make sure the filename in the code matches your CSV file:
```python
file_name = "your_file.csv"

3. Run the script: python DatasetAnalyzer.py

4. After running, the cleaned dataset will be saved as:

🔹 Example Output

📊 Data Overview
----------------------------------------
📏 Rows: 1000
📐 Columns: 12
----------------------------------------

🔝 First 5 Rows:
   Country  Students  Year
0  USA      1200      2020
1  UK       900       2020
...

📝 Columns Info:
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 1000 entries, 0 to 999
Data columns (total 12 columns):
...
----------------------------------------

❗ Missing Values:
0️⃣ No missing values

🔁 Duplicated Rows:
0️⃣ No duplicated rows

🧹 Cleaning data...
✅ Data analysis & cleaning completed
💾 Clean file saved as: your_file_cleaned.csv

## 🔷 **Requirements**
- 🐍 **Python 3.x**
- 📚 **Libraries:**
  - `pip install pandas`
  - `pip install numpy`

## 🔷 **Notes**
- ⚠️ **Manual Handling:** The script does **not automatically fill** missing numeric values — please handle them manually if required.
- 📂 **File Location:** Make sure your **CSV file** is in the **same folder** as the script.
- 🚀 **Beginner-Friendly:** Designed to be **lightweight** and easy to understand.

