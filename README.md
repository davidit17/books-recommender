# books-recommender
scrape books data from simania and simple books recommender 

## first file : simania 

the first file is the scraper - gets books data from www.simania.co.il

and loads the data into csv file ( only for books with more than 1 review)

## source : 

<p align="center">
  <img src="img/simania2.JPG">
</p>

## as a row in the dataframe :

<p align="center">
  <img src="img/df.JPG">
</p>

## second file : recommender 

simple recommender (without users data)

based on weighted rating and optional variables like under 200 pages book , specific author and more . 

returns the top rated (weighted rating) N books.


