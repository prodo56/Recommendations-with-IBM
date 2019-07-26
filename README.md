# Recommendations with IBM

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [Project Components](#projectComponents)
4. [Licensing, Authors, and Acknowledgements](#licensing)

### Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python. The code should run with no issues using Python versions 2.*.

### Project Motivation <a name="motivation"></a>
In this project, I have applied Data Science skills to analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles you think they will like.


### Project Components <a name="projectComponents"></a>
There are three components in this project.

1. Exploratory Data Analysis

	- Before making recommendations of any kind, you will need to explore the data you are working with for the project. Dive in to see what you can find. There are some basic, required questions to be answered about the data you are working with throughout the rest of the notebook.
	- What is the distribution of how many articles a user interacts with in the dataset?
	- The number of unique articles that have an interaction with a user.
	- The number of unique articles in the dataset (whether they have any interactions or not).
	- The number of unique users in the dataset. (excluding null values)
	- The number of user-article interactions in the dataset.

2. Rank Based Recommendations
	
	- We will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

3. User-User Based Collaborative Filtering

	- In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users.
  
4. Matrix Factorization

	- Finally, we will complete a machine learning approach to building recommendations. Using the user-item interactions, we will build out a matrix decomposition. Using our decomposition, we will get an idea of how well you can predict new articles an individual might interact with.


### Licensing, Authors, and Acknowledgements <a name="licensing"></a>

* [Udacity](https://www.udacity.com/)
