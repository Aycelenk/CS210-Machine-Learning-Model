# CS210-Machine-Learning-Model
IMDB DATASET
PREDICTING THE RATINGS

OUR AIM IS TO PREDICT THE RATINGS OF MOVIES DEPENDING ON THE DATA GIVEN TO US.
We begin by choosing our dataset, IMDB Movies because we find the topic interesting and predicting the rating is a crucial step for the movie industry.
Dataset accessed is maintained of 993 observations of movies from different genres, different timelines. We use 12 variables which are the information 
given about the movies in the columns of the dataset. We aim to predict the ratings, which determine the enlargement of the audience of the said movies, 
by attending variables to given information such as runtime, Metascores, votes. In case we predict correctly we print “Correct Rating!” The IMDB contains 
information of how the movies were liked by the audience, by providing ratings. Audience can vote from 1 to 10 depending on their interest in the movie. 
IMDB uses these numbers to calculate the movie’s rating. The Metascore is a weighted average of these calculations made by a sample size containing the 
famously known critics. In this sample group, the voting numbers are between 0-100. A runtime variable indicates the length of the movie in minutes.
The votes indicate the number of votes cast by the audience. This benefits the film or vice versa. These variables are the most critical ones in our prediction. 
Before moving further, we process the data in great detail to reach our final information to be used. In order to reach a clear, net outcome we analyze the data
to spot empty information. Therefore, we do data cleaning, resulting in some rows being deleted and some empty spaces being filled with calculated means.
