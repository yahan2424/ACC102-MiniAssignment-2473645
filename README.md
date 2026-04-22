# ACC102-MiniAssignment-2473645
Profitability Analysis: Moutai vs Wuliangye
# Track 2
# Profitability Comparison: Kweichow Moutai vs Wuliangye

## 1. Project Overview
This project analyses and compares the profitability performance of two leading Chinese high-end baijiu companies: Kweichow Moutai (600519) and Wuliangye (000858). Using quarterly financial data from 2021 to 2024, the analysis focuses on two core profitability indicators: ROE and Net Profit Margin. The output is intended to help investors and industry analysts understand the long-term profitability stability and competitive advantages of both firms.

## 2. Data Source & Information
- Data Source: WRDS CSMAR Financial Database
- Access Date: April 2026
- Time Period: 2021–2024 (Quarterly)
- Key Variables: Stock code, accounting period, total assets, net profit, operating revenue

## 3. Methodology
1. Data extraction via SQL query from WRDS CSMAR
2. Data cleaning: missing value removal, deduplication, date formatting
3. Financial ratio calculation: ROE and Net Profit Margin
4. Outlier filtering to ensure stable trend analysis
5. Time-series visualisation for comparative analysis

## 4. Key Findings
1. Kweichow Moutai maintains a significantly higher Net Profit Margin than Wuliangye across the whole period.
2. Both companies show stable profitability trends without extreme fluctuations.
3. Moutai’s stronger profitability reflects its premium brand positioning and higher pricing power.

## 5. Repository Structure
- ACC102_MiniAssignment_Track2.ipynb: Main analysis notebook
- README.md: Project documentation

## 6. How to Run
1. Install required packages: pandas, matplotlib, wrds
2. Open the Jupyter notebook
3. Run all cells sequentially from top to bottom
4. View the final charts and analysis results

## 7. Limitations
- ROE is simplified using total assets instead of shareholders’ equity.
- No seasonal adjustment applied to quarterly data.
- Only two companies are included; industry-wide comparison is not provided.

## 8. Product & Demo Links
- GitHub Repository: https://github.com/yahan2424/ACC102-MiniAssignment-2473645.git
- Demo Video: 【ACC102 Track2】 https://www.bilibili.com/video/BV1Gxo4BzEMe/?share_source=copy_web&vd_source=a7c68cb413b14c0ce0c9559a17de9272

## 9. AI Disclosure
- AI Tool: Doubao (Seed Model),DeepSeek,QianWen
- Access Date: April 2026
- Purpose: Code formatting, visualization adjustment, English writing, and README structure.

Author: [Yahan.Sun]
Module: ACC102
