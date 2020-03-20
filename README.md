## Using Yelp dataset to help users find the best restaurants via sentiment analysis and recommendation system
Whenever I need recommendations for restaurants, I Yelp. However, it is really difficult for me to distinguish two restaurants with similar average star ratings. While there could be thousands of reviews for a given restaurant, it is impossible to go through all them to extract the insights. More importantly, I would love to get recommendations based on my preference. Therefore, I propose to investigate Yelp’s dataset, which includes ~7GB data of business details, user, customer reviews and photos. By using sentiment analysis and recommender algorithm, I hope to assist customers discover the best restaurants that they will like. Yelp’s dataset is avaliable from Yelp’s 2019 dataset challenge (https://www.yelp.com/dataset).

## Outline

1. **Import and explore Data** <br>
    1a. Read Yelp business data <br>
    1b. Read Yelp user review data <br>
    1c. Filter the Yelp business, only select Chinese Restaurant business <br>
    1d. Merge the chinese restaurant business dataframe with the customer review dataframe <br>

2. **Present customer review data using Word Clouds** <br>
    2a. Review text preprocessing, clean reviews <br>
    2b. A word cloud image for reviews of Chinese restaurants <br>

3. **A new feature (positive review ratio for restaurants) to help users choose restaurants using Sentiment Analysis** <br>
    3a. Clean reviews and perform sentiment analysis <br>
    3b. Calculate the positive review ratio for Chinese restaurants <br>
    3c. Explore the relationship between restaurant "stars" rating and positive review ratio <br>

4. **Restaurant recommender system** <br>
    4a. Build a recommendation engine With collaborative filtering <br>
    4b. Recommendation generation: obtain a list of restaurants for a given user based on his preference<br>

