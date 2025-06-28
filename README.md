# SuperStore Profit & Loss Analysis

A brief description of what this project does and who it is for*📊 SuperStore Returns & Loss Analysis

This Tableau Dashboard analyzes customer returns from the SuperStore Dataset to identify patterns, quatify losses, and uncover
inprovement areas in the product, region, and time dimensions.

## 🔍 Project Objectives
- Calculate return rates across product categories and multilple regions
- Visualize the return patterns over time
- Quantify sales lost due to many returns in severeral categorys
- Indentify the highest-risk of categories and geographics

## 📂 Data Source 

**Dataset** [SuperStore](https://public.tableau.com/app/profile/lonn.mejiano/viz/Superstore_Analysis_17495396141450/Advertising)

-**Orders Sheet** Used

## 🧮 Calculated Fields Used

###' 'Return Flag'
IF [Returned] = "Yes" THEN 1 ELSE 0 END
