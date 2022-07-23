# Goodreads_EDA_Miniposter
Presenting interesting insights with plots after performing Exploratory Data Analysis (EDA) on Goodreads popular books dataset.

#### Plots are visible in the following files :

1.Powerpoint Presentation (Mini_Poster.pptx): (https://github.com/kapilsahukp/Goodreads_EDA_Miniposter/blob/main/Mini_Poster.pptx)

2.Report(Mini_Poster.pdf): https://github.com/kapilsahukp/Goodreads_EDA_Miniposter/blob/main/Mini_Poster.pdf

#### Title:
     Analyzing Goodreads Dataset to gain interesting insights about factors impacting the popularity of Books

#### Dataset Description: 

     The data set used for analysis is collected from the Goodreads database(Goodreads API)
     and is available on Kaggle. A brief description of data available in it is below:

     **bookID**: Contains the unique ID for each book/series
     **title**: contains the titles of the books
     **authors**: contains the author of the particular book
     **average_rating**: the average rating of the books, as decided by the users
     **ISBN**: ISBN(10) number, tells the information about a book - such as edition and publisher
     **ISBN 13**: The new format for ISBN, implemented in 2007. 13 digits
     **language_code**: Tells the language for the books
     **Num_pages**: Contains the number of pages for the book
     **Ratings_count**: Contains the number of ratings given for the book
     **text_reviews_count**: Has the count of reviews left by users

#### Observations:

#### 1. Plot 1 (Relationship between average rating and review count): 

     It is a scatter plot from which we can infer that most of the ratings for the books seem to lie near 3-4, 
     with a heavy number of reviews lying mostly near 5000, approx. Hence, we need to look closely at the area 
     where the review count is below 5000 to get some insights.

#### 2. Plot 2 (Relationship between average rating and review count <5000):
     This scatter plot is a kind of magnified version of plot 1 where we are looking at observations where 
     the review count is less than 5000. Even after looking at a smaller scale, most text reviews for books 
     still lie under 1000, making data results inconclusive. The reviews seem to be predominant amongst books 
     with good ratings. Maybe this is pointing towards a possibility that these are all fake reviews. 
     Fake reviews are usually posted to promote a product in the market and hence are not from genuine readers
     which is somewhat self-explanatory since most of the time, bibliophiles don't just rate a book, 
     they also share their honest reviews no matter positive or negative to help the community grow.

#### 3. Plot 3 (Top 10, Most rated books): 
     Here we are looking at the top 10 books with the most reviews. The first book of any series usually has most
     of the ratings, i.e, Harry Potter and the Sorcerer’s Stone, Twilight #1, The Hobbit, Angels and Demons #1. 
     However, A huge gap in ratings(approx. 50%) of Harry Potter(#1) and  Harry Potter(#2) indicates that fiction 
     enthusiasts did not pick up the sequel in the series as much as they liked the first one. 
     This is quite interesting as generally, people eagerly wait for a sequel of a book if the first part is a 
     big hit and authors expect a positive response mostly. But this data tells otherwise. 
