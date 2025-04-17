## 📘 Kidney Disease Analytics Dashboard

### 📂 Dataset Overview

This dataset contains health-related information about patients and is focused on identifying and analyzing risk levels of **Chronic Kidney Disease (CKD)**. It includes a wide range of clinical, demographic, and lifestyle attributes.

**Total Records:** ~21,000  
**Key Attributes:**
- Age, Gender
- Blood Urea, Serum Creatinine
- eGFR (Estimated Glomerular Filtration Rate)
- Hemoglobin, BMI
- Hypertension & Diabetes status
- Smoking, Physical Activity
- Target Risk Label (CKD / No CKD)

---

### 📊 Power BI Dashboard Description

This Power BI dashboard is built to **analyze patterns in kidney health** and identify potential risk indicators of CKD. It includes filters, KPIs, charts, and summaries to support diagnosis and monitoring.

#### 🔍 Filters (Slicers)
- **Target** (CKD, No CKD)
- **Smoking Status**
- **Age**
- **Duration of Hypertension** (Years)
- **Duration of Diabetes Mellitus** (Years)

#### 🧮 Key Metrics (Cards)
- **Total Patients:** 21K
- **PTH Level:** 800K+
- **Diabetes %:** 50%
- **Average BMI:** 27.54
- **At Risk %:** 20%
- **Hemoglobin Level:** 245K+

#### 📈 Visuals & Charts

1. **Pie Chart:**
   - Proportion of patients with Diabetes and those at Risk (CKD)

2. **Bar Chart:**
   - **Sum of Serum Creatinine** grouped by **BMI**

3. **Line/Bar Combo Chart:**
   - **Sum of Hemoglobin level** and **Albumin in urine** plotted against **eGFR**

4. **Summary Table:**
   - Aggregated values of **Serum Creatinine** and **Hemoglobin** grouped by eGFR

---

### 💡 Insights

- **Higher BMI** is correlated with elevated **Serum Creatinine**.
- Patients with lower **eGFR** tend to show lower **Hemoglobin** and higher **Albumin in urine**—a sign of impaired kidney function.
- ~50% of patients are diabetic, and ~20% are classified at risk for CKD.
- Most CKD patients show abnormal levels of **blood urea**, **creatinine**, and reduced **hemoglobin**.

---

### 🛠️ How to Use

1. **Open Power BI Desktop**
2. Import the `kidney_disease_dataset.csv`
3. Load the prebuilt visuals or recreate them using fields described above
4. Use slicers to filter based on demographics or disease duration
5. Interpret health patterns and risk factors interactively

---

### 📌 Future Additions (Optional)
- Add machine learning prediction (CKD risk classifier)
- Drill-down by gender or region (if data is available)
- Time-series analysis if date fields are added

---

