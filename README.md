# AtliQ Mart Campaign Analysis

### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiOTBjMjEzNTYtZTdiMi00Y2VjLWI2OGQtMDhlNjZkY2YxMmQ1IiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9

## Problem Statement
AtliQ Mart, a renowned retail giant with over 50 supermarkets in the southern region of India, aimed to analyze the performance of their promotional campaigns during the festive seasons of Diwali 2023 and Sankranti 2024. The sales director sought actionable insights to strategize future promotional activities effectively.

### Steps followed 
- Step 1 : Converted Data files into Excel workbook from CSV Files.
- Step 2 : Peformed Data cleaning on all files like checked for duplicates, unnecessory spaces ETC.
- Step 3 : Converted files into table and brought all tables in one file.
- Step 4 : Performed Basic Statistical Analysis such as Mean, Median, Mode, Etc.
- Step 5 : Created Calculated columns Promotion Price, Revenue before promotion, Revenue after promotion, Total revenue, incremental sold units and incremental revenue.
- Step 6 : Used VLookup to merge two tables and bring required columns in one table for further Analysis.
- Step 7 : Performed Exploratory Data Analysis using Excel functions, formulas and Pivot tables. 
- Step 8 : Loaded Cleaned datasets in Power BI.
- Step 9 : Created Metrics Incremental Revenue and Incremental sold unit Using DAX Expressions as well as some calculated columns as stakeholders requirements.
- Step 10 : Used Card visuals to Show KPI's Incremental revenue, Incremental sold units, Total revenue, Total sold units, Revenue before promotion, revenue after promotion.
- Step 11 : In store Analysis Dashboard using Table visuals showed top 10 stores by incremental revenue, bottom 10 stores by incremental sold units.Using map visual showed incremental revenue per store by cities.
- Step 12 : In Promotion Analysis Dashboard using column chart visuals showed top 2 stores by incremental revenue, bottom 2 stores by incremental sold units. Bar chart visuals used to a.To show promotions category by incremental revenue and Incremental sold units. b.Distribution of incremental revenue by promotions and product category.Also table visual to show efficiency ratio of promotions.
- Step 13 : In Product and Category Analysis Dashboard using column chart visuals showed top 3 Product by incremental revenue, bottom 3 product by incremental sold units.used stacked bar chart Correlation Between Product Category and Promotion Category. used line chart to show Incremental  Revenue and incremental sold units By Product Category.
- Step 14 : Slicers are used to filter visuals by campaign, promotions, category, product code.
- Step 18 : The report was then published to Power BI Service.
 
 
# Snapshot of Dashboard (Power BI Service)


![power bi service](https://github.com/akshayhchawan/AtliQ-Mart-Campaign-Analysis-Project/assets/167336764/fdb652ce-1d6f-48bd-9efc-80ef62a6a12a)

 
 # Report Snapshot (Power BI DESKTOP Store Analysis)

 ![store analysis](https://github.com/akshayhchawan/AtliQ-Mart-Campaign-Analysis-Project/assets/167336764/a4c3ad37-05f2-4c5b-b810-31d909d6fbc9)

 
 # Report Snapshot (Power BI DESKTOP Promotion Analysis)

![promotion analysis](https://github.com/akshayhchawan/AtliQ-Mart-Campaign-Analysis-Project/assets/167336764/e14965ba-a712-4256-aa78-ed50e59eeec3)


 # Report Snapshot (Power BI DESKTOP Product & Category Analysis)

![product analysis](https://github.com/akshayhchawan/AtliQ-Mart-Campaign-Analysis-Project/assets/167336764/e54fd030-62a1-4ded-a0d4-39546f8f93d3)



# Insights

### Store Analysis:
1. Total Incremental Revenue is 107 Millions increased by 76.2%.
2. Total Sold Units is 226 thousand that is 108.3% increased.
3. Top 10 Stores by incremental Revenue holds 30.60% share in IR and and 25.43% in ISU.
4. The Top Performing Store STMYS -1 By IR is From Mysuru City with IR 3.63 Millions and Isu 6863.
5. The Bottom Performing Store STMLR-0 By ISU is From Mangalore City with ISU 1952  and IR 0.78 Millions.
6. In Both Stores Two of Top performing products are similar which Can be seen Thoruought all the Stores P15 and P04, Which gives indication that performance of these products defines stores ranking.
7. Top 3 Cities By Incremental Revenue Per store are Bengaluru with 2.67 Millions, Chennai with 2.65 Millions and Mysuru with 2.52 Millions. 
8. Mysuru is doing Exceptionally well even after having half of number of stores compared to other top two.
9. Bottom 3 Cities By Revenue Per store are Mangalore with 1.12 Millions, Trivandrum with 1.18 Millions and Vijayawada with 1.43 Millions.

### Promotions Analysis
1. Top 2 promotions by IR are 500 Cashback with 91 Millions and BOGOF 22 Millions.
2. Bottom 2 promotions by ISU are 50% OFF with 6.9k and 25% OFF with negative 5.7k.
3. There is significant difference in Cashback, BOGOF and %OFF Promotions.
4. In case Incremental revenue Cashback has 91 Million and Isu is 40k, BOGOF has IR of 22Millions and Isu 157K and %OFF has Negative IR -5.46 millions but Positive ISU 28.47K.
5. Also Cashback promotions  strike best balance between ISU and Sold Margins Beccause revenue per unit sold is 2227.
6. the 100% IR in category combo1 comes from Cashback promotions as it is only category and only promotion. the 100% IR in category Home Appliances comes from BOGOF promotions.
7. the 70% IR in category Grocery & Staples comes from BOGOF promotions and 30% from %OFF but it is negative.
8. the 85% IR in category Home Care comes from BOGOF promotions and 15% from %OFF but it is negative.
9. In Personal Care 100% IR Comes From %OFF but all is negative.

### Product and Category analysis
1. Top 3 Products by IR are P15 with 91 Millions P14 and P04 with 5 Miilions each. 85% od IR is generated by P15 because it is product with high base price.
2. Bottom 3 products by ISU are P09 with  -777, P06 with -735 and P05 with 556.
3. The Correlation between categories and promotions is all %off Promotions showing negative IR but BOGOF and Cashback promotions Showing positive IR.
4. in category Combo 1 cashback promotion is positively related. In Category Home appliances BOGOF Promotions is Positvely Related. In Category Personal Care %OFF Promotions is negatively Related. In Category Home Care %OFF Promotion is negatively and BOGOF Promotions is Positvely Related. Category Grocery & Staples %OFF Promotion is negatively and  BOGOF Promotions is Positvely Related.
5. The product categories which show significant lift in sales are Combo1 136% in IR , 183% in ISU and Home Appliances IR 82% and ISU 264%.
6. Also The Product P15(Atliq_Home_Essential_8_Product_Combo) with IR 134% and 183%, Product P14(Atliq_waterproof_Immersion_Rod) with IR 83% and ISU 266%, P13(Atliq_High_Glo_15W_LED_Bulb) with IR 81% and ISU 263% Has Done Exceptionaly well.
7. Also The Product P06(Atliq_Fusion_Container_Set_of_3) with IR -35% and ISU -14%, Product P05(Atliq_Scrub_Sponge_For_Dishwash) with IR 35% and ISU 13%, P09(Atliq_Body_Milk_Nourishing_Lotion (120ML)) with IR -36% and ISU 9% Has Done Exceptionaly poor.



