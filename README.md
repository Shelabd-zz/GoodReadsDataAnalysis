# GoodReadsDataAnalysis
In this experiment, we investigate the effects of each feature of a book on it's average rating. 
Questions to pose for hypothesis are:

* Does the reoccurance of a book through different publications bias the rating?
* Does the ratings count and text review counts affect the rating 
* Does the popularity of the author affect the rating?
* Does the number of pages of a book affect its rating? 

### The motivation for the project (this should be a bit more detail -- why was this project chosen?):
In this experiment, we investigate the effects of each feature of a book on it's average rating. The main purpose of my                 investigation was to understand if book ratings actually give a proper representation of how good a book is.  
Questions to pose for hypothesis are:
* Does the reoccurance of a book through different publications bias the rating?
* Does the ratings count and text review counts affect the rating
* Does the popularity of the author affect the rating?
# The files:
* GoodReadsDataAnalysis.ipynb:
	 * Jupyter notebook with the data analysis conducted
* books.csv:
	 * A CSV of the list of 13,500+ books with the their bookID, Title, Author, ISBN, ISBN13, Average Rating, Ratings Count, Text Reviews Count, Language_code, Number of pages
* Readme.md:
	 * A short discription of the project and all it entails
	 
-----------------------------------------------------------------------------------------------------------------------------
# A summary of the results:
### With all relevant columns in place, I think its fair to now conclude that predicting the rating of a book based on the book's features is incoclusive. While the author's ranking, the number of pages and the ratings count as well as the text review count all play a factor in calculating an educated estimate of the rating, they are still not enough without the actual content of the book. Which is good news for book lovers :)
### So with the above colcuded we can now revise the initial hypothesis questions:

* Does the reoccurance of a book through different publications bias the rating? It does not as we investigated earlier, the results show that books that have been published many times dont necesarrily have higher than normal ratings (3.5-4.5 rating)
* Does the ratings count and text review counts affect the rating? Yes, but to a small degree as it is clear that the books with higher than average ratings count and text review count still fall within the normal range 
* Does the popularity of the author affect the rating? No, as we concluded earlier that the authors with higher rankings do not fall outside the normal range of 3.5-4.5
* Does the number of pages of a book contribute to the rating? To a small extent, it was clear that the number of pages between 200-400 is preferable by readers as a alrge number of books in that page range fall within the 3.5-4.5 rating range
