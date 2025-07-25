### Blinkit Sales & Store Analysis (Excel-Based Project)

This Project is a complete Excel -based data analysis of a simulated Blinkit (grocery delivery) dataset. The goal is to extract insights on product sales ,store performance, and key business metrics using Excel tools such as Pivot Tables, Charts and Functions. It demonstrate skills in data cleaning, transformation, and dashboard creation - ideal for a data analyst role.

### Objective
-- To explore and visualize data of Blinkit delivery application
-- To practice data cleaning, transformation and storytelling using real-world project


### Tools & Techniques Used

***Excel Function*** -- IF,AVERAGEIF,MODE,PROPER,COUNTIF,OR
***Pivot Tables*** -- Grouping, Sorting, Filtering
***Charts*** -- Bar, Pie,Slicers
***Data Cleaning*** -- Missing value handling, standardization

### Analysis Performed
-- Summary Metrics ( using Formulas) 
1) Total Revenue
2) Total Unique Products and Store
3) Most Frequent Store Size

   
-- Pivot Table Analyses (sheet- Pivot_Table_Analysis) 
1) Revenue by Product_Category
2) Revenue by Store_ID
3) Average Product Weight by Category
4) Slicer by Store_Type and City Tier 

-- Data Cleaning (sheet- Original_data_transformation_in
1) Product_Weight_grams_Check : IF(B2="", $P$3,B2)
   Converting null value  into Average 
2) Health_Tag_Check
    Converting this into Unknown 
3) Product_Visibility_ShelfShare_Check
   Converting null value into Average
4) Store_Opening_Year_Check
   Converting null value into Mode value
5) Store_Size_sqFT
   Converting null value into Mode value
6) Cleaning Heath_Tag_Check Column:
   Converting LF : Low Fat
              reg : Regular
              regular : Regular
7) Removed Duplicates
8) Converted into proper format
   
    
### Dashboard Example (sheet- Chart_1, Chart_2)
Bar Chart : Top 10 Categories by Revenue (Slicer: Store_Type, City_Tier)
Pie Chart : Store Age by Store Type
Bar Chart : Revenue by Store Type

### Dataset 
Kaggle [https://www.kaggle.com/datasets/mukeshgadri/blinkit-dataset]






