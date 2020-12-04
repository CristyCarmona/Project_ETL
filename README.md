# Project_ETL

# Title: Best ever written books & best sellers. 
 
## Description:
For the use of the public in general and for those who love books, a best seller and best everwritten books database was constructed and loaded into a server. The main difference between this and other existing databases is that more fields are considered as part of the junction of three already cleaned sources of information: “List of best-selling books” retrieved from Wikipedia through web-scraping, Kagle website provides a CSV file (Goodreads-books) with clean information from Good Reads Api, and Britannica’s website is the 
source of the 12  Novels Considered the “Greatest Book Ever Written”. A database with 3 tables, 174 individual books, and 9 main characteristics is available in 
pgAdmin4 SQL format.   

## Resources
books.csv .- Downloaded from Kaggel, used to obtain the book's rating.                                                                                            
websites used for scraping purposes: https://www.britannica.com/list/12-novels-considered-the-greatest-book-ever-written
https://en.wikipedia.org/wiki/List_of_best-selling_books

## Coding approach
![codingApproach](https://github.com/CristyCarmona/Project_ETL_Best_Seller_Books/blob/master/img/coding%20approach.jpg)

## Dependencies and Setup
Pandas, BeautifulSoup, requests and from sqlalchemy import create_engine.

## Database diagram 
![Diagram](https://github.com/CristyCarmona/Project_ETL_Best_Seller_Books/tree/master/img)
