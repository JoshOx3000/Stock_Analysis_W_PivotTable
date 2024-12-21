# Stock_Analysis_W_PivotTable
designed for practicing pivot table skills in Excel or other spreadsheet tools

Here’s the updated README with credit to Alex Freberg and Analyst Builder:

---

# Stock Data Analysis Using Pivot Tables

This repository contains a dataset of stock market information, designed for practicing pivot table skills in Excel or other spreadsheet tools. The project focuses on analyzing key metrics for companies across various sectors, using raw data and answering specific business questions.

**This exercise is inspired by the Analyst Builder course by Alex Freberg. Full credit to Alex Freberg for creating this engaging and educational exercise.**

## 📁 Repository Structure

- **`Raw_Data/`**: Contains the original dataset for analysis.
- **`Final_Analysis/`**: Contains the final pivot tables and answers to the analysis questions.

## 📊 Analysis Objectives

1. **What is the Average Dividend Yield?**
   - Per **Sector** and **Company**.
   
2. **What is the Total Market Cap per Sector?**
   - Market Cap is calculated as `Price * Shares`.

3. **Which sectors meet the investment criteria?**
   - Criteria:
     - Dividend Yield > 2
     - Market Cap > Sector's average

## 📘 Data Dictionary

| Column Name       | Description                                                                                  |
|--------------------|----------------------------------------------------------------------------------------------|
| **Symbol**         | The stock symbol or ticker symbol of the company. It is a unique identifier for publicly traded companies. |
| **Name**           | The name of the company.                                                                    |
| **Sector**         | The industry or sector to which the company belongs, such as "Industrials" or "Health Care".|
| **Price**          | The stock price of the company at a specific point in time.                                 |
| **Price/Earnings** | The price-to-earnings (P/E) ratio, a measure of company valuation (`Price ÷ Earnings/Share`).|
| **Dividend Yield** | The dividend yield (%) representing expected income from the company's stock.               |
| **Earnings/Share** | The company's profit per outstanding share.                                                 |
| **52 Week Low**    | The lowest stock price in the past 52 weeks.                                                |
| **52 Week High**   | The highest stock price in the past 52 weeks.                                               |
| **Shares**         | Total share options issued by the company.                                                  |
| **EBITDA**         | Earnings before interest, taxes, depreciation, and amortization (operating performance).    |

## 🚀 How to Use

1. Open the `Raw_Data` file in your spreadsheet software.
2. Create a pivot table to answer the analysis questions:
   - Use **Sector** and **Company** as row/column fields.
   - Calculate metrics such as:
     - Average **Dividend Yield**
     - Total **Market Cap**
   - Apply filters for the investment criteria.
3. Refer to the `Final_Analysis` folder for the completed pivot table with answers.

## 🔧 Tools Required

- Spreadsheet software like Microsoft Excel or Google Sheets.
- Basic knowledge of creating and customizing pivot tables.

## 🏆 Key Learning Outcomes

- Mastery of pivot table creation and customization.
- Ability to analyze stock data and identify strong investment sectors.
- Improved skills in filtering and summarizing large datasets.

## 💡 Future Enhancements

- Automate the analysis using Python (e.g., pandas).
- Integrate visuals to enhance insights (e.g., charts for market cap by sector).

---

Feel free to modify this further to suit your style while giving credit where it’s due!
