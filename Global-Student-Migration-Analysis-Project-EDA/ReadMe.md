### Global-Student-Migration-Analysis-Project-EDA

# Global Student Migration Analysis Project — EDA

**One‑notebook exploratory data analysis (EDA)** on global student migration patterns.
The notebook walks through data loading, cleaning, feature engineering, and visual insights to help students, universities, and policymakers understand flows, outcomes, and trends.

---

## 📁 Project Contents

* `Global_Student_Migration_Analysis_Project_(EDA).ipynb` — primary analysis notebook.
* `data/` — place the raw CSV here (e.g., `data/global_student_migration.csv`).
* `figures/` — (optional) saved charts/exports.
* `requirements.txt` — (optional) minimal Python libraries to run the notebook.


---

## 🧰 Tech Stack

This project uses standard data‑science libraries:

* Python 3.10+
* NumPy, Pandas
* Matplotlib, Seaborn
* Jupyter / VS Code (or Google Colab)

> Detected in the notebook: `pandas, numpy, matplotlib, seaborn`


---

## 📦 Data

* Expected CSV (example path): `data/global_student_migration.csv`
* Put your dataset under `data/` and adjust the path in the notebook cell that loads the CSV, e.g.:

```python
import pandas as pd
df = pd.read_csv("data/global_student_migration.csv")
df.head()
```

### Expected/Referenced Columns

Below are representative columns often seen in this analysis (yours may differ slightly):

```
origin_country, destination_country, destination_city, destination_region,
year_of_enrollment, graduation_year, student_count, test_score, gpa_or_score,
starting_salary_usd, visa_status, placement_status, enrollment_reason
```

---

## 🚀 How to Run

### Option A — Locally

1. Clone this folder or copy the notebook into your repo.
2. Create and activate a virtual environment (see above).
3. `pip install` the libraries.
4. Put the CSV under `data/` and update the load path in the notebook.
5. Launch Jupyter:

   ```bash
   jupyter notebook
   ```

   Open `Global_Student_Migration_Analysis_Project_(EDA).ipynb` and run cells top‑to‑bottom.

### Option B — Google Colab

1. Upload the notebook to Colab.
2. Upload the CSV to Colab (or mount Google Drive) and update the file path.
3. Run cells in order.

---

## 📊 What You’ll See

The notebook is structured into clear analysis sections such as:

* Dataset overview
* Data quality checks (types, missingness)
* Geographic patterns
* Enrollment & Graduation trends
* Outcome & placement analysis
* Score/Salary distributions

Typical visuals include:

* Data type distributions
* Missing value heatmap & percentages
* Geographic comparisons by origin/destination
* Trend lines for enrollment and graduation years
* Placement outcomes and starting salary distributions

---

## 🧪 Reproducibility Checklist

* ✅ Set a fixed CSV path under `data/`
* ✅ Execute the notebook top‑to‑bottom without manual edits mid‑way
* ✅ Save any figures to `figures/` (optional code provided in the notebook cells)
* ✅ Commit a small sample CSV (anonymized) if you want others to run the notebook

---


## 📚 Dataset Source & Citation

Please fill in the blanks below with your specific Kaggle dataset details:

* **Dataset:** <Dataset T> by \<Eren Ata> — Kaggle, <Year>.
  **License:** <License name>
  **URL:** <(https://www.kaggle.com/code/erenata/global-student-migration-eda))

**Suggested short citation (APA‑style):**
\<Eren Ata>. (<2025>). *<Dataset global-student-migration>* \[Data set]. Kaggle. <URL>

---

## 🙌 Acknowledgements

Thanks to the AiSaturday Lagos ML Flipped Cohort community for inspiration and weekly study prompts.
