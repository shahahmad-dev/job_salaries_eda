# 📊 Data Science Salaries EDA

This project performs **Exploratory Data Analysis (EDA)** on the `ds_salaries.csv` dataset, which contains job salaries in the field of data science. The analysis explores salary trends, job roles, company sizes, and remote work ratios with the help of **Python** and popular data visualization libraries.

---

## 🚀 Features & Steps

### **1. Importing Libraries**

* **pandas** → data manipulation
* **numpy** → numerical operations
* **matplotlib / seaborn** → static plots
* **plotly express** → interactive visualizations

### **2. Data Loading**

```python
df = pd.read_csv('ds_salaries.csv')
```

### **3. Data Exploration**

* `.head()`, `.info()`, `.describe()` for dataset overview
* Checking for **missing values**
* Inspecting columns like `work_year`, `job_title`, `company_size`, etc.

### **4. Data Cleaning**

* Handled missing values check
* Renamed / validated columns
* Distribution check of categorical features

---

## 📊 Visualizations

### 1️⃣ **Distribution of Work Years**

* Histogram of `work_year`

### 2️⃣ **Maximum Salary by Job Title (Top 10)**

* Horizontal bar chart showing top-paying job roles

### 3️⃣ **Average Remote Ratio by Company Size**

* Bar chart comparing remote work flexibility by company size

### 4️⃣ **Trend of Top 5 Job Titles Over Work Years**

* Line chart showing the yearly trend of the most common job titles

---

## 🛠️ Technologies Used

* **Python 3**
* **pandas**
* **numpy**
* **matplotlib**
* **seaborn**
* **plotly express**

---

## 📌 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/shahahmad-dev/job_salaries_eda.git
   cd job_salaries_eda
   ```
2. Install requirements (if needed):

   ```bash
   pip install pandas numpy matplotlib seaborn plotly
   ```
3. Run the Jupyter Notebook:

   ```bash
   jupyter notebook job_salaries.ipynb
   ```

---

## 📷 Sample Visualizations

* Distribution of Work Years
* Maximum Salary by Job Title (Top 10)
* Average Remote Ratio by Company Size
* Trend of Top 5 Job Titles

---

## 🎯 Conclusion

This analysis provides insights into:

* Salary variation across job roles
* Remote work adoption by company size
* Popularity trends of job titles over years

It helps **data scientists and analysts** understand salary distributions and job market patterns in the data industry.

