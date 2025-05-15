# Comparative Need State Analysis for Ride-Hailing Platforms: A Case Study on PickMe and Uber

## 🚖 Project Overview
This project presents a **Comparative Need State Analysis** of **ride-hailing customers** in **Colombo, Sri Lanka**, focusing on the two leading platforms: **PickMe** and **Uber**.

The aim is to **segment customers based on behavioural and demographic factors** and provide **data-driven recommendations** for:
- Targeted marketing strategies
- Improved customer engagement
- Increased retention and loyalty

This study was conducted as part of my **Final Year Project (FYP)** for the **BSc (Hons) in Data Science and Analytics** degree awarded by the **University of Westminster** in collaboration with **IIT Sri Lanka**.

---

## 🎯 Objectives
- Identify and compare **customer need states** for PickMe and Uber.
- Collect and preprocess survey responses from **Colombo-based users**.
- Apply **K-Modes clustering** to categorise users based on categorical attributes.
- Evaluate and validate clustering outcomes using appropriate metrics.
- Develop an **interactive Power BI dashboard** to visualize insights.
- Provide **business recommendations** tailored to each cluster and ride-hailing platform.

---

## 📊 Dataset Overview
- Data was collected through two separate surveys in **English and Sinhala**.
- Focused only on respondents from **Colombo** to ensure regional consistency.

**Data Preprocessing Included:**
- Removal of **duplicates** and **inconsistent responses**
- **Manual translation** of Sinhala inputs
- Handling **missing values** via domain-specific imputation
- Label encoding for clustering input

**Final Dataset Summary:**
- ✅ 384 valid responses
- ✅ Fully **categorical** data
- ✅ Cleaned and encoded for clustering analysis

---

## 🤖 Clustering Methodology

### K-Modes Clustering
The clustering model used was **K-Modes**, ideal for categorical data. After testing several cluster sizes using the following evaluation methods:

- 📉 **Elbow Method**
- 📈 **Silhouette Score**
- 🧮 **Dunn Index**
- 📊 **Calinski-Harabasz Index**

The optimal number of clusters was determined to be **4**, each representing a distinct group of ride-hailing users.

---

## 📌 Key Outputs
- **Cluster Profiles**: Clear segmentation with labeled cluster personas.
- **Interactive Dashboard**: Built in **Power BI**, highlighting behavioral patterns and preferences.
- **Business Recommendations**: Tailored marketing and service strategies for PickMe and Uber.

---

## 🧪 Tools & Technologies
- **Python (Jupyter Notebook)**
- **Power BI**
- **pandas, numpy, seaborn, matplotlib**
- **kmodes** for clustering
- **scikit-learn** for evaluation metrics

---

## 📎 Appendix Links
📊 [Interactive Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMDljYzdhMWUtZDVjNS00ODVhLTlhOWYtOGJlZjliMjFkMjdlIiwidCI6IjlhNWI1NjkxLWE0NTEtNDllNy05M2RlLTljNjFjYjA0MzI4YiIsImMiOjEwfQ%3D%3D&pageName=8ab0c408e8729a0e6140)

---

## 📬 Contact
Dinith Mario Perera
- **Email:** dinithmperera@gmail.com
- **LinkedIn:** linkedin.com/in/dinithmario
