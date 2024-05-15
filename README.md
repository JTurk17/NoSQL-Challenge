# NoSQL-Challenge

This Challenge was done in 3 parts.

PART 1:

I loaded the data into mongo, creating a new database and collection. I saved the created collection into a variable to be used throughout the code.

PART 2:

I updated the collection with a new establishment. From there I did a bit of cleaning. I got rid of any documents with "Dover" in their Local Authority Name. Then I updated the longitude and latitudes to doubles, and the rating values to integers.

PART 3: 

Using the cleaned collection I answered the following questions:

1. Which establishments have a hygiene score equal to 20?
2. Which establishments in London have a RatingValue greater than or equal to 4?
3. What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
4. How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.
