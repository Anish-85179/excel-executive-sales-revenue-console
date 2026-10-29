# Dark-Mode Executive Sales & Revenue Analytics Console (Excel Portfolio Project #3)

## 📁 File Name
`Dark_Mode_Executive_Sales_Console.xlsx`

## 📦 Repository Name
`excel-executive-sales-revenue-console`

## 📝 Description (50 Words)
An enterprise-grade financial analytics console built in Microsoft Excel featuring a sleek dark-mode aesthetic. It integrates 100 raw transaction records, automated Pivot Engine aggregations, and dynamic KPI cards. Enhanced with interactive Slicers, custom dark-themed charts, and lookup reference tables, it delivers a polished, Apple-grade executive command center for real-time business intelligence.

---

# README.md

```markdown
# Dark-Mode Executive Sales & Revenue Analytics Console

An enterprise-grade financial and sales analytics console built natively in **Microsoft Excel**. This project establishes an Apple-grade minimalist dark-mode reporting environment (`#121212` canvas) to ingest raw enterprise transactions, execute automated calculations, aggregate performance metrics through a dedicated calculation engine, and present real-time intelligence via an executive command center dashboard.

---

## 🏗️ Workbook Architecture & Structure

The workbook is structured into **4 sequential operational sheets**:

1. **`Raw_Data`** — Ingestion layer containing 100 enterprise sales transaction records with columns for Order ID, Date, Sales Region, Product Category, Product Name, Units Sold, Unit Price, Total Revenue (`=F*G`), and Sales Rep[cite: 7].
2. **`Pivot_Engine`** — Calculation backend housing structured aggregation tables using robust `SUMIF` formulas to summarize total volume and revenue dynamically by Sales Region and Product Category[cite: 6].
3. **`Dashboard`** — Executive command center featuring top-line KPI summary blocks, linked summary tables, custom dark-themed charts, and interactive Slicers for real-time data filtering.
4. **`Lookup_Reference`** — Metadata repository storing commission tiers, incentive schedules, regional target benchmarks, and regional manager mappings with professional dark-mode zebra striping[cite: 4].

---

## 🛠️ Core Technical Implementation & Formulas

### 1. Automated Revenue Calculation (`Raw_Data`)
* **Extended Line Revenue:**
  ```excel
  =F2*G2
