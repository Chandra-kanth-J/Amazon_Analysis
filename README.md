# 📊 Amazon Sales Dataset Analysis

This project showcases an **Exploratory Data Analysis (EDA)** on a dataset of over **1,400 Amazon product listings**. The dataset includes pricing, discounts, ratings, reviews, and other product-related metadata scraped from **Amazon India**.

The primary objective is to extract actionable insights into customer preferences, product performance, pricing patterns, and discounting strategies across various product categories.

---

## 📌 Project Objectives

The analysis addresses the following key questions:

⭐ **1. Which categories have the highest customer satisfaction?**  
Identified the Top 5 product categories based on average customer ratings.

🔗 **2. Is there a link between discounts and product ratings?**  
Used Pearson correlation to determine if discounted pricing influences customer perception and rating behavior.

🏷️ **3. What keywords are common in product names?**  
Created a function to extract lowercase, alphabetic keywords from product titles — useful for trend spotting and feature analysis.

💸 **4. How do discount rates vary across categories?**  
Calculated the average discount percentage by category to uncover patterns in promotional strategies.

📈 **5. How are prices distributed across products?**  
Visualized and compared the distributions of actual and discounted prices to detect trends and outliers.

🥇 **6. Which products are most popular within each category?**  
Ranked products by number of reviews per category to measure popularity and customer engagement.

⚖️ **7. What is the overall discounting behavior?**  
Plotted side-by-side histograms of actual vs discounted prices to analyze general pricing behavior.

---

## 🗃️ Dataset Overview

- **Total Records:** 1,465  
- **Features:** 16 columns  
- **Source:** Scraped from Amazon India  
- **Scraping Tools:** BeautifulSoup, Selenium WebDriver  

The dataset includes product IDs, names, categories, pricing details, customer ratings, and user-generated reviews — offering a comprehensive snapshot of Amazon product listings.

---

## 🧹 Data Cleaning & Preprocessing

Key steps taken to prepare the data:

- Removed currency symbols (₹), commas, and percentage signs from numeric fields  
- Converted price and rating columns to numeric data types  
- Imputed missing values using median strategy  
- Removed duplicate records for clean analysis  
- Applied Label Encoding to categorical variables for modeling readiness  

---

## 🛠️ Tools & Technologies

- **Language:** Python  
- **Libraries:** Pandas, NumPy  
- **Visualization:** Matplotlib, Seaborn  
- **Preprocessing:** Scikit-learn (Label Encoding)  
- **Environment:** Jupyter Notebook  

---

## 📊 Visualizations & Insights

The analysis is supported by multiple visualizations:

- **Histograms** – for price distribution  
- **Scatter plots** – to explore correlations (e.g., price vs rating)  
- **Heatmaps** – for feature relationships  
- **Bar charts** – for comparing discounts and ratings across categories  

---

## 📋 Summary of Insights

- Categories with highest-rated products  
- No strong correlation between discounts and ratings  
- Keyword patterns in high-performing products  
- Variation in pricing and discounting across categories  
- Products with high engagement (reviews)  

These insights help businesses optimize product listings, refine pricing strategies, and improve customer experience on e-commerce platforms like Amazon.


## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/Chandra-kanth-J/Amazon_Analysis.git

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook Amazon_EDA_Project.ipynb

