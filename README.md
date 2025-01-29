# NPL
The aim of this project is to analyse reviews and provide insights into the general trends and patterns of customers. 

## Dataset Description
This dataset is an adaptation of the Amazon Books Reviews dataset from Kaggle.The dataset contains book reviews written by customers and contains a total of 11 features.Each row of the dataset corresponds to one review and the primary feature of analysis will be Reviews_text.
The features are:
Title: Book Title.
Book_Price: The price of Book.
Reviewer_id: ID of the user who rates the book.
Rating: Rating from 0 to 5 for the book.
Time: Time of the given review. Converted to seconds from some start date.
Review_title: The title/summary of the review.
Review_text: The full text of the review.
Found_helpful_ratio: Helpfulness rating of the review voted by other users. (Number of votes “Found Helpful” / Total number of votes.)
Publisher: Name of the publisher of the book.
First_author: The author of the book, or first in the list of authors if more than one.
Genre: The genre of the book.

## Methods
Data pre-processing and text mining techniques was used to prepare and draw insight from the text and to also produce informative visualization.
Sentiment Analysis techniques was used to understand and classify customer sentiment.
Topic modelling was then used to cluster reviews and similar expressions that best characterise customers in order to identify hidden trends within the text to better understand customer segmentation.
