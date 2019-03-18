# Topic-based-opinion-summarization-and-sentiment-analysis

We analyzed around 25000 Amazon reviews for mobile phones. Firstly, we scraped the reviews to create our dataset. Then, we formed clusters based on similar features for ex. battery, camera etc. using TFIDF. Later, we trained a Gated Recurrent Neural Network(GRNN) for the polarity of the reviews. We achieved a test accuracy of about 61%. We had 3 classes for the reviews namely positive, neutral and negative(sentiment) for each of the features. These three sentiment polarity clusters were created for each feature. A short summary of reviews in each of these clusters was created using extractive summarization. We used Maximum Coverage Minimum Redundancy approach to ease the comprehension for an individual. We implemented summarization as a 0/1 Knapsack Algorithm based on Branch and Bound approach. This project would be beneficial for people to decide whether to purchase the product, given the summary. A paper based on the same has been published successfully in ‘International Journal of Engineering Research and Applications’, Volume 8 - Issue 9 (Part 3) Sep 2018. 

Here's the link to our paper if you are interested in reading in depth.
Link: https://www.ijera.com/papers/vol8no9/p3/G0809035357.pdf

# Steps

1. 
