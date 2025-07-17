# 📊 Loan Data Analysis

This repository showcases advanced **Excel techniques** for analyzing real-world loan data across multiple districts and branches. It includes dynamic dashboards, data cleaning, VBA automation, Power Pivot models, and integration strategies for SQL Server.

---

## 📁 Datasets Used
- `LoanDashBoard.xlsx`: Contains loan data by district and thana.
- `LoanInfo.xlsx`: Detailed loan breakdown.
- `Performance.xls`: Branch-wise performance metrics.
- `PythonData.csv`: Mixed-format data with inconsistencies.

---

## ✅ Excel Techniques Demonstrated

### 🔍 1. Advanced Lookup and Reference Functions
- **INDEX + MATCH**: Flexible multi-column lookups.
- **XLOOKUP**: Modern two-way lookup with error handling.

📌 _Example_:  
```excel
=INDEX(LoanDashBoard!D:D, MATCH("Chuadanga"&"Alamdanga", LoanDashBoard!A:A&LoanDashBoard!B:B, 0))

