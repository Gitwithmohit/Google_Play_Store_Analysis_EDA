# 📊 Google Play Store Apps - Exploratory Data Analysis (EDA)

This project focuses on **analyzing apps listed on the Google Play Store** using Exploratory Data Analysis (EDA).  
The dataset (`googleplaystore_v2.csv`) provides detailed attributes such as app ratings, installs, reviews, categories, content ratings, and pricing.  
The aim was to uncover patterns and trends that explain **user behavior, app distribution, and performance metrics**.

---
![LOGO](google.jpg)

## 📂 Project Files
- **Dataset:** `googleplaystore_v2.csv` (googleplaystore_v2.csv) 
- **Jupyter Notebook:** `Google Playstore-Case Study.ipynb`  
- **Report (PDF):** `Google_Play_Store_Report.pdf`

---

## 🛠 Approach
The analysis was carried out step by step in a structured manner:

1. **Data Cleaning & Preprocessing**
   - Removed junk and duplicate records  
   - Handled missing values  
   - Corrected data types (e.g., numerical conversions)  
   - Detected and removed outliers  

2. **Univariate Analysis**
   - Histogram of ratings → observed skewness towards higher ratings  
   - Bar chart of content ratings → found **‘Everyone’** category dominates  

3. **Bivariate Analysis**
   - Scatter plot (App Size vs. Rating) → weak trend, medium-sized apps perform better  
   - Regression plots → explored subtle correlations between variables  

4. **Multivariate Analysis**
   - Pair plots → insights on relationships:
     - Price & Rating → very weak correlation  
     - Reviews & Price → mostly inversely related  
   - Box plots & bar plots (by Content Rating) → highlighted spread of ratings across categories  

5. **Advanced Insights**
   - Heatmap of Ratings vs. Reviews vs. Content Ratings → identified user preference clusters  
   - Category-wise install distribution → Games, Family, Tools dominate in count, while Communication & Social apps dominate in installs  

---

## 🔑 Key Insights
1. **App Ratings:** Most apps maintain a strong rating between **4.0–4.5**, showing positive user satisfaction.  
2. **App Categories:** *Family, Games, and Tools* dominate in volume; *Social & Communication* apps lead in installs.  
3. **Pricing Strategy:** ~92% of apps are **free**, reflecting a freemium-driven ecosystem.  
4. **Paid Apps:** Attract fewer installs; pricing does **not directly boost ratings**.  
5. **App Size:** Medium-sized apps (**10–50MB**) perform best in installs & ratings.  
6. **User Reviews:** Generally, more reviews = higher ratings, with some outliers.  
7. **Install Distribution:** Right-skewed; most apps between **1,000–100,000 installs**, very few cross **1B installs**.  
8. **Content Rating:** **‘Everyone’** dominates, reflecting mass adoption of general-use apps.  
9. **Gaming Apps:** Arcade, Casual, and Action games lead the space; niche genres have smaller but loyal bases.  
10. **Top Performers:** Apps like **WhatsApp, YouTube, and Google services** dominate installs and ratings → showing their indispensability.  

---

## 📈 Visuals & Techniques Used
- Histograms, Bar Charts, and Box Plots  
- Scatter Plots and Regression Plots  
- Pair Plots for multivariate relationships  
- Heatmaps for comparative analysis  

---

## 🚀 Conclusion
The analysis highlights how **user satisfaction, app category, size, and freemium models** influence app success on the Google Play Store.  
These findings can help **developers, marketers, and businesses** optimize app design, pricing strategies, and user engagement.

---

## How to Use

1. **Clone the Repository**: Clone this repository to your local machine.
   ```sh
   git clone https://github.com/Gitwithmohit/Google_Play_Store_Analysis_EDA.git
   ```

## Author - MOHIT PURI


Thank you for your interest in this project!
