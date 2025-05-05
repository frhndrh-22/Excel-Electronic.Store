# Excel-Electronic.Store

Welcome to the Excel-Electronic.Store project! In this repository, I've demonstrated my skills in data cleaning, analysis, and visualization using Excel to analyze sales data for an electronic store. This project showcases my ability to handle large datasets, apply Excel functions, and present insights that are crucial for business decision-making.

## 📝 Project Overview

The dataset consists of sales transactions from an electronic store. It includes information on order id, products, prices, quantities, order dates, cities and purchase addresses. Through this analysis, I aimed to:

  - Clean and structure the data for analysis.
  - Perform descriptive analysis (e.g., total sales, sales by product, sales by city).
  - Create pivot tables to summarize sales trends.
  - Visualize the data through charts to make it easier to interpret.

## 🎯 Skills Demonstrated

1. Data Cleaning 🧹

    * **Removing Duplicates:** Cleaned up the dataset by removing duplicates where necessary, especially ensuring that each unique order was kept even if customers purchased multiple items.
    * **Handling Missing Data:** Used Excel’s Go To Special > Blanks to detect and ensure no missing values.
    * **Formatting:**
      - Properly formatted the Order Date column to remove time and just show the date using the formula =INT(E2).
      - Applied appropriate data types to columns like Quantity Ordered (number), Price Each (accounting), and Sales (accounting).

<img width="440" alt="Blank Cells" src="https://github.com/user-attachments/assets/5bb44bc7-5bc8-40d4-b9c9-41bba6fa82eb" />

<img width="816" alt="Order Date Before" src="https://github.com/user-attachments/assets/58583ff0-ce03-43d0-9d9f-37629e729cec" />

<img width="815" alt="Order Date After" src="https://github.com/user-attachments/assets/9242e11c-3d53-42a7-8803-4e7c5fa651f2" />

2. Data Normalization 🔄

    * **VLOOKUP for Product IDs:** Created a new sheet called References, where I added unique Product IDs for each product. I then used the VLOOKUP function in the Sales Data sheet to link products with their corresponding Product ID.

<img width="710" alt="VLOOKUP Product ID" src="https://github.com/user-attachments/assets/1d85d788-0d86-46c3-a645-d0cc00b34943" />

3. Conditional Formatting & Data Validation 🖌️

    * **Conditional Formatting:** Highlighted duplicate Order ID values in red, as customers purchasing multiple items in a single checkout (same order ID) needed to be clearly marked.
    * **Data Validation Message:** Added a helpful message to the Order ID column explaining that red cells indicate duplicated Order IDs.

4. Data Analysis 🧠

    * Calculated key metrics such as total **sales, average sales, maximum, and minimum**.
    * Created **pivot tables** to summarize sales by product and city.
    * Analyzed **sales trends** across quarters and products.

<img width="208" alt="SUM:AVERAGE:MIN:MAX" src="https://github.com/user-attachments/assets/974ee6c9-cf84-4053-beb4-a024086c9a3a" />

5. Data Visualization 💡

    * Created **pie charts** to show the percentage of **sales by product.**
    * Built **bar charts** to visualize **quarterly sales by city.**

## 📚 Files Included

  - **Electronic.Store.xlsx:** The main dataset containing all cleaned and processed data.
  - **Sales Data:** The primary sheet with sales transactions, including columns for Order ID, Product, Product ID, Quantity Ordered, Price Each, Formatted Order Date, Purchase Address, Sales and City.
  - **References:** A secondary sheet containing unique Product IDs and their corresponding Price Each.
  - **Pivot Tables and Charts:** Analysis of total sales, product performance, and city-based sales trends.

## 📊 Key Visualizations

🔹 **Total Percentage Sales (Product)**
- A pie chart visualizing the contribution of each product to total sales. This helps identify which products are performing best.
- The Macbook Pro Laptop contributed 23% of the total sales, followed by the iPhone at 14%.

<img width="690" alt="Popular Product" src="https://github.com/user-attachments/assets/debb83c7-4317-4a57-b8ba-7eff395dc084" />

🔹 **Total Quarterly Sales (City)**
- A bar chart showing the total sales per city for each quarter. This helps visualize which cities have the highest sales across different quarters.
- San Francisco showed the highest sales in Q4, indicating strong end-of-year performance.

<img width="678" alt="Total Quarterly Sales (City)" src="https://github.com/user-attachments/assets/4c13b459-1d66-479c-99eb-2cee76345db8" />

## 🔍 Analysis & Insights 📈

1. **Top-selling Products:**
    - The Macbook Pro Laptop was the top seller, contributing 23% of total sales.
    - Other popular products include the iPhone (14%) and ThinkPad Laptop (12%).
2. **Sales Trends by City:**
    - San Francisco consistently had the highest sales across all quarters, with - significant spikes in Q4.
    - Cities like Atlanta and Austin showed stable sales growth over the year.
3. **Quarterly Sales Performance:**
    - Q4 showed the highest sales across most cities, indicating strong end-of-year performance.
    - The Seattle market was strong in Q1, but saw a decline in later quarters.

## 🏁 Conclusion

Through this project, I've demonstrated my ability to work with real-world sales data and produce actionable insights. The use of Excel functions like **VLOOKUP, pivot tables, conditional formatting,** and **data validation** helped me **clean, organize, and analyze the data** efficiently. The **visualizations** provide a clear overview of **sales trends**, which is crucial for decision-making in any business.

## 🚀 Future Enhancements

- Implement more advanced analyses, such as forecasting sales trends based on - historical data.
- Explore Power BI or Tableau for more dynamic visualizations and dashboard creation.
- Incorporate Python or SQL for more automated data processing.

## 💻 How to Use the Files

1. Download the repository.
2. Open Electronic.Store.xlsx in Excel.
3. Review the data in the Sales Data and References sheets.
4. Explore the Pivot Tables and Charts to gain insights into the data.

# 🌟 Thank You For Your Time 🌟
