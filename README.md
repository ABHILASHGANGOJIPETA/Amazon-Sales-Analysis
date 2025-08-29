# 📊 Amazon Sales Analysis Dashboard (Power BI)

🚀 This project is a **Power BI Dashboard** built to analyze Amazon product sales and reviews.  
It focuses on **Year-to-Date (YTD)** and **Quarter-to-Date (QTD)** insights, helping track sales performance, product demand, and customer feedback.

---

## 🔹 Problem Statement
The business needs to monitor **sales performance and customer reviews** to identify growth opportunities and track top-performing products.

### KPI’s Requirement
- **YTD Sales** – Track year-to-date sales performance  
- **QTD Sales** – Monitor quarterly sales trends  
- **YTD Products Sold** – Analyze number of products sold throughout the year  
- **YTD Reviews** – Assess customer satisfaction via reviews  

### Charts Requirement
- 📈 **YTD Sales by Month** (Line Chart)  
- 📊 **YTD Sales by Week** (Column Chart)  
- 🔥 **Sales by Product Category** (Text Table)  
- 🏆 **Top 5 Products by YTD Sales** (Bar Chart)  
- ⭐ **Top 5 Products by YTD Reviews** (Bar Chart)  

---

## 📂 Dataset
The dataset used: **`Amazon_Combined_Data.xlsx`**  

It contains information on:  
- **Order Date**  
- **Product Category & Description**  
- **Price (Dollar)**  
- **Shipments**  
- **Customer Reviews**  

---

## 🧹 Data Cleaning & Preparation
Before building the dashboard, the dataset was cleaned to ensure accuracy and reliability:  
- ✅ **Removed Duplicates** – Dropped duplicate transactions and product rows  
- ✅ **Handled Missing Values** – Replaced or removed nulls in `Price`, `Order Date`, and `Reviews`  
- ✅ **Date Formatting** – Converted `Order Date` into proper **Date Hierarchy (Year, Quarter, Month, Week)**  
- ✅ **Standardized Categories** – Corrected inconsistent product category names (e.g., “Men Shoes” vs. “Mens Shoes”)  
- ✅ **Outlier Check** – Identified extreme values in `Price (Dollar)` to avoid misleading trends  
- ✅ **Created Date Table** – Added custom date table with fields: `Month`, `Quarter`, `Week Number`, etc.  


## ⚙️ Tools Used
- **Power BI** (Data Visualization & Dashboarding)  
- **Excel** (Data Source & Cleaning)  
- **DAX** (KPI Calculations & Measures)  

---

## 🎯 Key Insights
✔️ Sales peaked in **September & December**  
✔️ **Men Shoes & Cameras** are the top-selling categories  
✔️ Customer reviews show strong engagement, with **SanDisk products** leading  

---

## 📌 How to Use
1. Clone this repository or download as ZIP  
2. Open the `.pbix` file in **Power BI Desktop**  
3. Load the dataset (`Amazon_Combined_Data.xlsx`) if required  
4. Explore the dashboard using filters (Product Category, Quarter, etc.)  

---

## 👨‍💻 Author
**Abhilash Gangojipeta**  
📧 [imabhi.1753@gmail.com]  
🔗 [https://www.linkedin.com/in/abhilashgangojipeta/]  

