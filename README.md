## Recommender systems 
 They are one of the most successful and widespread application of machine learning technologies in business. You can find large scale recommender systems in retail, video on demand, or music streaming.

Examples of recommendation systems are:
  1. Offering news articles to on-line newspaper readers, based on a prediction of reader interests.
  2. Offering customers of an on-line retailer suggestions about what they might like to buy, based on their past history of purchases and/or product searches.
  3. Recommending movies to user based on there previous watch
  
# Aim 
The main aim of this project is to develop a hybrid movie recommender system that: 
         • incorporates and enhances the properties of existing recommendation systems
          • Adapt new approaches in order to decrease system runtime
          • Reveal latent user and movie relations with great accuracy. 
 To achieve this,I have to evaluate all the existing recommendation techniques to find better models which can be fused with our hybrid recommendation model.

# Dataset 

Dataset : Movielens
https://grouplens.org/datasets/movielens/100k

# Algorithms Implemented
     1. Content based filtering
     2. Collaborative Filtering
          2.1. Memory based collaborative filtering
                 2.1.1. User-Item Filtering
                 2.1.2. Item-Item Filtering
         2.2. Model based collaborative filtering
                2.2.1. Single Value Decomposition(SVD)
                2.2.2. SVD++
    3. Hybrid Model
           Content Based + SVD
