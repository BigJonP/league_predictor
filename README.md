## league_predictor

The aim: to predict the outcome of a League of Legends game before the game actually begins. This will hopefully allow the player to understand his chances of success and help him decide whether he should dodge (leave the game) or not.


![Challenger](https://i2.wp.com/i.pinimg.com/originals/90/8f/95/908f95127caf7f739877f9f555807361.png)

Each notebook consists of the following:

1. #### [data_scraping.ipynb](https://github.com/BigJonP/league_predictor/blob/main/data_scraping.ipynb)
    * It uses the [Riot Games API](https://developer.riotgames.com/) to scrape data related to a specific player. Feel free to play around with the functions to choose whatever data you think is best (you can see all the data available to scrape with the RIOT API [here](https://developer.riotgames.com/apis#match-v4). Or you can just change the summoner name to your own, or whoever it is you are trying to predict games for.
   <br /> 
   <br /> 
    * *Keep in mind the API keys need to be regenerated every 24 hours, so the key used in the source code won't work. Thankfully anyone with a RIOT Games account can generate an API key [here](https://developer.riotgames.com/app-type).*
   <br /> 
   <br /> 
2. #### [EDA.ipynb](https://github.com/BigJonP/league_predictor/blob/main/EDA.ipynb)
    * This notebook explores the data collected in the previous notebook. It also cleans the data and manipulates certain values in order to prepare the data for modelling. 
   <br />  
   <br /> 
3. #### [modelling.ipynb](https://github.com/BigJonP/league_predictor/blob/main/modelling.ipynb)
    * Finally this notebook models the data and looks at several models in a cross test validation to determine the most effective one. 
    
   <br /> 
   <br /> 
   

As you can see the accuracy is quite weak. It would be really cool if fellow league players can pursue the efforts of climbing the ladder (winning games) by implementing data analysis, so feel free to play with the code and share any discoveries you make!
