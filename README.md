# 🌍 Global Terrorism Analysis

## 📌 Project Overview

This project analyzes the **Global Terrorism Dataset (GTD)** to uncover patterns and trends in terrorist incidents worldwide. The dataset includes detailed information such as year, country, region, attack type, target type, weapon type, and casualties.

The objective is to **clean, analyze, and visualize the data** to generate meaningful insights about terrorism trends across time and geography.

---

## 🎯 Objectives

* 📂 Load and inspect the dataset
* 🧹 Handle missing values and remove duplicates
* 🔄 Correct inconsistent or incorrect data types
* ➕ Create new features (e.g., *casualties = nkill + nwound*)
* 📊 Perform exploratory data analysis (EDA)
* 📈 Build visualizations to identify trends
* 💡 Generate actionable insights for stakeholders

---

## 🛠️ Tools & Technologies

* 🐍 Python
* 🐼 Pandas
* 🔢 NumPy
* 📉 Matplotlib
* 🎨 Seaborn

---

## 🧼 Data Cleaning

The dataset was preprocessed using the following steps:

* 🗑️ Removed duplicate records
* ⚠️ Handled missing values in key columns
* 🔧 Converted data types to appropriate formats
* ➕ Created a **`casualties`** column (`nkill + nwound`)
* 📅 Extracted additional features such as:

  * Year
  * Month
  * Decade

---

## 📌 Key Features Used

* 📅 `iyear`, `imonth`, `iday`
* 🌍 `country_txt`, `region_txt`, `city`
* 💣 `attacktype1_txt`
* 🎯 `targtype1_txt`
* 👥 `gname`
* 🔫 `weaptype1_txt`
* ☠️ `nkill`, 🤕 `nwound`
* ✅ `success`, ⚔️ `suicide`
* 📊 `casualties` (engineered feature)

---

## 📊 Exploratory Data Analysis

The analysis focuses on:

* 📈 Year-wise trend of terrorist attacks
* 🌍 Countries with the highest number of incidents
* 💣 Most frequent attack types
* 🎯 Most targeted sectors
* ☠️ Distribution of casualties
* 📦 Detection of outliers
* 🔗 Correlation between numerical variables

---

## 📉 Visualizations

* 📈 Line chart: Attacks per year
* 📊 Bar chart: Top affected countries
* 💣 Bar chart: Attack type frequency
* 🥧 Pie chart: Target distribution
* 📉 Histogram: Casualty distribution
* 📦 Box plot: Outlier detection
* 🔥 Heatmap: Correlation matrix

---

## 💡 Key Insights

* 🌍 Terrorism is unevenly distributed across regions and time
* 📍 A small number of countries account for a large share of incidents
* 💣 Bombings/explosives are the most common attack type
* 🎯 Civilians and public infrastructure are frequent targets
* 📊 Casualties are highly skewed—few events cause extremely high impact
* 🧠 Insights can support risk assessment and strategic planning

---

## 👥 Stakeholder Relevance

This analysis can benefit:

* 🏛️ Government agencies for policy and counter-terrorism planning
* 🛡️ Security organizations for threat monitoring
* 🎓 Researchers studying global conflict patterns
* 📜 Policy makers for resource allocation
* 🌐 International organizations assessing regional risks

---

## 📁 Project Structure

```
project-folder/
│── Global_Terrorism_Data.csv
│── notebook.ipynb
│── README.md
└── images/
```

---

## 🚀 Getting Started

1. 📥 Clone the repository

   ```bash
   git clone https://github.com/your-username/global-terrorism-analysis.git
   ```
2. 💻 Open `notebook.ipynb` in Jupyter Notebook or Google Colab
3. 📦 Install required libraries (if needed)
4. ▶️ Run the notebook cells step by step

---

## 🏁 Conclusion

This project demonstrates how **data cleaning, exploratory analysis, and visualization** can uncover meaningful patterns in complex datasets. The findings provide valuable insights that can aid decision-making in security and policy domains.

---

## ✍️ Author

**Annanya Naudiyal**
