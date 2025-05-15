# Physical Activity & Metabolic Health Analysis

This project explores the relationship between weekly physical activity levels and metabolic health indicators—specifically fasting insulin—using real NHANES data.  
The goal is to uncover how movement patterns relate to biomarkers of health, with a focus on clarity and reproducibility.

## 📊 What This Project Does

- Converts raw activity survey data into total weekly minutes of moderate and vigorous activity  
- Cleans and standardizes biomarker variables (e.g., fasting glucose, insulin, HDL)  
- Detects and manages outliers using percentile‑based capping  
- Visualizes the relationship between physical activity and insulin sensitivity  
- Highlights differences in metabolic markers between active and less‑active individuals  

## 🧠 Why It Matters

Understanding how movement translates to measurable health outcomes is key for building interventions, platforms, and recommendations in the health and wellness space. This analysis helps identify:

- How much movement is associated with improved fasting insulin  
- How common physical inactivity is in population samples  
- The strength of the relationship between behavior and biomarker  

## 🔍 Key Visual Output

A custom Matplotlib chart shows:

- Activity (capped at the 97th percentile) on the x‑axis  
- Fasting insulin on the y‑axis  
- Highlighted zones for meeting or missing the 150 min/week threshold  
- Difference in insulin levels between groups  

## 📁 Files in This Repo

- `notebook.ipynb`  
  Full analysis, cleaned and documented  
- `.gitignore`  
  Ensures raw data files are not tracked  
- `README.md`  
  You’re reading it!

> **Note:** Raw NHANES `.xpt` files are not included. Instructions to download them can be added if needed.

## 🛠 Tools Used

- Python 3  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Jupyter Notebook  
- NHANES public health dataset  

## 🧭 Next Steps

- Scale to other health metrics (cholesterol, A1c)  
- Incorporate demographic segmentation  
- Deploy as part of a digital health insights dashboard  
- Layer economic datasets to measure potential investment opportunities (see Market Analysis below)  

---

### 📊 Market Analysis Layer

- **96 million U.S. adults** are prediabetic  
  → Source: [CDC 2022 National Diabetes Statistics Report](https://www.cdc.gov/diabetes/data/statistics-report/index.html)

- **30% adoption** of activity nudges (e.g., walking prompts, step goals)  
  → From digital health app engagement studies (JAMA, Nature Digital Medicine)

- **~5% reduction** in fasting insulin is associated with reduced diabetes risk  
  → Clinical studies suggest even modest increases in physical activity improve insulin sensitivity

- **Assumption:** We reach 1 million preventable cases long term  

- **Annual direct medical cost of diabetes:** ~$9,600 per person  
  → Source: [ADA, 2022 Cost of Diabetes Report](https://diabetesjournals.org/care/article/46/4/454/148746)

- **Estimated cost savings:**  
  - 1 million cases × \$8,000–\$10,000 per person = \$8–\$10 billion/year  
  → Source: [ADA, 2022 Cost of Diabetes Report](https://diabetesjournals.org/care/article/46/4/454/148746)

---

## 🧪 How to Reproduce This Project

1. **Clone this repository:**  
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name


2. **(Optional) Create a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Download NHANES `.xpt` files**  
   You can access the NHANES datasets from the [CDC website](https://wwwn.cdc.gov/nchs/nhanes/) and place them into a local `/data` folder inside your project.

5. **Launch the notebook:**
   Open `notebook.ipynb` in Jupyter or PyCharm and run the cells from top to bottom.

---

---

Made with care to support better data-driven health decisions.