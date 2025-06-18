# Physical Activity & Metabolic Health Analysis

This project explores how weekly physical-activity levels relate to metabolic markers—especially **fasting insulin**—using real NHANES data.  
Our goal is to uncover clear, reproducible links between movement and metabolic health.

## 🌐 Live Report (Rendered HTML)

A code-free, fully rendered walkthrough is hosted on GitHub Pages:

**https://yasthilsingh.github.io/MetabolicHealthProject/**

Open that URL in any browser to read the narrative, explore the charts, and download assets—no cloning required.

---

## 📊 What This Project Does

* Converts raw NHANES activity surveys into **weekly minutes** of moderate & vigorous exercise  
* Cleans and standardizes biomarker variables (fasting glucose, insulin, HDL, etc.)  
* Detects and caps outliers using percentile thresholds  
* Visualizes the link between activity and insulin sensitivity  
* Compares metabolic markers between active and less-active groups

---

## Data Sources

This project uses data from the **2021 – 2022 cycle** of the  
[National Health and Nutrition Examination Survey (NHANES)](https://www.cdc.gov/nchs/nhanes/index.html).

| File Code | Description                                            | Direct XPT Download |
|-----------|--------------------------------------------------------|---------------------|
| DEMO_L    | Demographics (age, gender, race, income, etc.)        | [Download](https://wwwn.cdc.gov/Nchs/Data/Nhanes/Public/2021/DataFiles/DEMO_L.xpt) |
| PAQ_L     | Physical Activity Questionnaire                       | [Download](https://wwwn.cdc.gov/Nchs/Data/Nhanes/Public/2021/DataFiles/PAQ_L.xpt) |
| GLU_L     | Plasma Fasting Glucose                                | [Download](https://wwwn.cdc.gov/Nchs/Data/Nhanes/Public/2021/DataFiles/GLU_L.xpt) |
| INS_L     | Fasting Insulin                                       | [Download](https://wwwn.cdc.gov/Nchs/Data/Nhanes/Public/2021/DataFiles/INS_L.xpt) |
| GHB_L     | Glycohemoglobin (HbA1c)                               | [Download](https://wwwn.cdc.gov/Nchs/Data/Nhanes/Public/2021/DataFiles/GHB_L.xpt) |
| HDL_L     | HDL Cholesterol                                       | [Download](https://wwwn.cdc.gov/Nchs/Data/Nhanes/Public/2021/DataFiles/HDL_L.xpt) |
| TCHOL_L   | Total Cholesterol                                     | [Download](https://wwwn.cdc.gov/Nchs/Data/Nhanes/Public/2021/DataFiles/TCHOL_L.xpt) |
| HSCRP_L   | High-sensitivity C-Reactive Protein (inflammation)    | [Download](https://wwwn.cdc.gov/Nchs/Data/Nhanes/Public/2021/DataFiles/HSCRP_L.xpt) |
| CBC_L     | Complete Blood Count                                  | [Download](https://wwwn.cdc.gov/Nchs/Data/Nhanes/Public/2021/DataFiles/CBC_L.xpt) |

## 🧠 Why It Matters

* Quantifies *how much* movement improves fasting insulin  
* Highlights prevalence of physical inactivity in population samples  
* Guides evidence-based interventions for digital-health products, insurers, and clinicians  

---

## 🔍 Key Visual Output

A custom four-panel dashboard shows:

* **Scatter & regression** – activity (x) vs. insulin (y)  
* **Box & violin** – activity and insulin distributions split by gender  
* **Jitter** – individual datapoints with goal thresholds highlighted

### 📊 Dashboard Snapshot

This snapshot gives a quick visual overview of the dashboard built for analyzing metabolic health metrics:

![Dashboard Overview](images/dashboard.png)

---


## Repository Structure

```text
MetabolicHealthProject/
├── Datafiles/                             # Raw NHANES XPT files
├── docs/                                  # Rendered HTML walkthrough (index.html)
├── images/                                # Static figures used in notebooks and reports
├── metabolic_health_analysis-updated.ipynb    # Main analysis notebook
├── metabolic_health_analysis_walkthrough.ipynb# Walkthrough notebook
├── requirements.txt                       # Python dependencies
├── README.md                              # Project overview & instructions
├── LICENSE                                # MIT license
└── .gitignore                             # Files and folders to ignore


---

## 🛠 Tools Used

* **Python 3**, Pandas, NumPy  
* Matplotlib, Seaborn  
* Jupyter Notebook / PyCharm  
* Public NHANES dataset  

---

## 🧭 Next Steps

1. Extend to other biomarkers (cholesterol, HbA1c)  
2. Add demographic segmentation (age, ethnicity)  
3. Deploy as an interactive digital-health dashboard  

---

Made with care to support better data-driven health decisions.
