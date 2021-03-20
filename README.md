# Recommendations_with_IBM
This project analyzes the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles they may like.The project contains several parts of data exploration and recommendations for any users.

# Installations
To continue with our tasks the following Python libraries have been utilized.
This project requires Python 3.x as well.

*1. Nltk
*2. Pandas
*3. Progressbar
*4. Seaborn
*5. scikit-learn


# Tasks
The project contains the following tasks:

1. Exploratory Data Analysis: This part is for data exploration before any recommendations could be made.
2. Rank Based Recommendations: To get started in building recommendations, I first find the most popular articles based on the most interactions. These are then the articles we might recommend to new users (or anyone depending on what we know about them).
3. User-User Based Collaborative Filtering: In order to build better recommendations for the users of IBM's platform, I look at users that are similar in terms of the items they have interacted with. These items could then be recommended to similar users.
4. Content Based Recommendations: Using NLP skills, I developed a content-based recommendation system.
5. Matrix Factorization: Finally, I completed a machine learning approach to building recommendations. Using the user-item interactions, I built out a matrix decomposition. Using the decomposition, I got an idea of how well I can predict new articles an individual might interact with .
