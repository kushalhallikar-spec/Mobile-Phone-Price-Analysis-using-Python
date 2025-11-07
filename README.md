# 📱 Mobile Phone Price Analysis using Python

This project explores a **Mobile Phone Price dataset** to uncover relationships between smartphone specifications and their price ranges.  
The goal is to perform **Exploratory Data Analysis (EDA)** to identify which features — like RAM, battery power, camera quality, and storage — most influence the phone’s price category.

---

## 📂 Dataset Overview
The dataset includes information about multiple smartphone specifications such as:
- Battery power  
- RAM  
- Internal memory  
- Primary and secondary camera megapixels  
- Screen dimensions and pixel density  
- 4G/3G availability  
- Price range (target variable: 0–3, representing low to high)  

**Source:** Kaggle — *Mobile Price Classification Dataset*

---

## 🧰 Tools & Libraries Used
- **Python**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook / Google Colab**

---

## 🔍 Exploratory Data Analysis Steps
1. **Data Cleaning**
   - Checked for null values and duplicates  
   - Verified data types and consistency  

2. **Univariate Analysis**
   - Distribution of features like RAM, battery power, and camera quality  
   - Price range frequency  

3. **Bivariate Analysis**
   - Relationship between price range and features (RAM, battery, etc.)  
   - Correlation heatmap for feature importance  

4. **Visualization**
   - Histograms, boxplots, and pairplots to visualize trends  
   - Heatmap to identify highly correlated attributes  

---

## 📊 Key Insights
- **RAM** and **battery power** have the **strongest influence** on mobile price range.  
- Phones with **4G connectivity** and higher **pixel resolution** are generally priced higher.  
- The dataset shows a clear linear trend between **RAM** and **price range**.  
- No significant correlation between features like **talk time** and price.  

---

## 💡 Conclusion
This analysis provides a foundation for understanding how hardware specifications affect phone prices.  
It can serve as a base for building a **Machine Learning model** to predict the price range of new phones.

---

