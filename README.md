# 🔄 End-to-End Sales Data Analytics & ETL Pipeline

An automated **Data Analytics ETL (Extract, Transform, Load) Pipeline** demonstrating raw data ingestion, automated cleaning and normalization with Python, relational database staging, and interactive **Power BI** dashboard reporting.

---

## 📌 Workflow Overview
```
[Raw Messy Data: sales_raw_500.xlsx]
                 │
                 ▼
[Python ETL / DataCleaning.ipynb] ──► Handling nulls, formatting dates, types & validation
                 │
                 ▼
[Cleaned Production Data: Sales_cleaned.CSV]
                 │
                 ▼
[Relational DB / MySQL Staging]
                 │
                 ▼
[Power BI Dashboard: SalesGrowth.pbix] ──► KPI Tracking, MoM/YoY Revenue Acceleration
```

---

## 🛠️ Tech Stack & Components
- **Python (Pandas, NumPy):** Missing value imputation, string trimming, data type coercion, validation rules (`DataCleaning.ipynb`).
- **Relational Storage:** MySQL Schema Design & Table Constraints.
- **Power BI:** Dynamic visual reporting tracking revenue trends and product sales (`SalesGrowth.pbix`).

---

## 📁 Repository Structure
```
├── DataCleaning.ipynb      # Complete Python extraction & cleaning pipeline
├── sales_raw_500.xlsx      # Raw transactional input dataset
├── Sales_cleaned.CSV       # Cleaned, transformed output ready for SQL/BI
├── SalesGrowth.pbix        # Interactive Power BI Sales Growth Dashboard
└── README.md               # Project documentation
```

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/MianSabooh/Sales-ETL-Pipeline-PowerBI.git
   ```
2. Run the cleaning notebook in Jupyter:
   ```bash
   jupyter notebook DataCleaning.ipynb
   ```
3. Open `SalesGrowth.pbix` in Power BI Desktop to view the sales growth metrics.
