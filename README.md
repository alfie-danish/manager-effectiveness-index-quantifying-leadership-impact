# Manager Effectiveness Index — Data Analysis (Python)

This repository contains the Python analysis used to build the **Manager Effectiveness Index**, a composite score designed to quantify leadership impact objectively across departments, levels, and team sizes.

The notebook demonstrates end-to-end analytical workflow using synthetic HR data, including data cleaning, metric creation, aggregation, clustering, and visualization.

---

## 🔍 Project Summary
The analysis explores patterns in manager effectiveness using:
- Composite scoring based on four effectiveness metrics
- Department-level comparison
- Variation by manager level
- Team-size and span-of-control effects
- Outlier analysis for targeted intervention

The findings were used to power the portfolio project:
**_Manager Effectiveness Index — Quantifying Leadership Impact_**

---

## 🧰 Technologies Used
- Python  
- Pandas  
- NumPy  
- Seaborn  
- Matplotlib  

---

## 📂 Repository Contents
| File | Purpose |
|------|---------|
| `notebook.ipynb` | Full analysis notebook with score calculations and visualizations |

---

## 📄 Notebook Structure
The notebook follows a reproducible and linear analytical workflow:

1. Imports & Configuration  
2. Load Data  
3. Data Cleaning & Preprocessing  
4. Composite Score Calculation  
5. Departmental Analysis  
6. Manager Level Analysis  
7. Team Size & Span of Control  
8. Outlier Investigation  
9. Summary of Analytical Results  

Each section includes explanatory Markdown and labeled visualizations.

---

## 🚀 Running the Notebook
To run the notebook locally:

```bash
pip install -r requirements.txt
```

Required packages:

```
pandas
numpy
matplotlib
seaborn
```

Then open the notebook:

```bash
jupyter notebook notebook.ipynb
```

---

## 🔗 External Links
| Resource | Link |
|---------|------|
| Full Case Study | [Notion](https://www.notion.so/Manager-Effectiveness-Index-Quantifying-Leadership-Impact-2037d818e5c980fcbb13d1ced74915ea?source=copy_link) |
| Portfolio Project Page | [Website](Framer link) |

---

## 📌 Key Analytical Findings
- Sales managers show the highest average effectiveness
- Seniority does **not** predict leadership capability (mid-level ≈ senior)
- Team size has no strong correlation with effectiveness (r ≈ 0.06)
- Outliers exist in every department and level — capability varies, not hierarchy

---

## 👤 Author
**Alfie Danish**  
Python • HR Analytics • Data Visualization
