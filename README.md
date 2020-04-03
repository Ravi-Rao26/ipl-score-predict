# ipl-score-predict
The IPL - Indian Premerier League is a major cricket tournament held once every year during the summer time (April - June) in India. There are in total 9-10 teams participating in this tournament. The matches played are of 20 overs each. Each team play against each other twice as a part of round robin stage. Post the round robin stage top 4 teams qualify for the semi-finals followed by the finals between the winners of the semi final stage. The total number of matches played in the tournament are in the range 60 -70 (depending on number of teams participating). The T20 games are pretty exciting and given the nature of the IPL torunament, almost all the games go down the wire and thus these matches are never short of providing thrills to the public. Post end of 5 overs of every innings, projected score is calculated which is product of 20*Net Run Rate. Given the volatile nature of the game, it seldom happens that a team would arrive at the projected score at the end of 20 overs. This tournament began in 2008. There is a data of last 11 years (approx 750 matches).For each and every innings of the matches played, the innings score at the end of 5 overs and at the end of the 20 overs is available. Taking this data, an attempt has been made to create and train a ML model to predict the innings score at the end of 20 overs for a given innings score at the end of 5 overs. 

The dataset of IPL matches is available in two formats - .yaml files which were uploaded at a portal and the iptl20 portal which consists of match details in json format. The IPL matches in period 2008 till 2018 were considered for training the model. There are three notebook files. Notebook File 1 processes the .yaml files. Notebook File 2 is related to addition of additional variables to the training data set formulated out of .yaml files. Notebook File 3 processes the iplt20 files. Web scrapping is done in this file and the data is downloaded into json files and the json files are then processed to formulate the training data.  

This is a work in progress project. 
