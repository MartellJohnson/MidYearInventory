# 🧾 SSRS Physical Inventory Reporting

<img width="957" height="371" alt="Screenshot 2025-07-21 102234" src="https://github.com/user-attachments/assets/c4767130-8b8e-4137-a57b-759f5da5ab19" />

## 📘 Overview
This project automates the creation of **Physical Inventory Sheets** used across warehouse, logistics, and production environments. It leverages **SQL Server views** and **Microsoft Report Builder (SSRS)** to generate printable reports by bin and building.

## 💡 Problem
Before this solution, physical inventory was managed manually using spreadsheets for more than **44,000 SKUs**, leading to inefficiencies, data entry errors, and lack of consistency during audits.

## ✅ Solution Highlights
- Replaced spreadsheet-based inventory count process with automated SSRS reports
- Pulled live data from ERP views: `v_item_master`, `v_inventory_mstr`, `V_PRODUCT_LINE`
- Applied SQL logic to classify BINs and BUILDINGS, including special zones like staging or casting
- Grouped reports by location and formatted with auditor/counter signature lines

## 🧰 Tools Used
| Tool                       | Purpose                                    |
|----------------------------|--------------------------------------------|
| SQL Server                 | Data queries and transformation logic      |
| Microsoft Report Builder   | SSRS design and report printing            |
| Global Shop Solutions ERP  | Source of inventory and bin data           |

## 📈 Impact
- **Saved 40+ hours** per full inventory cycle
- **Reduced errors** by removing manual bin classifications
- **Standardized reporting** across departments and buildings
- **Supported audit readiness** and contributed to a smooth **business sale process**

## 📂 Project Files
- `SSRS_Physical_Inventory_Full_Documentation.ipynb`: Full technical breakdown and SQL logic
- `SSRS_Physical_Inventory_Report.rdl`: SSRS report definition file (not included here)
