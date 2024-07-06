## 🍺 The Beer project  🍺 

Graph databases are a natural way of navigating distinct types of data. For this first project we will be taking a graph database to analyse beer and breweries!   

_For reference the dataset used for this project has been extracted from [kaggle](https://www.kaggle.com/ehallmar/beers-breweries-and-beer-reviews), released by Evan Hallmark. Even though the author does not present metadata on the origin of the data it is probably a collection of open data from places like [beeradvocate](https://www.beeradvocate.com/)_.

### Problem description

Explore the database via python neo4j connector and/or the graphical tool in the NEO4J webpage. Answer the questions with python syntax. Submit the results by following the instructions.


### Questions

1. How many distinct countries exist in the database? [Hint: mind repetitions]
1. Most reviews:  
    1. Which `Beer` has the most reviews?  
    1. Which `Brewery` has the most reviews for its beers? [Hint: 3-node path]
    1. Which `Country` has the most reviews for its beers? [Hint: 5-node path]
1. Who is/are the user/users that have the most shared reviews (reviews of the same beers) with the user CTJman?
1. Which Portuguese brewery has the most beers?
1. From those beers (the ones returned from the previous question), which has the most reviews?
1. On average how many different beer styles does each brewery produce?
1. Which brewery produces the strongest beers according to ABV? [Hint: database has NaN values]
1. If I typically enjoy a beer due to its aroma and appearance, which beer style should I try? (Justify your answer) [Hint: database has NaN values]
1. Using Graph Algorithms answer **one** of the following questions: [NB: make sure to clear the graph before using it again]
    1. Which two countries are most similiar when it comes to their **top 10** most produced Beer styles?
    2. Which beer is the most influential when considering the number of users who reviewed it? [Please use limit of 1000 on beer-review-user path]]
    3. Users are connected together by their reviews of beers, taking into consideration the "overall" score they assign as a weight, how many communities are formed from these relationships? How many users are in the largest community? [Please use limit of 1000 on beer-review-user path]]
1. Using Graph Algorithms answer **one** of the following questions:
    1. Which beer has the most similar reviews as the beer `Super Bock Stout`? [Hint:inspect two subsets: with and without the beer in question]
    2. Which user is the most influential when it comes to reviews made?
1. If you had to pick 3 beers to recommend using only this database, which would you pick and why? (Justify your answer) [Hint: database has NaN values]
