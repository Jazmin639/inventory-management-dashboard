# Inventory Optimization & Management Dashboard

## 📊 Dashboard Overview
This interactive Power BI dashboard was developed to monitor and optimize stock levels across the supply chain. The panel provides comprehensive control over product flows, allowing users to identify reconciliation variances and maintain optimal storage baselines.

<img src="image_8d4334.png" alt="Inventory Dashboard Overview" width="100%">


## 🎯 KPIs & Control Metrics Analyzed
The analytical framework of this dashboard evaluates:
*   **Inventory Flow Pipeline**: Sequential tracking of starting inventory (35K), incoming purchases (Incoming), outbound sales (Outbound), and final available stock (24K On hand).
*   **Inventory Reconciliation**: Analytical detection of discrepancies or shrinkage between physical and theoretical stock (tracking a variance of -284 units for the close of April 2026).
*   **Optimal Stock Framework**: Implementation of replenishment logic based on **Min Stock** (15.71K), **Max Stock** (31.42K), and **Safety Stock** (15.00) to prevent stockouts or excessive holding costs.
*   **Composition & Valuation**: Detailed breakdown of *Closing stock* value and *Inventory composition* across critical product categories (Portfolio, Celular, Tablet, Impresora), highlighting that "Impresora" products represent the largest volume of tied-up financial capital.

## 🛠️ Technical Competencies Demonstrated
*   **Data Modeling & DAX**: Development of dynamic measures for automatic theoretical inventory calculations, stock alerts, and Days of Supply (DOS).
*   **UI/UX Dashboard Design**: Structuring clean visual interfaces, smooth slicing by product type, and clear prioritization of primary logistics alerts.

## 📂 Repository Structure
*   `Inventory_2026.pbix`: Original Power BI workbook.
*   `Supply_Chain_Management_Dataset_200_Rows.csv`: Master data used for the stock analysis.
