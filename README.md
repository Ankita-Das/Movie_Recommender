# Movie_Recommender

Here I've made a movie recommender system using the [movie lens dataset](https://grouplens.org/datasets/movielens/). 
Although there are many other ways like content-based approach I've used only the collaborative filtering method. 

 *Please note:There are many library functions available for implementing recommender system but,here I've coded up the algorithms itself and haven't used any library function.* 
  
Here,I've used the **cosine similarity** measure to measure the similarity between 2 users(user-item similarity) and then 2 items(**item-item similarity**).

Following are the steps which I followed: 

1.Uploaded the files u.data,u.item.    
2.Loaded the data into pandas Dataframe.  
3.No of unique user and movies in the dataset is calculated.  
4.Preparing the user-item matrix with user id as rows-label and movie id as column-headers.  
5.Preparing of the item similarity matrix.Similarity measure used here is the cosine similarity .  
6.Taking input from the user about the no. of recommendations required and movie id he liked the most and then recommending other     movies accordingly!   

The last part is for prediction of ratings given the user id and the movie id.i.e.prediction : if the user would have seen that movie what rating he/she would have given!!!

