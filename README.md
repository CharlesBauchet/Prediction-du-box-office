# Prediction-du-box-office
Il s'agit du projet 8 de la formation DATA Analyste de chez OpenClassRooms

### Lecture des dashboards

Il faut avoir le logiciel Tableau Public 2021.4 pour pouvoir les lires

### Dataframes

Train.csv => est un dataframe qui va nous permettre de travailler notre modèle de prédiction de revenus avec toutes les informations utile à cette problèmatique

Test.csv => est un dataframe ou il manque la variable 'revenue' et qui est notre objectif 

Sample_Submission => est un exemple de ce que l'on attends de cette étude avec 2 variables 'id' qui correspond à l'identifiant du film et 'revenue' qui sera la prédiction de revenue du film
 


### Description des variables

Data Description id - Integer unique id of each movie

belongs_to_collection - Contains the TMDB Id, Name, Movie Poster and Backdrop URL of a movie in JSON format. You can see the Poster and Backdrop Image like this: https://image.tmdb.org/t/p/original/. Example: https://image.tmdb.org/t/p/original//iEhb00TGPucF0b4joM1ieyY026U.jpg

budget:Budget of a movie in dollars. 0 values mean unknown.

genres : Contains all the Genres Name & TMDB Id in JSON Format

homepage - Contains the official homepage URL of a movie. Example: http://sonyclassics.com/whiplash/ , this is the homepage of Whiplash movie.

imdb_id - IMDB id of a movie (string). You can visit the IMDB Page like this: https://www.imdb.com/title/

original_language - Two digit code of the original language, in which the movie was made. Like: en = English, fr = french.

original_title - The original title of a movie. Title & Original title may differ, if the original title is not in English.

overview - Brief description of the movie.

popularity - Popularity of the movie in float. => pour savoir comment est calculer la valeur de cette variable https://developers.themoviedb.org/3/getting-started/popularity

poster_path - Poster path of a movie. You can see the full image like this: https://image.tmdb.org/t/p/original/

production_companies - All production company name and TMDB id in JSON format of a movie.

production_countries - Two digit code and full name of the production company in JSON format.

release_date - Release date of a movie in mm/dd/yy format.

runtime - Total runtime of a movie in minutes (Integer).

spoken_languages - Two digit code and full name of the spoken language.

status - Is the movie released or rumored?

tagline - Tagline of a movie

title - English title of a movie

Keywords - TMDB Id and name of all the keywords in JSON format.

cast - All cast TMDB id, name, character name, gender (1 = Female, 2 = Male) in JSON format

crew - Name, TMDB id, profile path of various kind of crew members job like Director, Writer, Art, Sound etc.

revenue - Total revenue earned by a movie in dollars.
