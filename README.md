# Power BI Product Analysis

This repository contains my solution for Assignment 2 from Internshala Trainings, focusing on advanced Power BI features for product data analysis.

## Assignment Overview

The project involves analyzing product data to understand profit margins, pricing factors, and product performance using various advanced Power BI visualization techniques.

## Dataset
- `products.xlsx`: Contains product information including:
  - ProductPrice
  - ProductCost
  - ProductColor
  - ProductStyle
  - ProductSize
  - ProductSubcategory

## Tasks Completed

### 1. Profit Margin Analysis
- Created custom column calculating ProfitMargin = (ProductPrice - ProductCost)/ProductPrice
- Added conditional column classifying products as High/Medium/Low Margin

### 2. Q&A Visualization
- Used Power BI's Q&A feature to create a bar chart showing average product cost by color

### 3. Decomposition Tree
- Analyzed ProductPrice by ProductColor and ProductStyle to identify price drivers

### 4. Key Influencer Analysis
- Determined which product attributes influence high prices

### 5. Data Transformation & Conditional Formatting
- Created new column extracting first letter of product colors
- Applied conditional formatting to highlight cost variations

### 6. Bookmarks
- Created interactive bookmarks for different product views

### 7. Card Visuals
- Designed single-row and multi-row cards for key metrics

### 8. Reference Line
- Added reference line in line chart to show average pricing

### 9. Data Cleaning
- Identified and removed duplicate product records

### 10. Treemap Visualization
- Created treemap showing price distribution and top profitable subcategories

## Files Included
- `Assignment2.pdf`: Completed assignment PDF with screenshots and steps
- `products.csv`: The dataset used (optional)
- `Product_Analysis.pbix`: Power BI project file (optional)
- `README.md`: This documentation file

## Advanced Features Demonstrated
- Power BI Q&A natural language processing
- Decomposition tree analysis
- Key influencer detection
- Advanced conditional formatting
- Bookmark navigation
- DAX measures for profit calculations
- Treemap and card visualizations
