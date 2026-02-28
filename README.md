# Mini Project – Week 6  
## Exploratory Data Analysis (EDA)

### 📌 Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) on a dataset to understand its structure, distributions, group differences, and relationships between variables.

The goal is to extract meaningful insights that help guide future modeling decisions.

---

### 📂 Dataset
The dataset contains the following features:

- Age
- Income
- Spend
- Segment (target variable)

---

### 🔍 EDA Steps

1. Initial Data Inspection  
   - Checked dataset shape  
   - Verified data types  
   - Checked missing values  

2. Univariate Analysis  
   - Histograms  
   - KDE plots  
   - Boxplots for numeric features  

3. Group Analysis  
   - Compared values by Segment  
   - Used groupby summary (mean, median, std, count)  

4. Correlation Analysis  
   - Heatmap to understand relationships between features  

---

### 📊 Key Insights

- Age distribution appears balanced.  
- Income shows slight right skew.  
- Segment C has higher age, income, and spend compared to others.  
- Income and spend increase with age.  
- Features are strongly related to each other.

---

### 🚀 Recommended Next Steps

- No strong outliers detected.  
- Income may require scaling later.  
- Segment C may need separate modeling.  
- Highly correlated features should be checked for redundancy.

---

### 🛠️ Tools Used

- Python  
- Pandas  
- Seaborn  
- Matplotlib  

---

### 📈 Outcome

The EDA provided a clear understanding of:

- Data distribution  
- Group behavior  
- Feature relationships  

This helps guide preprocessing and future model building.

---
