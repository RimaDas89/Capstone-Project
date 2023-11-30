# Capstone-Project
SHOE BRAND CAPSTONE Project

1. **Web Scraping:** Extract shoe data from specified URLs using BeautifulSoup and Selenium.
2. **SQL Queries:** Create CSVs and write SQL queries for specific insights.
3. **EDA:** Merge CSVs with pandas, and analyze data using stats and visualizations.
4. **Machine Learning:** Predict shoe prices and star ratings using regression and classification models. Apply scaling and hyperparameter tuning. Save the best models on GitHub. Follow the submission guidelines carefully.

## Phase1: 21 marks
Web scrapping the below given six URL :
1. https://www.nike.com
2. https://www.adidas.com
3. https://us.puma.com/us/en
4. https://www.skechers.com
5. https://www.columbia.com/
6. https://www.woodlandworldwide.com/

## Phase 2   (15 SQLqueries *1 each) + (7 join queries*2 ) = 29 marks
Make the table in  csv format  (3 csv files)  

1. **Table1.csv:** ShoeName ,Category(Men/Women), no.of colors,price  
2. **Table2.csv:** count of sizes, colors 1, color 2, color3 ,color4, color5, Style code/product code  
3. **Table3.csv:** reviews, Size, comfort, durability /quality/performance(quantification), star rating

## Write the SQL queries :

1. **Table 1**          
  * Write a query  to retrieve all shoe names and their corresponding prices for men's shoes:
  * Write a query to retrieve the number of different colors available for each category.
  * Write a query to find the most expensive men's shoe.
  * Write a query to find the cheapest women's shoe in a specific color (e.g., 'Black ').
  * Write a query to retrieve all shoe names and their corresponding prices for men's shoes.

2. **Table 2**
  * Write a query that retrieves the count of sizes for all styles.
  * Write a query to list all styles with their associated colors.
  * Write a to find styles that have more than one color.
  * Write a query to find the count of sizes available for each color for a specific style code.
  * Write a query to find styles that have a specific color.

3. **Table 3**
  * Write a query that calculates the average comfort rating for a specific product based on its reviews.
  * Write a query to retrieve products with high star ratings (e.g., 4 stars or above)
  * Write a query that counts the number of reviews for each product.
  * Write a To retrieve products that have a quantified durability/quality/performance rating above a certain threshold (e.g., above 7).
  * Write a query that  calculates the average comfort rating for each size.

**7  Join SQL Queries  using all 3 tables**
  * Write a query to find the top-rated men's shoes along with their sizes from "Table1" and "Table3."
  * Write a  query that calculates the average comfort rating for each category from "Table1" and "Table3."
  * Write a  query that identifies products with a durability/quality/performance rating higher than the average from "Table1" and "Table3."
  * Write a  subquery that finds products with comfort ratings above the average comfort rating using "Table1" and "Table3."
  * Write a  query that joins Table 1  and Table 2  using the "Style code/Product code" column, allowing you to retrieve shoe information along with product details.
  * Write a  query that  identifies products with a star rating above the average star rating for their respective size.
  * Write  a  query that finds products with the highest comfort rating in each category.

## Phase  3
* Now make only 1 dataframe of 3 CSV files using the concat/merge /join operation of pandas and start doing EDA.
* Do the complete EDA in detail to explore the insights of data and write the detailed observations of each analysis.

## Phase 4
Write the complete Machine learning code to make predictions of price and star rating. Use appropriate models on their label basis. Remember you need to make 2 different predictions:
* price
* star rating.

Apply all the best techniques of scaling, and hyperparameter tuning, and avoid underfitting or overfitting (bias/variance)
In the end, save the best model and convey on which basis you have chosen that model. 

**Submission guidelines:**
You need to submit  only 3 files in Github. Only the Github link will be accepted:
  1. File 1:  web scraping phase 1 file
  2. File 2:   SQL Queries phase 2 file
  3. File 3: EDA and Machine Learning  file.






 



 



 

