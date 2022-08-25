# Goodreads Book Recommender - Collaborative Filtering using Pearson Correlation Coefficient
Created by: Amanda Chen

## Description
Aim of the project is to:
* Conduct EDA to analyse the factors that could influence a book's rating

* Use Pearson Correlation Coefficient to explore various angles to make book recommendations to myself based on books I've previously read
  
  (1) User based: Find users whose ratings of the books I've read is the most similar to my ratings, then extract the books that these users have rated highly and I haven't read, for the final recommendation
  
  (2) Book based I: Recommend books whose ratings that have the highest correlation with a book of my choice
  
  (3) Book based II: Repeat (2) for every book that I've rated as 5, then sort by correlation and extract books with the highest score for the final recommendation

## Dataset
* Book metadata of 10,000 books from Goodreads
* Ratings from more than 53,000 users

Source: 

books_enriched dataset: https://github.com/malcolmosh/goodbooks-10k-extended

ratings dataset: https://github.com/zygmuntz/goodbooks-10k

## Technology used
* Python
* Jupyter Notebook

## Techniques used
* EDA
* Data cleaning
* Data preprocessing 
* Pearson correlation coefficient
