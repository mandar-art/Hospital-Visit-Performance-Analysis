# 📌 Hospital Visit Performance Analysis 🏥

**Exploratory Data Analysis | Python | Healthcare Analytics**

This project focuses on analyzing hospital visit performance to uncover trends in patient demographics, seasonal disease patterns, revenue-driving departments, and operational improvement areas. The dataset contains patient visit records including symptoms, diagnoses, doctors, and financial details.

---

## 📊 Project Overview

Hospitals often struggle with:

* Managing patient load during peak seasons
* Ensuring efficient resource allocation
* Understanding revenue drivers
* Tracking clinical performance trends

This project answers key questions like:

* Which departments and doctors drive most revenue?
* Which symptoms most frequently lead to which diagnoses?
* What months and seasons observe the highest patient flow?
* How do age and demographics impact healthcare utilization?

---

## 🧩 Dataset Details

| Feature Category    | Example Columns               |
| ------------------- | ----------------------------- |
| Patient Information | PatientID, Age, Gender, City  |
| Visit Information   | VisitID, VisitDate, Symptoms  |
| Clinical Data       | Department, Doctor, Diagnosis |
| Financial Data      | TreatmentCost, PaymentMethod  |

🗂️ Rows: Patient visit records
📌 Time Coverage: Multi-year quarterly trends

---

## 🛠️ Tools & Technologies Used

| Tool                | Purpose                           |
| ------------------- | --------------------------------- |
| Python              | Data analysis & visualization     |
| Pandas, NumPy       | Data cleaning & transformation    |
| Matplotlib, Seaborn | Trend plots & visual storytelling |
| Jupyter Notebook    | Analysis workflow                 |

---

## 🧹 Data Preprocessing

✔ Converted date column into datetime format
✔ Extracted new features → Year, Month, Quarter, Day
✔ Categorized Age into: *Child · Adult · Middle-Aged · Senior*
✔ Cleaned categorical inconsistencies
✔ Removed duplicate entries

---

## 🔍 Key Insights

### 👥 Patient Demographics

* Majority visits come from **Middle-Aged & Senior** groups
* Equal gender distribution indicates **no gender-based bias**

### 📅 Temporal Trends

* Strong seasonal spikes in **Quarter 3** (flu & viral infections)
* Weekend visits increase — emergency/injury cases

### 🧪 Symptom → Diagnosis Mapping (Heatmap)

| Symptom  | Most Likely Diagnosis |
| -------- | --------------------- |
| Fever    | Flu                   |
| Cold     | Viral Infection       |
| Injury   | Sprain / Fracture     |
| Headache | Migraine              |

✔ Valuable for faster triage & staffing needs

### 🏥 Department Performance

* **Orthopedics** is the top revenue-generating department
* **General Medicine** handles highest daily patient volume
* **Neurology cases** show higher treatment costs

### 🧑‍⚕️ Doctor Performance

* Top doctors by *visits* vs *revenue* differ — specialty matters
* Useful for resource and schedule planning

### 💰 Cost Analysis

* Positive correlation between **age** and **treatment cost**
  → Seniors require more intensive care

---

## 💡 Business Recommendations

| Insight                          | Recommendation                                          |
| -------------------------------- | ------------------------------------------------------- |
| Seasonal viral peaks             | Increase temporary staff during monsoon/winter          |
| Orthopedic overload              | Add support staff on weekends & sports seasons          |
| Chronic disease in elders        | Launch senior health programs                           |
| Pediatric & Gynecology stability | Improve service quality for better patient satisfaction |

👉 Drives operational efficiency & revenue growth

---

## 📂 Project Structure

```
Hospital-Visit-Performance/
│
├── data/
│── Hospital_Visit.csv (raw data)
│
├── notebooks/
│── Hospital_Visit.ipynb (full EDA)
│
├── images/
│── plots & charts used in report
│
└── README.md  <- You are here!
```

---

## 📌 Future Work

🚀 Enhance analysis with:

* Machine Learning model for **diagnosis prediction**
* No-show analysis for patient follow-up optimization
* Patient segmentation using clustering
* Real-time dashboard for hospital admin

---

## 🧑‍💻 Author

**Mandar Manjare**
Data Analyst | Python | SQL | Power BI
🔗 *Open to collaboration & feedback!*
