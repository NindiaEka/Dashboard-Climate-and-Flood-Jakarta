# 🌦️ Weather Data Analysis & Dashboard – Jakarta

## 📘 Problem Background  
Extreme weather and flooding are major challenges for farmers, especially in Jakarta and surrounding areas.  
Unpredictable floods can damage crops, delay planting seasons, and even lead to crop failure.  

Currently, access to systematic information regarding weather patterns and flood seasons remains limited for farmers.  
By analyzing **five years of weather and flood data**, this project aims to help farmers make better decisions on **planting time, fertilization, and harvesting**, while also serving as a foundation for **flood risk mitigation** in agriculture.

---

## 🎯 Project Output  
This project produces an **interactive dashboard** that visualizes rainfall and flood data to support data-driven agricultural decisions, helping farmers reduce crop failure risks caused by floods.  

🔗 **View the Dashboard here:**  
[Weather & Flood Dashboard – Tableau](https://public.tableau.com/app/profile/nindia.ekasuci.larasati/viz/P0M1_Nindia-Ekasuci/Dashboard1?publish=yes)

---

## 📊 Data Source  
Dataset used: [Climate and Flood Jakarta (Kaggle)](https://www.kaggle.com/datasets/christopherrichardc/climate-and-flood-jakarta/data)

- **Rows:** 6,308  
- **Columns:** 15  
- **Missing Values:** Found in rainfall and sunlight duration columns.  
  These missing values were **imputed using the median** to preserve essential information such as station names.  

---

## 🧠 Methodology  

### 1. **Data Cleaning**
- Handled missing values using **median imputation** for rainfall and sunlight duration.  
- Merged weather and flood datasets into a single analytical dataset.  

### 2. **Descriptive Statistics**
- Calculated **mean, variance, skewness,** and **kurtosis** to understand weather patterns.

### 3. **Data Visualization**
- Created **line charts, bar charts, boxplots,** and **choropleth maps** to explore temporal and spatial trends.

### 4. **Inferential Statistics**
- **ANOVA Test:** To analyze temperature differences across months.  
- **T-Test:** To compare temperature during flood and non-flood periods.  
- **Chi-Square & Cramer’s V:** To identify relationships between regions and flood occurrences.

---

## 🧰 Tech Stack  

| Category | Tools & Libraries |
|-----------|-------------------|
| **Programming** | Python |
| **Data Analysis Libraries** | Pandas, NumPy, Seaborn, Matplotlib |
| **Geospatial Tools** | GeoPandas, Folium, QGIS (for shapefile extraction) |
| **Visualization** | Tableau |
| **IDE/Environment** | Jupyter Notebook |

---

## 📚 References  
- **Dashboard Inspiration:** Various Tableau Public projects on climate data visualization  
- **Data Source:** Kaggle – *Climate and Flood Jakarta*  
- **Final Dashboard:** [View Here](https://public.tableau.com/app/profile/nindia.ekasuci.larasati/viz/P0M1_Nindia-Ekasuci/Dashboard1?publish=yes)

---

## 🌾 Project Impact  
This dashboard provides valuable insights into **Jakarta’s weather and flood dynamics**, supporting:  
- **Farmers** in choosing the right planting and harvesting time.  
- **Decision-makers** in designing better flood mitigation strategies.  
- **Researchers** in understanding long-term weather trends in urban and agricultural contexts.

---

💡 *Created by [Nindia Ekasuci Larasati](https://www.linkedin.com/in/nindia-ekasuci-larasati/)*  
🎓 *Master’s in Geophysical Engineering | Data Science Enthusiast*  
