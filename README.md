# Movie Recommendation System  


# PROBLEM STATEMENT :   
Build a good movie recommendation engine for users based on existing movie ratings using collaborative filtering approach.  

# ABOUT THE DATASET:  
        
The data can be found at  http://grouplens.org/datasets/movielens/100k/  
The dataset consists of:   
•	100,000 ratings (1-5) from 943 users on 1682 movies.   
•	Each user has rated at least 20 movies.  
•	Simple demographic info for the users (age, gender, occupation, zip)  

There is one more data set consisting of 1 million ratings. We will train our models on this data set also to see if accuracy of the model increases.     
The data was collected through the MovieLens web site (movielens.umn.edu) during the seven-month period from September 19th, 1997 through April 22nd, 1998. This data has been cleaned up - users who had less than 20 ratings or did not have complete demographic information were removed from this data set.  


# MODELS : 

1.	Alternative Least Squares Method (ALS)   
ALS is the most common and effective method in matrix factorization.   

2.	K- Nearest Neighbor Algorithm   
We used k-NN with cosine distance for classification. We can also use k-NN with Euclidean distance for classification.   

3.	Cosine Similarity:  
In cosine similarity we manually use the cosine distance formula for classification.     
This is the parameter by which we calculated the similarity score and number of users that have rated.  

# ANALYSIS & RESULTS: 
•	We saw that the user 6 liked the movies : Sense & Sensibility, Father of the Bride – part 2, Eye for eye and ALS recommended the movies : Police Academy, Lost Tango in Paris, Zero Dark Thirty.   
•	Thus, ALS recommended similar movies to the user 6 by learning that the user liked Thriller/Drama movies.   
•	We compared the recommendations from the K-NN with the IMDB recommendations and found 12 recommendations to be same out of the 20 for a movie “The Silence of the Lambs”.  
•	We used the similar approach for verifying the cosine similarity model with IMDB recommendations and found out that 3 of the 10 recommendations for the movie “The Silence of the Lambs” matched.  


