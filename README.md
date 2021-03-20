# Recommendations_with_IBM
This project analyzes the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles they may like.The project contains several parts of data exploration and recommendations for any users.

# Installations
To continue with our tasks the following Python libraries have been utilized.
This project requires Python 3.x as well.

* Nltk
* Pandas
* Seaborn
* scikit-learn
* pickle
* re

# Tasks
The project contains the following tasks:

* Exploratory Data Analysis: This part is for data exploration before any recommendations could be made.
* Rank Based Recommendations: TTo get started in building recommendations, I will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).
* User-User Based Collaborative Filtering: In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. 
* Content Based Recommendations: Using NLP skills, I developed a content-based recommendation system.
* Matrix Factorization: Finally, I completed a machine learning approach to building recommendations. Using the user-item interactions, I built out a matrix decomposition. Using the decomposition, I got an idea of how well I can predict new articles an individual might interact with.


# Dataset:
* user-item-interactions.csv: file contains user interaction.
* articles_community.csv: file contains articles description.

# Acknowledgements
I am really thankful that I had an opportunity to work on such recommendations engine building where users can easily can recieve idea about new article per thier taste and interest. Data Scientist Udacity Nanodegree program has provided necessary lessons and helped to develop such skillset. I also get some idea from following resources when I need any clarification.

 * https://github.com/joshxinjie/Data_Scientist_Nanodegree/tree/master/ibm_recommendations
 * 



