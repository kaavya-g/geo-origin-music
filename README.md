# geo-origin-music
Music is one of the most soul-soothing art forms in the history of human evolution. music is probably no longer just an art. It is extensively used in therapy, as it is known to have positive biological implications on the human body and mind. Throughout its lifespan, music has witnessed innumerable transformations, from starting as a note to the complex range of instruments and styles in which it is delivered. Music can hint at the social, political, and behavioral setting of society in a given period. Given the endless nuances of the importance of music, as it is can be both a cause as well as a consequence of human activity, understanding its origin and the subtle attributes constituting it can be crucial. In this project, we will be investigating whether we can predict the geographical origin of music using its audio features. We will be focusing on the distribution of music and the interrelations among various attributes using data mining techniques, which is generally referred to as geographical ethnomusicology. This is an interesting problem as it involves both regression and classification aspects to the target origin prediction. We will be training our model on training data set and validate the results using a separate test data. The first part of our project will be some data exploration to better understand the data followed by feature selection, which we expect will take a significant effort from our end. We will then build various models, tune the hyperparameters and validate the results. The major goal is to predict the geographical location of the music given by latitude and longitude. We also plan to identify special patterns that might give us insights about the relationship between unique attributes of music and the location.\newline
In this project we are working with Geographical Origin of Music Data from the UCI Machine Learning Repository. The dataset was built from a personal collection of 1059 tracks covering 33 countries/areas. The music used is traditional. Any Western music is not included because its influence is global. The program MARSYAS \cite{Tza} was used to extract audio features from the wave files. The default MARSYAS settings in single vector format (68 features) to estimate the performance with basic timbal information covering the entire length of each track. All features were transformed to have a mean of 0, and a standard deviation of 1. The last two columns of the dataset are the latitude and longitude, representing the place of origin of the music. A second version of the dataset also contains chromatic features which describe the notes of the scale being used, a distinguishing feature in geographical ethnomusicology. This dataset contains an additional 48 features making the total number of features 116\cite{7023456}. 
