# Yelp Elite Member Classifier

1. Yelp is well known as the most popular tool used by people to discover new places through reviews. 
2. For engagement they added the social aspect to their business. Eg. “Friends”
feature, a “Fans” feature, votes and likes on reviews and much
more. 
3. In this probelm I am intrested in a unique social feature **Elite use** feature.
4. They are basically handpicked by the yelp who are most active and produce exceptional reviews
5. With more and more users who want to become part of the club has created the tough competetion for user to become elite.
6. So yelp on daily basis recieves lot of applications especially from the young yelpers
7. I want to automate this process with building a model which help selecting the members to elite.
8. Until this stage, the model is designed for low false positive. That means the classifier will be more active in not predicting 
non-elite to be elite.

# Approach
1. For the work I have used google colab jupyter envoirment.

2. I first performed some basic analysis to get the gist of the different datasets from the yelp. Exploration is performed using 
python, pandas and matplotlib. BasicExploration.ipynb file shows the report for mostly two datsets. User and Business

3. I formulated the problem statement in problemstatement.ipynb where I further looked more into patterns of being elite from
prespective of review_count. 

4. As the dataset in our hand was quite imbalanced. I tried going with the approach of undersampling. Classifier building is in
classifier.ipynb






