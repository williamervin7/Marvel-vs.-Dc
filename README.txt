# Marvel vs. DC Movies - Financial & Critical Performance Analysis

## Project Overview

This project compares the financial and critical performance of Marvel and DC movies based on their budgets, box office earnings (both in the USA and worldwide), and critical ratings. The analysis includes:

- Average Gross Earnings vs. Budget
- Critical Ratings vs. Gross Earnings
- Trends over time for Marvel and DC
- Return on Investment (ROI) comparison

## Data Sources

- **Marvel and DC Movies Dataset**: Data used in this analysis includes information on movie titles, release years, budgets, earnings, and critical ratings for both Marvel and DC films.

## Project Structure

- **Data Preprocessing**: Data was cleaned and aggregated, focusing on `Budget`, `Gross USA`, `Gross Worldwide`, and `Rate` (ratings).
- **Data Analysis**: 
  - Comparison of average gross earnings and budgets between Marvel and DC.
  - Exploration of trends over time for both companies.
  - Correlation analysis between ratings and gross earnings.
- **Visualizations**: 
  - Scatter plots to show the relationship between ratings and earnings.
  - Line plots to observe trends over time.
  - Bar charts to compare the total and average earnings for Marvel and DC.

## Key Findings

### 1. **Which Company Delivers Better ROI?**

- **Marvel** delivers a much better Return on Investment (ROI) than **DC**. The analysis shows a positive correlation between increasing budgets and increasing worldwide earnings for Marvel, indicating strong ROI.
- **DC**, on the other hand, lacks a consistent relationship between budget and earnings, with some high-budget films failing to generate proportionate returns.

### 2. **Who Leads in Critical and Commercial Performance?**

- **Critical Performance**: Marvel's films generally receive higher ratings compared to DC's films. This is evident in the scatter plot, where higher-rated Marvel films tend to have higher earnings.
- **Commercial Performance**: Marvel leads in worldwide box office earnings. The top 3 highest-grossing Marvel films grossed over a billion dollars each, while DC's highest-grossing films grossed significantly less.

### 3. **Strategic Recommendations**

#### For Marvel:
- Continue increasing production budgets as this has consistently resulted in higher earnings.
- Maintain high production quality to ensure that investments translate into profitable films.
- Focus on expanding both stand-alone films and interconnected cinematic universes to capitalize on commercial and critical success.

#### For DC:
- Refine budget allocation for films and focus on higher returns by investing in films that have a better chance of success.
- Improve critical reception through better scriptwriting, direction, and character development.
- Explore diverse movie strategies, such as stand-alone projects or reworking the cinematic universe approach to avoid inconsistencies in performance.

## Visualizations

### 1. **Average Gross Earnings vs. Budget** (Bar Chart)
This chart compares the average gross earnings and budgets for both Marvel and DC movies, showing that Marvel has consistently outperformed DC in both revenue and ROI.

### 2. **Opening Weekend vs. Year** (Line Chart)
A trend analysis of opening weekend earnings for both Marvel and DC shows that Marvel’s films have seen a steady increase in opening weekend earnings, while DC has experienced more volatility.

### 3. **Ratings vs. Gross Earnings** (Scatter Plot with Trend Line)
This scatter plot illustrates the correlation between critical ratings and worldwide gross earnings. Both Marvel and DC films tend to perform better commercially when rated higher, but Marvel has a more consistent positive correlation.

### 4. **Budget and Gross Worldwide Over Time** (Dual-axis Line Plot)
A comparison of how Marvel and DC’s budgets and worldwide gross earnings have evolved over time. Marvel's financial success and consistent budget increases are evident, while DC shows more fluctuating results.

## Requirements

- Python 3.x
- Pandas
- Matplotlib
- Seaborn

