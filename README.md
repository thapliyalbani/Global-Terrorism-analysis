# Global-Terrorism-analysis

## 📖 Project Overview  
This project explores the **Global Terrorism Dataset (GTD)** to identify patterns and trends in terrorist incidents worldwide. The dataset contains detailed attributes such as year, country, region, attack type, target type, weapon type, and casualties.  

The aim is to **clean, analyze, and visualize** the dataset to uncover meaningful insights about terrorism across time and geography, and to apply machine learning techniques for predictive modeling.  

---

## 🎯 Objectives  
- 📂 Import and examine the dataset  
- 🧹 Manage missing values and eliminate duplicates  
- 🔄 Fix inconsistent or incorrect data types  
- ➕ Engineer new features (e.g., casualties = nkill + nwound)  
- 📊 Conduct exploratory data analysis (EDA)  
- 📈 Build visualizations to highlight trends  
- 💡 Generate actionable insights for stakeholders  
- 🤖 Apply machine learning algorithms for classification and prediction  

---

## 🛠️ Tools & Techniques  
- 🐍 **Python**  
- 🐼 **Pandas** for data manipulation  
- 🔢 **NumPy** for numerical operations  
- 📉 **Matplotlib** & 🎨 **Seaborn** for visualization  
- 🤖 **Scikit‑Learn** for machine learning models  

**Machine Learning Algorithms Applied:**  
- **Logistic Regression** → for binary classification tasks  
- **Decision Trees** → for interpretable classification/regression  
- **Random Forest** → for ensemble learning and improved accuracy  
- **Naive Bayes** → for probabilistic classification (e.g., text/spam filtering)  
- **K‑Nearest Neighbors (KNN)** → for similarity‑based classification/regression  

---

## 🧼 Data Preprocessing  
- 🗑️ Removed duplicate entries  
- ⚠️ Handled missing values in critical columns  
- 🔧 Converted data types to appropriate formats  
- ➕ Created a **casualties** column (`nkill + nwound`)  
- 📅 Extracted additional features such as Year, Month, and Decade  

---

## 📌 Key Features Used  
- 📅 iyear, imonth, iday  
- 🌍 country_txt, region_txt, city  
- 💣 attacktype1_txt  
- 🎯 targtype1_txt  
- 👥 gname  
- 🔫 weaptype1_txt  
- ☠️ nkill, 🤕 nwound  
- ✅ success, ⚔️ suicide  
- 📊 casualties (engineered feature)  

---

## 📊 Exploratory Data Analysis  
Focus areas include:  
- 📈 Year‑wise trend of terrorist attacks  
- 🌍 Countries with the highest incidents  
- 💣 Most frequent attack types  
- 🎯 Most targeted sectors  
- ☠️ Casualty distribution  
- 📦 Outlier detection  
- 🔗 Correlation between numerical variables  

---

## 📉 Visualizations  
- 📈 Line chart: Attacks per year  
- 📊 Bar chart: Top affected countries  
- 💣 Bar chart: Attack type frequency  
- 🥧 Pie chart: Target distribution  
- 📉 Histogram: Casualty distribution  
- 📦 Box plot: Outlier detection  
- 🔥 Heatmap: Correlation matrix  

---

## 💡 Key Insights  
- 🌍 Terrorism is unevenly distributed across regions and time  
- 📍 A few countries account for most incidents  
- 💣 Bombings/explosives dominate attack types  
- 🎯 Civilians and public infrastructure are frequent targets  
- 📊 Casualties are highly skewed — few events cause extreme impact  
- 🧠 Insights support risk assessment and strategic planning  

---

## 👥 Stakeholder Relevance  
This analysis benefits:  
- 🏛️ Government agencies for policy and counter‑terrorism planning  
- 🛡️ Security organizations for monitoring threats  
- 🎓 Researchers studying global conflict patterns  
- 📜 Policy makers for resource allocation  
- 🌐 International organizations assessing regional risks  

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
- 📥 Clone the repository:  
  ```bash
  git clone https://github.com/your-username/global-terrorism-analysis.git
  ```  
- 💻 Open `notebook.ipynb` in Jupyter Notebook or Google Colab  
- 📦 Install required libraries (if needed)  
- ▶️ Run the notebook cells step by step  

---

## 🏁 Conclusion  
This project demonstrates how **data cleaning, exploratory analysis, visualization, and machine learning** can uncover meaningful patterns in complex datasets. The findings provide valuable insights that can aid decision‑making in security, research, and policy domains.  

---

✍️ **Author:** 
Bani Thapliyal 
