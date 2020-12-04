# Project_ETL

# Title: Best ever written books & best sellers. 
 
# Description:
For the use of the public in general and for those who love books, in this project a database was constructed and loaded into a database server. The main difference between this and other existing databases is that more fields are considered as part of the junction of three already cleaned sources of information: “List of best-selling books” retrieved 
from Wikipedia through web-scraping, Kagle website provides a CSV file (Goodreads-books) with clean information from Good Reads Api, and Britannica’s website is the 
source of the 12  Novels Considered the “Greatest Book Ever Written”. A database with 3 tables, 174 individual books, and 9 main characteristics is available in 
pgAdmin4 SQL format.  


# Dependencies and Setup
Pandas, BeautifulSoup, requests and from sqlalchemy import create_engine. 

# Resources
books.csv .- Downloaded from Kaggel, used to obtain the book's rating.                                                                                            
websites used for scraping purposes: https://www.britannica.com/list/12-novels-considered-the-greatest-book-ever-written
https://en.wikipedia.org/wiki/List_of_best-selling_books
