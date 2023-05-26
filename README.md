# Recommendation-system-comparision
Will compare two types of recommendation on a movie dataset from group lens


## Collaborative Recommender system

Collaborative recommender systems aggregate ratings or recommendations of objects, recognize commonalities between the users on the basis of their ratings and generate new recommendations based on inter-user comparisons. The greatest strength of collaborative techniques is that they are completely independent of any machine-readable representation of  the objects being recommended and work well for complex objects where variations in taste are responsible for much of the variation in preferences. Collaborative filtering is based on the assumption that people who agreed in the past will agree in the future and that they will like similar kinds of objects as they liked in the past.

## Content-based Recommender System:  
Content-based filtering works on the principle that if you like a particular item, you will also like this other item. To make recommendations, algorithms use a profile of the customer’s preferences and a description of an item (genre, product type, color, word length) to work out the similarity of items using cosine and Euclidean distances.  
The downside of content-based filtering is that the system is limited to recommending products or content similar to what the person is already buying or using. It can’t go beyond this to recommend other types of products or content. For example, it couldn’t recommend products beyond homeware if the customer had only brought homeware.

## Hybrid Recommender System: 
A hybrid recommendation engine looks at both the meta (collaborative) data and the transactional (content-based) data. Because of this, it outperforms both. In a hybrid recommendation engine, natural language processing tags can be generated for each product or item (movie, song), and vector equations used to calculate the similarity of products. A collaborative filtering matrix can then be used to recommend items to users depending on their behaviors, activities, and preferences. Netflix is the perfect example of a hybrid recommendation engine. It takes into account both the interests of the user (collaborative) and the descriptions or features of the movie or show (content-based).


# Dataset -

The dataset is from the MovieLens dataset collected by the GroupLens Research Project at the University of Minnesota. 
This data set consists of:
	* u.data
	* u.item
	* u.genre


# Analysis Design Comprises of –
  •	Importing Data
  •	Creating Tagwords
  •	Scrapping related Tweets
  •	Cleaning Tweets
  •	Performing Sentiment Analysis
  •	Building Collaborative filter based recommender system
  •	Exploratory Data Analysis
  •	Adding Embedding Layer
  •	Evaluating Results
