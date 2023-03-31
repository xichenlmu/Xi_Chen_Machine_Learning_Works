The files contains a movie recommender for users built by using KNN model. The dataset has been used in this Python Notebook is a public scsv file published on Github with this link: https://github.com/ArinB/MSBA-CA-Data/raw/main/CA05/movies_recommendation_data.csv .
The data contains 30 movies, including data for each movie across 7 genres and their IMDB
ratings. The goal is to find 5 mivies from the dataset that are the most closed to these conditions conditions: The Post": IMDB Rating = 7.2, Biography = Yes, Drama = Yes, Thriller = No, Comedy = No, Crime = No, Mystery = No, History = Yes.
1. A dictionary of the conditions needs to be created as well as list of required columns we are specifically looking at.
2. transform the dictionary into a dataframe
3. create the train data for the model to extract
4. set the number of neighbors we are looking for, and build the model with KNN and using auto as the algorithm, the computer will use its default algorithm within the model we created
5. create a def function to define the 5 recommended movies, return and use indices[0] for finding the first variable of the list
6. use the above function to find the 5 recommended movies from the data, return the name and list of recommended movies to the user.
