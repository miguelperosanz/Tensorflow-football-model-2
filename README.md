# Tensorflow-football-model-2

Script that uses the Tensorflow neural network to predict betting-odds in a football match using tensorflow. 
The script uses the team-ratings before every match from the FIFA videogame database. I collected the info from
the webpage but I have not uploaded it to Github. I don't really know if I am allowed to share it. The script should 
be executed in a Tensorflow environment (Firstenv). In a standard environment there might be issues when importing the 
Tensorflow library.

- The files "apuestas_teams_20xx" are the scripts used to get the data of every season that will be used as input in the 
neural network. At the moment 2018 and 2019. The database will probably be enlarged with more seasons in the future.
For summarizing, the script takes the ratings of the spanish, german and italian teams for every season and
combines it with the result of the match. The results of the matches are taken from the database of the webpage http://www.football-data.co.uk/data.php. After mixing both databases we have the info about corners, cards, betting-odds,
goals, combined with the rating skills of every team. The skills of every team are actualised every week in the data
base from EA Sports, which means, the ratings of the football teams are dynamic, depending on the last performances of
the teams. The combination of all the data is a long process and takes long time on a local computer. It might be a good idea
to work remotely in a big data environment like hadoop in order to speed up the creation of the files.
