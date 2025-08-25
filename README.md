# India Asia Cup Squad – Data-Driven Selection (2018–2025)

## Overview  
This project builds a **data-driven 15-member Indian squad** for the Asia Cup by analyzing **ODI data series-by-series from 2018–2025**. The aim was to evaluate players not just by reputation but by **performance and potential using analytics**.

## Data Collection & Cleaning  
- **Data Source:** Scraped from ESPN Cricinfo using Python.  
- **Challenge:** Same players repeated across series.  
- **Solution:** Created a **unique player ID table** and mapped records using **VLOOKUP** and **INDEX** in Excel.  
- **All-rounder Dataset:** No dedicated table existed, so **batting and bowling stats were merged** to create one.  

## Player Categorization  
Players with **5+ innings** were classified into 6 roles:  
1. **Top Order (Power Hitters + Consistent)**  
2. **Middle Order (Consistent)**  
3. **Lower Order / Batting All-rounders (Aggressive + Power Hitters)**  
4. **Wicketkeepers**  
5. **All-rounders (Power Hitters + Economical)**  
6. **Bowlers (Wicket-takers)**  

### Sample Filters  
- **Top Order:** Avg. balls faced > 40, Boundary% > 40, Batting Avg > 35, Strike Rate > 80  
- **All-rounders:** Balanced batting & bowling economy  
- **Bowlers:** High wicket-taking ability  

## Handling Young Players  
For uncapped players like **Abhishek Sharma, Riyan Parag, Yashasvi Jaiswal, Shivam Dube**, **T20I data** was used to evaluate potential.  

## Final 15-Member Squad  
**Abhishek Sharma, Rohit Sharma, Virat Kohli, Shubman Gill (C), Shreyas Iyer, Hardik Pandya, KL Rahul (WK), Sanju Samson (WK), Axar Patel, Ravindra Jadeja, Varun Chakaravarthy, Jasprit Bumrah, Kuldeep Yadav, Mohammed Siraj, Arshdeep Singh**  

## Tools & Skills Used  
- **Python:** Web scraping, data cleaning  
- **Excel:** Data mapping, VLOOKUP, INDEX  
- **Power BI:** Visualization and analysis  

## Visualizations & Insights  
*(Add screenshots or Power BI dashboard images if available)*  

## How to View  
- Open Python/Jupyter files for scraping and cleaning scripts.  
- Check Excel files for processed data.  
- Open Power BI files to explore dashboards.  
