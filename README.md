# Sales-Data-Cleaning-Project_DecodeLabs
Internship Project 1 at DecodeLabs: Data Cleaning &amp; Preparation using Python (Pandas) in Google Colab. Focused on handling missing values, removing duplicates, correcting formats, and documenting changes for data integrity.
# DecodeLabs Internship Project 1: Data Cleaning & Preparation

## 📌 Overview
This repository contains my work for **Project 1: Data Cleaning & Preparation** during my DecodeLabs internship.  
The goal is to transform raw, messy datasets into reliable sources of truth by:
- Handling missing values
- Removing duplicates
- Correcting data formats (dates, numbers, text)
- Documenting all changes for transparency

---

## 🛠 Tools & Environment
- **Google Colab** (Python 3)
- **Pandas** for data cleaning
- **OpenPyXL** for Excel support
- **GitHub** for version control & portfolio showcase

---

## 📊 Dataset
The dataset used is `Dataset for Data Analytics(DECODELAB).xlsx`, containing e-commerce order records with attributes such as:
- OrderID, Date, CustomerID
- Product, Quantity, UnitPrice, TotalPrice
- ShippingAddress, PaymentMethod, OrderStatus

---

## 🔧 Steps Performed
1. **Loaded dataset** into Colab using Pandas.
2. **Handled missing values** (median imputation for numeric fields).
3. **Removed duplicates** to ensure unique records.
4. **Corrected formats**:
   - Dates → ISO 8601 (`YYYY-MM-DD`)
   - Numeric precision → rounded to 2 decimals
   - Text fields → trimmed & standardized case
5. **Integrity audit**:
   - Verified unique OrderIDs
   - Checked date formats
6. **Documented changes** in a change log.

---

## 📑 Change Log Example
| Change ID | Description                     | Impact                        | Status   |
|-----------|---------------------------------|--------------------------------|----------|
| CR001     | Imputed `UnitPrice` using Median | Preserved records with missing values | Resolved |
| CR002     | Removed duplicate OrderIDs       | Ensured unique transactions    | Resolved |

---

## 🚀 How to Run
1. Open the notebook in Google Colab.
2. Upload the dataset (`Dataset for Data Analytics(DECODELAB).xlsx`).
3. Run all cells to reproduce the cleaning process.
4. Export the cleaned dataset as `Cleaned_Dataset.xlsx`.


## 🎯 Outcome
By completing this project, I demonstrated:
- Ability to clean and prepare raw datasets
- Understanding of data integrity principles
- Documentation of analytical decisions
- Portfolio-ready project hosted on GitHub




