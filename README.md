# Pandas Challenge 1 

## Overview
This repository contains the Module 4 Pandas Challenge due on December 11, 2024. The challenge focuses on data analysis and transformation using Python's Pandas library. 

## The Business Use case is:
Identify top customers, popular product categories, calculating profits, and more.


## Challenge Instructions

### Part 1: Explore the Data
In this section, you will import and analyze the dataset using Pandas:

1. Import the data from the CSV file
2. Examine the column names
3. Use the `describe()` function for basic statistics
4. Answer key questions about the data:
   - Identify the three item categories with the most entries
   - Find the subcategory with the most entries within the top category
   - Determine the five clients with the most entries
   - Create a list of the top 5 client IDs
   - Calculate total units ordered by the top client

### Part 2: Transform the Data
Create new columns for analysis:

1. Calculate subtotal (unit_price × qty)
2. Determine shipping price:
   - Orders > 50 pounds: $7 per pound
   - Orders ≤ 50 pounds: $10 per pound
3. Calculate total price (subtotal + shipping + 9.25% sales tax)
4. Compute line cost (unit cost + shipping)
5. Calculate profit (line price - line cost)

### Part 3: Confirm Your Work
Verify calculations against known receipt totals:
- Order ID 2742071: $152,811.89
- Order ID 2173913: $162,388.71
- Order ID 6128929: $923,441.25

### Part 4: Summarize and Analyze
1. Calculate spending for top 5 clients
2. Create a summary DataFrame with:
   - Total units purchased
   - Total shipping price
   - Total revenue
   - Total profit
3. Format currency in millions and sort by total profits
4. Provide a brief analysis summary

## Hints and Considerations
- Consult Pandas DataFrame documentation
- Use functions appropriately
- Follow all analytical process steps
- Read instructions completely before starting

## Requirements

### Explore the Data (30 points)
- View column names (4 points)
- Use describe function (4 points)
- Identify top category (4 points)
- Find top subcategory (5 points)
- Identify top 5 clients (5 points)
- Store top 5 client IDs (4 points)
- Calculate total units for top client (4 points)

### Transform the Data (30 points)
- Create subtotal column (6 points)
- Calculate shipping price (6 points)
- Determine total price (6 points)
- Calculate line cost (6 points)
- Compute profit (6 points)

### Confirm Your Work (15 points)
- Verify Order ID 2742071 (5 points)
- Verify Order ID 2173913 (5 points)
- Verify Order ID 6128929 (5 points)

### Summarize and Analyze (25 points)
- Calculate top 5 client revenue (5 points)
- Create summary DataFrame (5 points)
- Format and sort data (5 points)
- Write analysis summary (10 points)

## Repository Information
- Remote: https://github.com/Raymond-St/pandas-challenge-1
- Local: C:\Users\resto\AI\Projects\Module_4_pandas-challenge-1\pandas-challenge-1

## Contact
For questions or feedback, please contact: RStover@Gmail.com
