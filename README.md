# ❤️ Heart Disease Risk Analysis Dashboard

## 📌 Overview
Heart disease is a leading global health concern, and early detection is crucial for improving patient outcomes. This **interactive Tableau dashboard** provides a **comprehensive analysis of heart disease risk** by visualizing key **demographic, symptom, and health indicators**.

The dashboard enables users to **filter data dynamically** based on **age, gender, and symptoms** to gain valuable insights into **high-risk patient groups**. Additionally, it allows for an **in-depth comparison of symptom prevalence, age-related risk factors, and gender-based variations**.

The dataset was **pre-processed in Python** before being imported into Tableau, where **calculated fields and interactive elements** were added to enhance the analysis.

🔗 **Live Dashboard on Tableau Public**:  
[Heart Disease Risk Analysis](https://public.tableau.com/app/profile/sumit.dighe8857/viz/HeartDiseaseRisk_17419185924340/HeartDiseaseRisk)

---

## 🎯 Objective
This dashboard serves as a **decision-support tool** for healthcare professionals, researchers, and policymakers. The key goals include:
- Identifying **high-risk individuals** based on demographic and symptom data.
- Understanding the **distribution of heart disease across age and gender**.
- Analyzing **which symptoms are most commonly linked to high-risk patients**.
- Enabling **interactive data exploration** for better insights and data-driven conclusions.

---

## 📊 Key Features

### 📈 **Advanced Data Visualizations**
- **🟠 Dual-Axis Line Chart:** Compares **Total Patients vs High-Risk Patients** across different age groups, revealing **which age brackets have higher risk exposure**.
- **📊 Stacked Bar Chart:** Displays the **proportion of high-risk individuals within each age group**, helping to identify **risk concentration trends**.
- **🔥 Symptoms Heatmap:** A **color-coded matrix** showing the **prevalence of symptoms across genders and risk levels**, making it easy to spot **common indicators**.
- **🥧 Gender-Based Pie Chart:** Provides a **quick comparison** of heart disease risk between **male and female patients**.
- **📌 KPI Metrics Panel:** Showcases key **summary statistics** including **Total Patients, High-Risk Percentage, and Average Age** for a quick overview.

---

## 🎛 **Interactivity & Filters**
This dashboard is **fully interactive**, allowing users to explore data dynamically through:
- **🔹 Gender Filter:** Compare **heart disease risk trends for males vs. females**.
- **🔹 Symptoms Filter:** Select specific symptoms to **analyze their occurrence in high-risk patients**.
- **🔹 Age Group Filter:** Examine **risk variations across different age brackets**.
- **🔹 Click-to-Filter:** Clicking on any chart **dynamically updates the entire dashboard**.

🔍 **How These Filters Enhance Analysis:**
- Selecting **"Chest Pain"** in the **Symptoms Filter** shows **only patients experiencing chest pain**, allowing users to see if it correlates with **high risk**.
- Filtering by **"High-Risk Patients"** allows for a **focused analysis** of severe cases.
- Choosing **"Female"** in the **Gender Filter** helps compare **symptom differences between men and women**.

---

## 📊 **Dashboard Walkthrough**
This dashboard consists of **multiple interactive visualizations**, each designed to provide a unique insight into **heart disease risk factors**.

![Dashboard Screenshot](Screenshot%202025-03-15%20120242.png)

### **1️⃣ KPI Overview Panel**
Located at the **top left**, this panel provides **quick-glance metrics**:
- **Total Patients:** The overall number of individuals in the dataset.
- **High-Risk Percentage:** The proportion of patients classified as **high risk**.
- **Average Age:** The mean age of patients, providing a **demographic overview**.

> **🔎 How it helps:** Gives an **instant summary** of the dataset and dynamically updates based on selected filters.

---

### **2️⃣ Dual-Axis Line Chart (Age vs. Risk)**
- **Tracks trends in patient count vs. high-risk patients** across **different age groups**.
- The **red line represents high-risk patients**, while the **blue line represents total patients**.

> **🔎 Key Insight:** If the **high-risk line rises steeply**, it means that **certain age groups have a disproportionately higher risk**.

---

### **3️⃣ Stacked Bar Chart (Age Group Distribution)**
- Displays the **total patient count by age group** while highlighting the **high-risk proportion in each bracket**.
- Uses **color differentiation** for clarity.

> **🔎 Key Insight:** Quickly identifies which **age groups have the highest concentration of heart disease risk**.

---

### **4️⃣ Symptoms Heatmap**
- A **color-coded table** displaying **which symptoms are most prevalent** in **high-risk patients**.
- Categorized by **Gender and Heart Risk Level**.

> **🔎 Key Insight:** If a symptom appears frequently in **high-risk males vs. females**, it suggests **potential gender-based differences in heart disease symptoms**.

---

### **5️⃣ Gender-Based Pie Chart**
- Shows the **gender distribution of high-risk patients**.
- Colors differentiate **male vs female proportions**.

> **🔎 Key Insight:** If one gender is disproportionately affected, it indicates a **higher susceptibility to heart disease**.

---

## 📂 Project Workflow

### **1️⃣ Data Processing & Preparation (Python)**
Before importing the data into Tableau, preprocessing was done in **Python** to ensure **data quality and accuracy**. This included:
- **Data Cleaning:** Removing missing values and duplicates.
- **Feature Engineering:** Creating **calculated columns** such as:
  - **Risk Level Calculation** (High vs Low Risk)
  - **Age Group Binning** (`<30`, `30-40`, etc.)
- **Aggregation:** Summarizing patient counts by **age group, gender, and symptoms**.

### **2️⃣ Tableau Data Import & Calculated Fields**
Inside **Tableau**, additional **calculated fields** were created:
- **Dynamic KPIs** → Using **SUM() and AVG()** for patient count and average age.
- **Custom Color Encoding** → Enhancing **clarity in heatmaps and bar charts**.
- **Percentage Breakdown** → Used in **stacked bar charts**.

### **3️⃣ Dashboard Design & Layout**
- **🖼️ Custom Background Image** → Used a **high-quality heart image** for aesthetics.
- **📌 Floating Containers** → Optimized layout and positioning.
- **🎨 Color Themes** → Chose **medical-themed colors (red, blue, white)**.

---

## 🛠️ Technologies Used

| Technology  | Purpose |
|-------------|---------|
| **Python (Pandas, NumPy)** | Data preprocessing and feature engineering |
| **Tableau** | Data visualization and dashboard development |
| **Tableau Public** | Hosting and sharing the interactive dashboard |
| **Calculated Fields** | Dynamic metric computation in Tableau |
| **Floating Layouts** | Improved dashboard arrangement |
| **Interactive Filters** | Enhanced user experience |

---

## 📥 How to Use
1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/heart-disease-risk-dashboard.git
