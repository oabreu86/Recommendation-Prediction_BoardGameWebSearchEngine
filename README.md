##Board Game Recommendation & Success Prediction Web Search

Please go to the file 'dcarbone-jmidkiff-oabreu-syedajaisha.pdf' for a full description of this project. 

  Our work intends to tackle two problems related to tabletop board games: obtaining personalized recommendations for consumers interested in new titles and, predicting success rates for games in development and making recommendations to improve the same. To build these systems, we used data from BoardGameGeek, www.boardgamegeek.com, a website that aggregates user ratings and game information for 100,000+ boardgames. We scraped a list of the top 5,000 titles ordered by total number of ratings. Afterwards, we used the site’s own API to build a database of these games and their characteristics, listing variables such as type of game, recommended number and age of players, and game difficulty, among others.
  
  Based on this data, we implemented a search functionality through which users describe the board games they’re interested in, as well as their preference for popular vs. critically acclaimed titles, and receive a personalized list of the top five releases that meet their criteria, as well as some of their characteristics. Finally, we created two predictive systems which, based on a number of inputs (unique to each model with some overlaps) foresee either the number of BoardGameGeek user ratings a future title might have, or its projected aggregate rating. In order to contextualize these results, we also provide the relative rank such a game would take within BoardGameGeek’s popularity and rating metrics.
