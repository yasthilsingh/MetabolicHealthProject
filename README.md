# Physical Activity & Metabolic Health Analysis

This project explores how weekly physical-activity levels relate to metabolic markers—especially **fasting insulin**—using real NHANES data.  
Our goal is to uncover clear, reproducible links between movement and metabolic health.

> **Market Intelligence Snapshot:**  
> In the U S. alone, **96 million adults are pre-diabetic** .A conservative view of direct medical cost of diabetes averages **\$9.6 k per person each year**.  
> Even a modest **5 % reduction in fasting insulin**—achievable through increased physical activity—could avert **\$8–10 billion** in annual healthcare spending.  
> This project quantifies how weekly movement links to insulin levels, laying the data foundation for preventive digital-health products and policy decisions.
---

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

---

## 📁 Files in This Repo

| Path | Purpose |
|------|---------|
| **`docs/index.html`** | Live HTML walkthrough (served by GitHub Pages) |
| `metabolic_health_analysis_updated.ipynb` | Cleaned notebook with hidden inputs |
| `requirements.txt` | Python dependencies |
| `.gitignore` | Ignore rules |
| `README.md` | Project overview (this file) |

> **Note:** Raw NHANES `.xpt` datasets are not included. See “Reproduce” below.

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
4. Layer in economic datasets to estimate healthcare savings (see Market Analysis👇)

---

### 📊 Market Analysis Layer

* **96 M U.S. adults** are pre-diabetic  → [CDC 2022](https://www.cdc.gov/diabetes/data/statistics-report/index.html)  
* **30 % adoption** of activity nudges in digital-health apps  → JAMA / *NPJ Digital Med*  
* **~5 % insulin reduction** lowers diabetes risk (clinical consensus)  
* **Direct medical cost** of diabetes ≈ \$9.6 k / person / year  → [ADA 2022](https://diabetesjournals.org/care/article/46/4/454/148746)  
* **Cost-savings potential:** 1 M prevented cases → \$8–10 B annually

---

## 🧪 How to Reproduce Locally

```bash
# 1) Clone
git clone https://github.com/yasthilsingh/MetabolicHealthProject.git
cd MetabolicHealthProject

# 2) (Optional) create a virtual env
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# 3) Install deps
pip install -r requirements.txt

---

Made with care to support better data-driven health decisions.
