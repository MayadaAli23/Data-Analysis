# 📊 Amazon Egypt Mobiles Data Analysis

## 📌 Overview
This project involves **web scraping** mobile phone product data from **Amazon Egypt** using `Selenium` and analyzing it with `Pandas`.  
The analysis includes:
- Cleaning and preprocessing the dataset.
- Filtering out irrelevant products.
- Categorizing products into **price segments**.
- Finding top brands and calculating average ratings & prices.

---

## 🛠️ Technologies Used
- **Python**
- **Selenium** for web scraping
- **Pandas** for data analysis
- **Chrome WebDriver** for browser automation


---

## 🔍 Data Collection Process
1. Used **Selenium WebDriver** to navigate Amazon Egypt's mobile phones category.
2. Extracted:
   - **Product Name**
   - **Price**
   - **Rating**
   - **Review Count**
3. Saved the results to `amazon_eg_mobiles.csv`.

---

## 🧹 Data Cleaning
- Removed rows with **missing product names**.
- Dropped products containing keywords like `"Case"` or `"Selfie Stick"`.
- Filtered out products with prices less than **450 EGP**.
- Filled missing `Rating` and `Review Count` with the mean/median.

---

## 📊 Analysis Performed
### 1. Price Segmentation
Products are categorized as:
- **Low Budget** → Below 15,000 EGP
- **Mid-Range** → 15,000 EGP to 40,000 EGP
- **Flagship** → Above 40,000 EGP

### 2. Average Rating by Price Category
Calculated the mean rating for each price segment.

### 3. Brand Analysis
- Extracted brand names from product titles.
- Counted the number of products per brand.
- Calculated **average price** and **average rating** per brand.
- Sorted brands by **popularity**.

---

## 📈 Example Insights
- Most popular brands in Amazon Egypt's mobile market.
- Price distribution among mobile phones.
- Top-rated brands in each segment.

---


📌 Notes
- Web scraping might break if Amazon updates its HTML structure.
- Use responsibly and avoid sending too many requests in a short period.

## 🧠 Author

Mayada Ali
_Data Analyst_  
LinkedIn: https://www.linkedin.com/in/mayadaali23/
GitHub: https://github.com/MayadaAli23


