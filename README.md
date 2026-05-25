# 🛒 DecodeLabs Project 1 — E-Commerce Sales Analysis

## 📌 Overview
End-to-end data analysis on a real-world e-commerce sales dataset 
with 1,200 orders and 14 features using Python in Google Colab.

---

## 📂 Dataset Features
| Column | Type |
|---|---|
| OrderID, CustomerID | Object |
| Date | DateTime |
| Product, PaymentMethod | Object |
| OrderStatus, ShippingAddress | Object |
| Quantity, ItemsInCart | Integer |
| UnitPrice, TotalPrice | Float |
| TrackingNumber, CouponCode | Object |
| ReferralSource | Object |

---

## 💾 Data Files
| File | Description |Link |
|---|---|------|
| ⁠ Dataset for Data Analytics.xlsx ⁠ | Original raw dataset |[📄 View](https://github.com/ramjotkaur0927-ops/DecodeLabs-Internship/blob/main/Dataset%20for%20Data%20Analytics.xlsx) |
| ⁠ Cleaned_Dataset.xlsx ⁠ | Cleaned & processed dataset |[✅ View](https://github.com/ramjotkaur0927-ops/DecodeLabs-Internship/blob/main/Cleaned_Dataset.xlsx) |

---

## 🔧 What I Did

### 1️⃣ Data Loading
•⁠  ⁠Loaded Excel dataset using ⁠ pd.read_excel() ⁠
•⁠  ⁠Explored shape, dtypes, and null counts

### 2️⃣ Data Cleaning
•⁠  ⁠Filled numeric nulls with *median*
•⁠  ⁠Filled categorical nulls with *"unknown"*
•⁠  ⁠Removed *duplicate rows*
•⁠  ⁠Converted ⁠ Date ⁠ column to proper DateTime format

### 3️⃣ Export
•⁠  ⁠Saved cleaned data as ⁠ Cleaned_Dataset.xlsx ⁠

---

## 🛠️ Tech Stack
•⁠  ⁠Python | Pandas | NumPy | Google Colab | GitHub

---

## ▶️ How to Run
1.⁠ ⁠Open ⁠ Decodelabs_Project_1.ipynb ⁠ in Google Colab
2.⁠ ⁠Upload ⁠ Dataset for Data Analytics.xlsx ⁠
3.⁠ ⁠Run all cells top to bottom
4.⁠ ⁠⁠ Cleaned_Dataset.xlsx ⁠ will be generated

---

## 👩‍💻 Author
*Ramjot Kaur* — Data Analyst Intern @ DecodeLabs  
[GitHub](https://github.com/ramjotkaur0927-ops)
