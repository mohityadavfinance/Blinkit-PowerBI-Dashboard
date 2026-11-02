# Blinkit-PowerBI-Dashboard
"An interactive Power BI dashboard analyzing Blinkit's sales performance, outlet types, and customer ratings."
# Blinkit Sales & Performance Dashboard

## 📌 Project Overview
This project involved analyzing Blinkit's (India's last-minute delivery app) sales data to uncover key insights regarding outlet performance, item visibility, and customer ratings. The goal was to provide actionable recommendations to optimize sales strategies across different outlet types and locations.

## 🛠️ Tech Stack
* **Tool:** Power BI Desktop
* **Data Transformation:** Power Query
* **Calculations:** DAX (Data Analysis Expressions)
* **Data Source:** [Mention where you got the data, e.g., Kaggle / Provided Dataset]

## 📊 The Dashboard
*(Drag and drop your Screenshot_Dashboard.png file right here into the GitHub editor. It will automatically insert the image code!)*

## 💡 Key Insights
* **Total Sales:** Generated 1.20M in total sales.
* **Outlet Performance:** Tier 3 outlets generated the highest sales (472.86K).
* **Product Categories:** Fruits, Snacks, and Household items are the top-selling categories.
* **Outlet Types:** Supermarket Type 1 accounted for the highest total sales (788.55K).

## 🔍 Data Modeling & DAX
*(Drag and drop your Screenshot_Data_Model.png file here)*
I created a robust data model to ensure accurate filtering and cross-filtering. Key DAX measures used include:
* `Total Sales = SUM(Sales[Sales])`
* `Average Rating = AVERAGE(Sales[Rating])`
* `No of Items = COUNTROWS(Sales)`

## 📁 Files in this Repository
* `Blinkit_Dashboard.pbix`: The source Power BI file. (Download and open in Power BI Desktop to interact with the report).
* `Blinkit_Dataset.xlsx`: The raw data used for this project.
