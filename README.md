# Assignments
Assignment 1 : Data Exploration
## 1. Sum, Count, Average:

   *. What is the total price of all products in the dataset?
          <br>The sum of product price  is calculated by using SUM() Function. Used Syntax is =SUM(D2:D35) .Then get output is 10100 .
     
  *. How many products are there in the dataset?
         <br>Total number of products are founded using COUNTA() function. The COUNTA function in Excel counts cells that are not empty. Used syntax is =COUNTA(B2:B35).Then get total number of products is  : 34.
 
   *. Calculate the average price of the products.
          <br>The average Prize of Products are calculated by using AVERAGE() function in excel. It returns the arithmetic mean of a set of numbers. Used syntax is =AVERAGE(D2:D35).Then get output is :297.0588235 .By using Round function we can short the average. =ROUND(D40,1) applied on Average Value , The final output is 297.1.  
        
## 2. Min and Max:

*. Determine the minimum price among all products.  
        <br>The minimum price among all products are calculated by using MIN().The MIN function extracts the lowest or smallest value from a range of cells or cell references.Used syntax is =MIN(D2:D35).The output is 30. 

*. Find the maximum price among all products.  
       <br>The  maximum price among all products are calculated by using MAX().The MAX function Returns the largest value from a range of cells. Used syntax is =MAX(D2:D35).The maximum price is 1000.
     
## 3. IF Function:

 *. Using an IF function, create a new column named Price Range to categorize products with a price greater than or equal to $500 as 'High Price' and others as 'Standard Price'.
        <br>First create a column named price range . By using If function categorize products with a price greater than or equal to $500 as 'High Price' and others as 'Standard Price'. We used syntax is =IF(D2>=500,"High Price","Standard Price").The Output displayed based on price of product.If you drag it down, the values in the cells below will also update.
 
## 4. SUMIF and COUNTIF:

*.Calculate the total price for products in the 'Electronics' category using the SUMIF function. 
       <br>The total price of products in electronics can be calculated using SUMIF().Used syntax is =SUMIF(F2:F35,"Electronics",D2:D35).The output is 8050.
     
*.Determine the count of products with a price less than $100 using the COUNTIF function.
      <br>The products with a price less than $100 can be calculated using COUNTIF().Used syntax is =COUNTIF(D2:D35,"<100"). The output is 11.
    
## 5. Text Formatting - LEFT, RIGHT, MID:

*.Create a new column named Day with the first 2 characters of each 'Product ID' using the LEFT function.  
     <br>  First create a column named Day. By using LEFT function display the first 2 characters of each 'Product ID'. Used syntax is =LEFT(A2,2).It return first 2 characters of each 'Product ID'. If you drag it down, the values in the cells below will also update.
   
*.Create a new column named Country Code by extracting the last 2 characters from the 'Product ID' column using the RIGHT function.  
     <br>  First Create a column named Country Code. By using RIGHT function display the last 2 characters from the 'Product ID'. Used syntax is =RIGHT(A35,2).It return the last 2 characters from the 'Product ID'. If you drag it down, the values in the cells below will also update.
   
*.Create a new column named Month by extracting 4th to 6th characters from the 'Product ID' column using the MID function.
       <br>First Create a column named Month. By using MID function display the 4th to 6th characters from the 'Product ID'. Used syntax is =MID(A2,4,3).It return 4th to 6th characters from the 'Product ID'. If you drag it down, the values in the cells below will also update.
