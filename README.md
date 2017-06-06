# imdbcrawler
this is a set of py for crawling data from imdb.\
1.run step1_getDoubanMovies step2_getScore and step3_getInfoOfOneMovie to get a imdbid list of movies from douban api.\
2.run imdb1 to get movie data from omdb\
3.run imdbuser to get a user id list via the id list we get from 1.\
4.run imdbdata3 to get user comments via the user id list we get from imdbuser\
5.run modify data to quantify the raw movie data from 2.\
6.run knn to calculate the nearest neighbor based on the data of 5\
7.run knnOverNumber to calculate nearest neighbor performance over number of user's commented movies\
