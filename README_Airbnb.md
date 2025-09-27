# 🏠 Airbnb Data Analysis Project  

## 📌 Introduction  
This project analyzes Airbnb open dataset to understand **pricing trends, room type distribution, neighborhood dynamics, and customer reviews**.  
The goal is to generate insights that help both **hosts** (pricing & listing strategy) and **Airbnb** (market demand patterns).  

---

## 📝 Problem Statement  
With millions of listings across cities, Airbnb needs to analyze data to:  
- Identify pricing dynamics across neighborhoods.  
- Understand room type preferences.  
- Track review activity trends.  
- Provide insights to improve business strategy for hosts & Airbnb.  

---

## ❓ Key Questions  
1. What is the distribution of listing prices?  
2. Which room types are most common?  
3. How are listings distributed across neighborhoods?  
4. How does price vary by room type?  
5. How have reviews changed over time?  

---

## 🗂️ Dataset  
- **File:** `Airbnb_Data.csv`  
- **Rows:** ~102k  
- **Columns:** 26 (id, host details, neighborhood, room type, price, reviews, availability, etc.)  

---

## 🛠️ Tools & Libraries  
- Python (Pandas, NumPy)  
- Visualization (Matplotlib, Seaborn)  
- Jupyter Notebook  
- Tableau / Power BI (optional for dashboards)  

---

## 📈 Analysis Performed  
1. **Data Cleaning**  
   - Handled missing values (`reviews per month`, `last review`).  
   - Removed duplicates & unnecessary columns.  
   - Converted price & service fee to numeric.  

2. **Exploratory Data Analysis (EDA)**  
   - Distribution of listing prices.  
   - Room type analysis.  
   - Neighborhood-wise listing count.  
   - Price vs. Room Type (box plot).  
   - Reviews trend over time.  

---

## 📊 Key Visualizations  
- Distribution of Listing Prices (Histogram + KDE)  
- Room Type Distribution (Countplot)  
- Neighborhood Group Analysis (Bar plot)  
- Price vs. Room Type (Boxplot)  
- Reviews Over Time (Line Chart)  

---

## ✅ Key Insights  
- **Manhattan & Brooklyn dominate Airbnb listings**, showing they are prime locations.  
- Most listings are for **Entire home/apt** and **Private rooms**.  
- Prices vary widely, with **Shared rooms being cheapest** and **Entire homes/Hotel rooms being most expensive**.  
- Reviews show clear **spikes and drops over time**, influenced by market trends and policies.  

---

## 🚀 Future Work  
- Build **predictive pricing models** using ML.  
- Add **geospatial analysis** (map visualizations).  
- Create **interactive dashboards** in Tableau/Power BI.  

---

## ⚙️ How to Run  
```bash
pip install -r requirements.txt
jupyter notebook Airbnb_Data_Analysis.ipynb
```
